# Smart India Hackathon Workshop
# Date:25-11-2026
## Reference Number:26019643
## Name:RAJASREE.M

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
KisanDirect is a mobile and web marketplace that connects farmers and FPOs (Farmer Producer Organisations) directly with consumers, retailers, restaurants and bulk buyers. It adds pooled delivery support and uses AI for demand forecasting and route optimization.

1. Detailed explanation of the proposed solution
- Farmer / FPO app: voice-enabled, regional-language crop listing with quantity, grade, price and harvest date. It shows the current mandi price so farmers can price fairly.
- Buyer app: search by crop, location and quantity. Supports single, bulk and weekly subscription orders.
- Logistics support: nearby orders are pooled into one vehicle and picked up from FPO collection centres or village pickup points.
- AI engine: demand forecasting (what will sell, where and when) and route optimization for deliveries.
- Price transparency: every order shows the split between farmer share, transport cost and platform fee.

2. How it addresses the problem
- The usual chain is farmer to local trader to wholesaler to retailer to consumer, and each step adds a margin. Selling directly removes most of these layers, so farmers earn more and consumers pay less.
- Pooled deliveries and optimized routes cut transport cost and spoilage.
- Demand forecasting helps farmers avoid unsold produce and sudden price crashes.

3. Innovation and uniqueness of the solution
- Marketplace, logistics and AI combined in one flow.
- Voice and regional-language interface for low-literacy farmers.
- Visible price breakdown (farmer share vs. consumer price).
- Pooled delivery from village clusters to consumers.
- FPO-first design, so small farmers can sell in bulk.
- Works with existing government platforms (e-NAM, ONDC) instead of competing with them.

## Technical Approach
1. Technologies to be used
- Frontend: React.js or HTML / CSS / JavaScript
- Mobile: Flutter or React Native (or a responsive web app)
- Backend: Python (Django or FastAPI)
- Database: PostgreSQL or MySQL
- AI / ML: Python, scikit-learn, Prophet / ARIMA (forecasting), Google OR-Tools (route optimization)
- Maps: OpenStreetMap or Google Maps API
- Language and voice: Bhashini API or Google Translate, Speech-to-Text
- Payments: UPI / Razorpay (test mode)
- Data sources: Agmarknet and data.gov.in mandi prices, weather API

2. Methodology and process for implementation
- Step 1: Farmer or FPO registers and lists the crop.
- Step 2: The system shows a suggested price from mandi price data.
- Step 3: The buyer searches, orders and pays.
- Step 4: The AI engine groups nearby orders and finds the best route.
- Step 5: A delivery partner collects the produce and delivers it.
- Step 6: The farmer is paid directly, and ratings are recorded.
- Step 7: Order history feeds back into the demand forecasting model.

Flow: Farmer / FPO -> Crop listing -> Platform (price guidance + AI) <- Buyer order -> Pooled route optimization -> Delivery to buyer -> Direct payment to farmer

## Feasibility and Viability
1. Analysis of the feasibility of the idea
- All proposed tools are open source or have free tiers.
- Government data on mandi prices is publicly available.
- Smartphone and UPI use in rural India is growing.
- Possible revenue: a small commission, delivery fees and bulk-order subscriptions.

2. Potential challenges and risks
- Low digital literacy among farmers.
- Perishability and quality variation of produce.
- Last-mile logistics cost.
- Trust and payment delays.
- Poor internet connectivity in villages.
- Resistance from existing traders.

3. Strategies for overcoming these challenges
- Voice-based regional-language UI, with FPOs and village agents helping onboarding.
- Grading standards, cold storage tie-ups and fast delivery.
- Pooled delivery and village-cluster collection points.
- Ratings and quick UPI payout.
- Offline-first app and SMS / WhatsApp ordering.
- Give existing traders a role as local collection agents.

## Impact and Benefits
1. Potential impact on the target audience
- Farmers / FPOs: a larger share of the final price, faster payment and guidance on when to sell.
- Consumers: fresher produce at lower prices with transparent pricing.
- Bulk buyers: reliable supply and bulk contracts.
- Government: better data for planning and price monitoring.

2. Benefits of the solution (social, economic, environmental, etc.)
- Economic: higher farmer income, lower consumer prices, new local jobs for delivery and village agents.
- Social: empowers small farmers and FPOs and reduces middleman exploitation.
- Environmental: less food waste, and fewer, fuller delivery trips mean lower fuel use.

## Research and References
1. Details / Links of the reference and research work
- RBI working papers estimate farmers get about 33% of the consumer rupee for tomatoes, 36% for onions and 37% for potatoes (Rajya Sabha Q. 508, 29 Nov 2024): https://rsdebate.nic.in/bitstream/123456789/753870/1/PQ_266_29112024_U508_p931_p932.pdf
- e-NAM had integrated 1,656 mandis, with over 1.8 crore registered farmers and 4,724 FPOs (PIB, April 2026): https://static.pib.gov.in/WriteReadData/specificdocs/documents/2026/apr/doc2026413845801.pdf
- 7,901 FPOs were onboarded on ONDC as of October 2024 (same Rajya Sabha reply above).
- e-NAM portal: https://enam.gov.in
- Agmarknet (mandi prices): https://agmarknet.gov.in
- Open Government Data Platform: https://data.gov.in
- ONDC: https://ondc.org
- Bhashini (Indian-language AI): https://bhashini.gov.in
- Google OR-Tools (route optimization): https://developers.google.com/optimization
