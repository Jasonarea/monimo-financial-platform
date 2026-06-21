# Monimo — Unified Financial Services Platform
**Samsung SDS · May 2024 – Present**


## Overview

Monimo is a unified mobile financial services platform developed by Samsung SDS, 
integrating multiple financial domains — banking, insurance, cards, securities, 
and telecommunications — into a single customer-facing experience for Samsung 
Financial Networks.

I contributed to the design and development of three core service modules: 
Loan Services, Automobile Services, and Product Catalog, building full-stack 
components across frontend, backend, and batch layers.

---

## Services Developed

### 1. Loan Services
- Developed backend interfaces to communicate with multiple financial institutions
(banking, insurance, cards, securities) to aggregate and display personalized 
loan information for each customer
- Designed APIs to retrieve and present loan eligibility and amount information 
across institutional boundaries within an MSA environment

### 2. Automobile Services
- Built external interface integration with AJ Selka to retrieve real-time 
vehicle valuation data based on customer-owned vehicle information
- Designed the data pipeline from external API to frontend display, ensuring 
accurate and timely vehicle market price information for customers

### 3. Product Catalog
- Developed a unified product browsing experience aggregating financial products
from multiple Samsung affiliate companies
- Designed backend data aggregation logic and frontend rendering for 
cross-institutional product comparison

---

## Technical Challenges

### Cross-Institutional Data Integration
Integrating data from multiple financial institutions (생명보험, 화재보험, 
카드사, 증권사) required designing a unified data model that could normalize 
heterogeneous API responses into a consistent customer-facing experience.

### MSA Architecture
All services were built within a Microservices Architecture (MSA), requiring 
careful design of service boundaries, inter-service communication, and 
data consistency across distributed components.

### Batch Processing
Designed Spring Batch jobs to handle large-scale data synchronization between 
external financial institutions and the Monimo platform, ensuring data freshness
while maintaining system stability.

---

## Key Insights

- Building for millions of users across multiple financial domains requires 
constant awareness of how design decisions affect real people's financial lives
- Working alongside UX designers revealed how much the framing and presentation
of financial information influences user trust and decision-making
- This experience reinforced my belief that financial technology must be designed
not just for technical correctness, but for human comprehension and confidence

---

## Technical Stack

**Frontend:** `Vue.js`  
**Backend:** `Java` `Spring Framework`  
**Batch:** `Spring Batch`  
**Architecture:** `MSA (Microservices Architecture)`  
**Integration:** `External API` `Inter-institutional Data Interfaces`

---

## References

- [Samsung Financial unveils the revamped New Monimo (Design Compass, 2025.12.04)](https://designcompass.org/2025/12/04/samsung-financial-unveils-the-revamped-new-monimo/)
  — Launch coverage of the redesigned Monimo with enhanced personalized UX

- [Samsung Card leads Monimo's turnaround as a pioneer in Korea's super-app transition (Opinion News, 2026.04.16)](https://www.opinionnews.co.kr/news/articleView.html?idxno=136889)
  — Analysis of Monimo's growth from early UX challenges to 10 million users

- [Monimo Official Website](https://www.monimo.com/monimo/homepage/main/PGIFPCCHomepageMainIndex001)
