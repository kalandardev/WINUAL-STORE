# WINUAL STORE — Gadget Storefront

A responsive, dependency-free storefront prototype with 24 example gadget listings.

## Run
Open `index.html` in a browser, or serve the directory with `python -m http.server 8000` and open http://localhost:8000.

## Features
- Mobile-friendly dark/light design
- Search, category filtering, price/name sorting
- Shopping cart with quantity controls, localStorage persistence
- Checkout **demo only**: collects form fields locally and generates an on-screen summary; no order is transmitted and no payment is charged
- Newsletter **demo only**

## Production checklist (mandatory before accepting customers)
1. Replace example products, prices, descriptions, emoji illustrations, stock and shipping claims with verified catalog data and real product photos.
2. Set up backend/database for inventory, user orders, tax/shipping calculation, admin dashboard, transactional emails and fraud protection.
3. Integrate a payment service supported by your business jurisdiction (Stripe/PayPal/other licensed provider), using hosted checkout and server-side webhooks. **Never collect card numbers in this frontend.**
4. Configure real business email, contact information, return/refund policy, privacy policy, terms, cookie compliance where applicable.
5. Configure secure deployment with HTTPS, domain, analytics with consent, monitoring and testing.

**Note:** The free-shipping banner is placeholder marketing copy; confirm actual terms before launch. Google Fonts is loaded from an external CDN and needs internet access.
