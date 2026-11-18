# QueueLess — College Canteen Ordering Prototype

Open `index.html` in a modern browser. No build step or server is required.

The Student tab contains the expanded canteen menu with category filters, search, cart, student details, pickup slots and simulated checkout. Each placed order receives a unique pickup token.

The Staff Dashboard displays orders and supports Accept → Preparing → Ready → Collected. Use “Add sample orders” to populate the queue.

This is a front-end-only prototype. Orders are stored in localStorage and shared between the two views in the same browser only. Payment is simulated; the QR graphic is illustrative, not scannable. A real deployment needs a backend/database, payment gateway, QR generation and staff authentication.
