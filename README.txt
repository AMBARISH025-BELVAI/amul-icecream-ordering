AMUL ICE CREAM WEBSITE — FIXED HOMEPAGE VERSION

Changes:
- Added Home navigation.
- The website opens on a homepage with two options: ICE CREAM MENU and DIRECT PAYMENT.
- ICE CREAM MENU opens the existing product menu and cart.
- DIRECT PAYMENT opens the existing amount-entry payment dialog.
- Kept the existing product menu, cart, admin panel and styling.

Before testing UPI:
1. Open index.html in a code editor.
2. Find SHOP_UPI_ID.
3. Replace the empty value with the shop owner's real UPI ID.
4. Test on a phone with a compatible UPI app.

Limitations:
- UPI app opening depends on the phone/browser and installed payment apps.
- The website does not automatically verify payments.
- This prototype stores data in localStorage on one browser only; orders are not shared across devices.
- Deploy on HTTPS hosting and test the live URL on Android and iPhone before printing the QR code.
