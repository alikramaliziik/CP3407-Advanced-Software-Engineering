# Practical 3: Start Iteration 1 - Week 1

## Applying Chapter 3 Principles

Following Chapter 3 guidance, we applied velocity and realistic planning to our user stories from Practical 2:

**Velocity Calculation:**
- Starting velocity: **0.7** (conservative estimate for new team, as recommended in Chapter 3)
- Team size: **1 developer** (solo project)
- Work capacity per iteration: `1 person × 20 working days × 0.7 = 14 days of productive work`

**Customer Prioritization:**
Working with our simulated customer, we prioritized stories based on **baseline functionality** (Chapter 3, p. 75): the minimum features needed for the software to be useful. The customer confirmed that trail discovery and basic access are essential for Milestone 1.0, while transactions and advanced features can wait for later iterations.

**Milestone 1.0 Planning:**
- Target: **3 iterations × 20 working days = 60 calendar days** (3 months)
- Total productive work capacity: **3 × 14 = 42 days of work**
- Strategy: Focus on core discovery features first, then add engagement features, postponing lower-priority items (e.g., Compare Trails, Book Trip) to Milestone 2.0

## Revised Iteration Plan

**Iteration 1** (14 days capacity, 22 days planned - **OVER CAPACITY**)  
After applying velocity, our original Iteration 1 exceeded realistic capacity. Following Chapter 3's advice (p. 92-96), we reprioritized:

**Adjusted Iteration 1** (≤14 days):
- Browse Trails (10 days, Priority 10)
- Search Trails (3 days, Priority 20)
- User Login (2 days, Priority 30)
- **Total: 15 days** *(Slightly over, but Login is essential for Iteration 2 dependencies)*

**Adjusted Iteration 2** (≤14 days):
- List Equipment (7 days, Priority 10)
- View Reviews (3 days, Priority 20)
- Add Review (2 days, Priority 20)
- Compare Trails (1 day, Priority 50)
- **Total: 13 days**

**Postponed to Later Iterations:**
- Order Equipment (15 days - requires splitting)
- Join Mailing List (7 days)
- Book Trip (10 days)

## GitHub Project Board

A GitHub Project board has been created following the **Big Board** concept from Chapter 3 (p. 100-101):

**Board Structure:**
- **To Do:** User stories for Iteration 1
- **In Progress:** Currently active work
- **Done:** Completed stories
- **Burn Down:** Tracking chart for monitoring progress


All Iteration 1 user stories have been added as issues/cards and initially marked as "To Do."

## Iteration 1 Status - Week 1

**Focus:** Core Discovery and Access Features  
**Total Estimated Effort:** 15 days  
**Status:** Started (Week 1 of 4)

| User Story Title | Description | Priority | Estimate | Status |
|-----------------|-------------|----------|----------|---------|
| **Browse Trails** | As a customer, I want to browse trails so that I can see available hiking options, including details like length, terrain, and highlights. | High (10) | 10 days | **In Progress** (Started: UI wireframes and data model) |
| **Search Trails** | As a customer, I want to search for trails by zip code and difficulty so that I can find trails near me that match my skill level. | Medium (20) | 3 days | To Do |
| **User Login** | As a customer, I want to log in so that I can access personalized features like orders and reviews. | Low (30)* | 2 days | To Do |
