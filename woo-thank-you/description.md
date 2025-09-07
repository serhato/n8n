# WooCommerce After Order Thank You Email
This workflow is designed to send a personalized thank-you email to a customer after an order is placed.

## What It Does
1. Check new orders regularly
2. Get order details from the WooCommerce website
3. Enters the essential information into a Google Sheet
4. Translates the product information to English
5. Sends the sample email to the related person
6. Sends the confirmed email to the customer

## Nodes Included
- Schedule
- WooCommerce
- Code
- Edit Fields
- Aggregate
- Basic LLM Chain
- Google Sheet
- If
- Human in the Loop

## Capability
- Usage of WooCommerce
- Editing files in Google Sheets
- Translation
- Code in JS
- A HITL(Human in the loop) process

## Improvements to Be Made
- Mark an order in the Google Sheet as processed to avoid multiple sent emails.
- A better HITL approach to provide a clear prompt to the LLM to edit the declined email draft
- A product recommendation and a possible discount coupon system
- Inclusion of customer follow-up system via Google Sheet, Notion, or a CRM
