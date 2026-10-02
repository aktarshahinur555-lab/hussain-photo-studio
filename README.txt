HUSSAIN PHOTO STUDIO SHOP — FRONT-END DEMO

Files:
- index.html: single-page shop with product gallery, cart, custom photo upload preview, address checkout, WhatsApp order draft, demo profile, and local order history.
- images/: the nine images supplied in the conversation, used as product examples.

How to use:
1. Keep index.html and the images folder together.
2. Open index.html in a modern browser, or upload the complete folder to a static web host.
3. Update the prices and product details in the `products` array in index.html.
4. WhatsApp orders open a prefilled chat to +91 96782 30302. The customer must manually attach their actual image in WhatsApp; a web page cannot attach a local file to a WhatsApp message automatically.

Important limitations:
- Signup/login is a local browser demo, not secure production authentication.
- No real OTP is sent. To send OTPs through WhatsApp from your business number, you need a backend server and an approved WhatsApp Business Platform/API setup, plus appropriate templates/verification. A static HTML file cannot securely send OTPs or impersonate a sender number.
- Cart/profile/order history use browser localStorage on the current device only; they are not synced between customers/devices.
- Prices are example estimates and should be confirmed with the studio.
