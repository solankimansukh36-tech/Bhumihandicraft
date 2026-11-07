BHUMI-Handicraft HANDCRAFT STORE — UPDATED DEMO

FILES
- index.html: customer storefront (English + Gujarati)
- admin.html: admin dashboard
- README.txt: this guide

OPENING
1. Extract the ZIP.
2. Open index.html in a browser to view the store.
3. Open admin.html in the same browser to manage it.
4. Demo dashboard passcode: 1234

ADMIN DASHBOARD FEATURES
- Overview metrics and recent orders
- Add, edit, hide and delete products
- Product category, price, stock, English/Gujarati name and descriptions
- View orders and update their status
- Approve/reject/delete customer reviews
- Update WhatsApp number and selected storefront text
- Export a JSON backup and reset demo data

IMPORTANT LIMITATIONS
This is a browser-only prototype. It uses localStorage and sessionStorage:
- Store changes are visible only in the same browser profile and same website origin.
- A customer using another device/browser will NOT share products, orders or reviews with this dashboard.
- Orders are recorded locally when the customer clicks the WhatsApp checkout link; WhatsApp still needs the customer to send/confirm the message.
- Reviews are saved locally and appear publicly only after approval in this same browser.
- The passcode (1234) is visible in the source code and is NOT secure authentication. Do not publish admin.html as a live secure admin system.
- Hosting these static files does not add a database or security.

BEFORE LAUNCH
Replace the demo WhatsApp number with your own number in Admin > Store settings.
Replace demo products/content with your real catalogue and genuine product photos/reviews.
For a real online store, connect a secure backend/database and protected admin login (for example, Supabase/Firebase or a custom server). This is required for shared customer orders, reviews, stock and admin access across devices.

BRAND ASSET
- bhumi-handicraft-logo.png: BHUMI-Handicraft logo used in the storefront header.


NEW FEATURES IN THIS UPDATE
- Admin product editor now supports a direct image URL or uploading a JPG/PNG/WebP photo from your computer.
- Uploaded photos are resized and stored in this browser's localStorage with product data.
- Storefront product cards and product details display the saved image.
- Each product card has a WhatsApp button that opens a message prefilled with the product name and price.
- Keep in mind: this demo stores data in the current browser only. For GitHub Pages, images saved through this local admin will not automatically sync to visitors or other devices. A hosted database/storage service is needed for shared live catalogue updates.
