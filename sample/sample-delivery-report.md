# Sample Delivery Report

## Summary

I cleaned the sample sales file by standardizing dates, customer names, categories, prices, and status labels. I removed one exact duplicate order row and added a `Line Total` column where quantity and price were available.

## Changes Made

- Trimmed extra spaces in customer names.
- Standardized dates to `YYYY-MM-DD`.
- Standardized categories to plural title case.
- Removed currency symbols from prices.
- Standardized status values to `Paid` and `Pending`.
- Removed one duplicate row for order `1002`.
- Added notes for rows needing buyer confirmation.

## Needs Confirmation

- Order `1004` is missing quantity, so line total is blank.
- Order `1006` is missing customer name, so it is marked as `Unknown`.

## Boundaries

This is data cleanup only. It is not tax, legal, financial, accounting, medical, or investment advice.
