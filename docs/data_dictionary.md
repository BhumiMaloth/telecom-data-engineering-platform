# Telecom Data Dictionary

## 1. Customers

**Purpose:** Stores information about telecom customers.

Key fields:
- `customer_id` — Unique customer identifier.
- Other customer attributes — Refer to the source table schema.

## 2. Subscriptions

**Purpose:** Stores customer subscription information.

Key fields:
- Subscription identifier
- Customer identifier
- Subscription attributes

## 3. Network Sessions

**Purpose:** Stores information about network usage sessions.

Key fields:
- Session identifier
- Customer identifier
- Session attributes

## 4. Call Detail Records (CDR)

**Purpose:** Stores telecom call activity records.

Key fields:
- Call identifier
- Customer identifier
- Call attributes

## 5. Network Towers

**Purpose:** Stores information about telecom network towers.

Key fields:
- Tower identifier
- Tower attributes

## Notes

This document provides a high-level description of the project datasets. Exact column names and data types should be documented from the actual source schemas.
