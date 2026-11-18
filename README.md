# Match Box Saree — first website version

## Open the website
1. Extract `match-box-saree-website.zip`.
2. Open `index.html` in Chrome, Edge, or Firefox.
3. The site is responsive and works on desktop and mobile.

## Included in this prototype
- Match Box Saree wordmark/logo treatment
- Home page and collection sections
- Sample catalogue with category filters, search and sorting
- Shopping bag/cart
- Delivery details form
- Demo Cash on Delivery order capture
- Browser-only admin form to add products and upload photos
- Export sample product data as JSON and demo orders as CSV

## Important before taking real orders
This is a front-end prototype, not yet a production e-commerce system.
- Sample sarees and prices are illustrative. Replace them with your actual catalogue.
- Products, cart and demo orders are saved only in the current browser using local storage. They are not shared with other devices or customers.
- The checkout does not transmit orders to the business.
- Online payments are intentionally not enabled. Connect a verified Razorpay/Cashfree merchant account using a secure server-side integration and payment webhooks.
- Add a secure admin login, hosted database, image storage, order notifications, shipping integration, privacy policy, terms, returns policy and business contact details before launch.
- Never put payment secret keys in browser JavaScript.

## Suggested production architecture
Next.js storefront + Supabase database/storage/auth + server-side payment integration (Razorpay or Cashfree) + shipping provider integration (for example Shiprocket). Use HTTPS and verify payment status on the server.

## Business contact configured
- WhatsApp click-to-chat: +91 98669 29019
- All-India delivery is shown as subject to courier serviceability; confirm courier coverage and shipping terms before launch.
- Domain registration is not included; check availability and register the domain through a domain registrar.

## Six initial saree products added
- MBS001 to MBS006 have been added with the six uploaded saree photographs.
- Selling price for each: ₹12,000.
- Product descriptions deliberately avoid claiming an unconfirmed fabric or weave.
- Keep the `assets` folder beside `index.html` when extracting/deploying the website.

## MBS001 product details updated
- Product name: Green & Pink Silk Ikkat Saree
- Fabric: Silk (as specified by the seller)
- Pattern: Ikkat
- Selling price: ₹12,000
- Product photo refreshed with the latest uploaded image.

## Catalogue fabric and pattern clarification
- Seller confirmed all six initial products are silk sarees with Ikkat pattern.
- MBS001–MBS006 are categorized as Silk and priced at ₹12,000 each.
