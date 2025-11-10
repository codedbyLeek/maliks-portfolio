---
layout: page
title: "Customer Account Overview & Subscription Manager"
permalink: /projects/salesforce/customer-account-overview
---

## Customer Account Overview & Subscription Manager  
**Technology:** Salesforce Apex (Controller) · Visualforce · SOQL · Data Modeling

### Overview
This project provides a centralized view of customer account information, subscription records, and contract history within Salesforce. The solution was designed to streamline support and sales workflows by eliminating the need to navigate multiple related record pages.

### Key Features
- Displays customer details, active subscriptions, and associated contract data in one Visualforce interface.
- Apex controller retrieves, organizes, and structures related records efficiently using optimized SOQL queries.
- Automatically separates parent records from child subscription items for clearer presentation.
- Supports dynamic rendering and conditional display based on data availability.

### Business Impact
- Reduces support handling time by improving data accessibility.
- Helps sales teams quickly evaluate contract terms and renewal opportunities.
- Enhances internal efficiency by centralizing customer account intelligence.

### Salesforce Concepts Demonstrated
- Controller-driven UI rendering (Visualforce)
- SOQL query optimization and relationship traversal
- Handling of parent/child data models (Contracts → Subscriptions)
- Clean separation of concerns between logic (Apex) and presentation (VF)

### Next Improvements (Planned)
- Convert UI to Lightning Web Component for more responsive layout
- Add inline subscription modification and renewal actions
- Introduce caching strategy for large accounts

