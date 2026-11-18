STAR TREATS WEBSITE — HOSTINGER STATIC VERSION

FILES
- index.html: website pages and dialogs
- styles.css: responsive design
- app.js: products, storefront interactions and reviews
- checkout.html: standalone checkout page
- admin.html: standalone admin dashboard
- assets/: logo and cookie photos cropped from your supplied screenshots

UPLOAD TO HOSTINGER
1. Open Hostinger File Manager > public_html.
2. Back up existing files first.
3. Upload the contents of this folder (not the outer folder) into public_html.
4. Confirm index.html is directly inside public_html.
5. Visit https://startreats.in and hard refresh (Ctrl+F5).

IMPORTANT LIMITATIONS
- Checkout orders and reviews are saved in the visitor's browser localStorage only. They are NOT sent to the business owner and are not shared across devices.
- Admin is a visual demo; demo password: startreats-demo. It is NOT secure authentication.
- No real payment gateway is connected. Cash on Delivery is the only selectable payment method.
- For real business use, connect a backend/database, secure admin authentication, order notifications and payment gateway before accepting live orders.
- Update phone, social links, product text/prices and images in app.js/index.html as needed.

SEPARATE PAGES
- Open checkout.html directly, or click a product's Pre-Order button on index.html.
- Open admin.html directly, or click ADMIN in the homepage navigation.
- Demo admin password: startreats-demo.

SEPARATE WEBSITE PAGES (V3)
- index.html — Home
- products.html — Shop / product collection
- reviews.html — Customer reviews
- contact.html — WhatsApp and Instagram contact
- checkout.html — Checkout (opens with selected product query)
- admin.html — Demo admin dashboard
All pages share styles.css and the assets folder. Upload every file and the assets folder directly into public_html.

PRODUCT ADMIN (BROWSER DEMO)
- Admin > Products > Add New Product or Edit/Delete.
- Product changes are saved to localStorage in the same browser and appear on products.html and the homepage when opened in that same browser.
- This is not a shared online database: changes on one device/browser do not automatically appear to other visitors. A backend/database is required for live public product management.

WHATSAPP ORDER NOTIFICATION (V5)
- Checkout opens a WhatsApp chat to Star Treats (+91 90329 78866) with order ID, customer name and phone, cookie, quantity, unit price, subtotal, shipping, total, payment method, delivery date, address and optional note.
- The customer must press Send in WhatsApp. A static HTML website cannot silently send a WhatsApp message. Automatic sending requires a server backend and approved WhatsApp Business Platform/API setup.

See WHATSAPP-AUTO-ORDER-SETUP.txt for the PHP + Meta WhatsApp Cloud API setup.
