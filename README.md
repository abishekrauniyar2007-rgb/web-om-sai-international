# Om Sai International — Static Website

Modern mobile-first building-material ordering website for Om Sai International.

## Included
- Automatic 6.5-second cinematic door intro (no scrolling required).
- White + light-purple theme.
- Product catalogue from the supplied price list.
- Cement, TMT, Binding Wire, Paints, Plumbing, Equipment, Nails and Others.
- TMT Bundle/Piece/Both ordering with automatic kg + price calculation.
- Paint 1L/4L/10L/20L independent prices.
- Paint colour-code input with dealer-decided colour charges message.
- COD + eSewa QR checkout with transaction ID/phone field.
- Customer cancellation is represented through admin status controls; a customer-facing cancellation flow can be added when backend order storage is introduced.
- Delivery rules editable in Admin Portal.
- Product/category editing in Admin Portal.
- Orders saved in browser localStorage for this GitHub-only version.

## Important limitation
This version intentionally has **no Neon/Postgres/backend**. Because GitHub Pages/static hosting cannot securely write to a shared database, Admin changes and orders are stored in the browser's localStorage. The password gate is also client-side and is **not a production security boundary**. For multi-device, persistent admin access and real secure order management, connect the same UI to a backend/database later.

## Run
Open `index.html` directly, or deploy the folder to GitHub Pages. A simple local server is recommended for best browser behavior.

Admin portal: click **Admin** and use the current demo password shown on the login screen.


V6 updates: 3-second cinematic tech-style intro with vanishing text; dream-home image is now the full-screen homepage hero background for reduced scrolling.
