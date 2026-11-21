# Smart India Hackathon Workshop
# Date:21-11-2026
## Reference Number:26019228
## Name:NAVEENKUMAR M

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
1. Detailed explanation
A mobile-first, multilingual marketplace (working name FarmDirect) with three user groups:

Farmers/FPOs list produce with quantity, grade, photos, harvest date and expected price, using voice or regional-language input. A price guide based on live mandi rates helps them set a fair price.
Consumers and bulk buyers (households, restaurants, retailers, hostels, institutions) browse nearby produce, place one-time or subscription orders, or post bulk requirements for farmers to bid on.
Logistics partners (local transporters, cold-chain and last-mile agents) accept pooled pickups and deliveries through the app.

Core modules: listing and quality grading, order matching, pooled logistics, digital payments with escrow, and an AI engine for demand forecasting and route optimization.

2. How it addresses the problem

Removes layers of commission agents by connecting producer and buyer directly.
Shows transparent pricing, so farmers see the buyer price and buyers see the farmer's share.
Pools orders to reduce transport cost per kg and cut spoilage.
Gives farmers demand forecasts, so they plant and harvest for known demand instead of selling in distress.
Pays through UPI directly into the farmer's bank account, with no cash dependence or delayed settlement.

3. Innovation and uniqueness

Demand-driven harvesting: forecasts and pre-orders go to FPOs before harvest.
Pooled, route-optimized last-mile logistics for small farmers.
Price-split transparency (farmer share vs. logistics vs. platform fee) on every order.
Voice-first, low-bandwidth interface for farmers with low digital literacy.
Quality assurance through photo-based grading and a farmer/buyer rating system.
## Technical Approach
<img width="2040" height="1680" alt="technical_approach_diagram" src="https://github.com/user-attachments/assets/9b82da7e-98a3-494f-b983-92c58eeb7045" />

## Feasibility and Viability
1. Feasibility

Technical: every component uses mature, open-source or widely available tools.
Operational: FPOs, cooperatives and existing digital rails such as UPI provide a ready base. Phase 1 can start with one district and 3–4 crops.
Economic: revenue from a small commission (for example 2–5%) and a logistics margin, far below the typical intermediary margin.

2. Challenges and risks

Low digital literacy and patchy internet in rural areas.
Building trust and enough supply and demand at launch (the "cold start" problem).
Perishability, quality disputes and last-mile cost.
Resistance from existing intermediaries.
Payment and delivery fraud.

3. Strategies to overcome

Voice and regional-language UI, an offline mode, and village-level agents or "Kisan Mitras" to help onboarding.
Pilot with existing FPOs and a few institutional buyers, then expand.
Pooled logistics, cold-chain tie-ups, and photo-based quality checks with a refund policy.
Escrow payments, verified profiles and ratings.
Work with mandis and intermediaries as logistics or aggregation partners instead of competing with them.

## Impact and Benefits
1. Impact on the target audience

Farmers/FPOs: a higher share of the consumer price, faster payment, less distress selling.
Consumers: fresher produce at lower prices.
Bulk buyers: reliable supply, bulk pricing and traceability.
Rural transporters: more consistent work and better truck utilization.

2. Benefits

Social: farmer empowerment, digital inclusion and rural employment (agents, drivers, packers).
Economic: better farm incomes, lower retail prices and reduced supply chain inefficiencies.
Environmental: less food waste, fewer empty trips and lower transport emissions through route optimization.

## Research and References
Agmarknet, mandi price data: https://agmarknet.gov.in
eNAM, National Agriculture Market: https://enam.gov.in
ONDC, Open Network for Digital Commerce: https://ondc.org
AgriStack, Government of India: https://agristack.gov.in
Government scheme for formation and promotion of 10,000 FPOs (Ministry of Agriculture & Farmers Welfare)
Google OR-Tools (vehicle routing): https://developers.google.com/optimization
Prophet, time-series forecasting: https://facebook.github.io/prophet
Project OSRM, routing engine: https://project-osrm.org
