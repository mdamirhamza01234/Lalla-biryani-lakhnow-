# Lalla Biryani — Lucknow

A responsive, GitHub Pages-ready restaurant website.

## Included
- `index.html` — website content and sections
- `style.css` — responsive styling
- `script.js` — menu cards, cart, WhatsApp order requests and reservation requests

## Publish on GitHub Pages
1. Extract the ZIP.
2. Upload the four files to the root of a GitHub repository.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.

## Important setup before publishing
- WhatsApp/call number is set to `+91 98891 94949`. Confirm that this is the correct Lalla Biryani business number and that it uses WhatsApp.
- Address and map are set to Bal Mukund Bajpai Marg, Tambaque Mandi, Chaupatiyan, Chowk, Lucknow, Uttar Pradesh 226003. Verify the exact outlet/location before publishing.
- Menu dishes are illustrative examples, not a verified current menu. Update them in `script.js` and confirm availability and prices with the restaurant.
- The menu currently does not display prices because verified prices were not supplied. Orders are sent as WhatsApp requests; the restaurant confirms availability and total.
- Reservation is a request sent to WhatsApp, not an automatic confirmed booking.
- Food images are generic Unsplash stock photos, not verified photographs of Lalla Biryani's own dishes. Replace them with authorised restaurant photos for authenticity.
- Google Fonts, Unsplash photos and the embedded Google Map require an internet connection.

## Payments and backend
This is a static front-end site. It does not collect online payments or store orders/bookings in a database. Add a secure backend/payment provider if you need those capabilities.
