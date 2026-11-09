# Arc Electricals customer catalogue (public website)

This folder is the customer-facing, static catalogue. It includes only products with wholesale prices from the supplied workbook, the Arc Electricals logo, search, cart, optional variants, and WhatsApp order handoff to 0767539827. Customers can view the catalogue on desktop or mobile.

## Important data boundary

This site does not contain the PC admin app or its private order management. Customer orders are sent to WhatsApp and are not stored automatically in the PC app. The site is built from the exported workbook list. Photos and item changes saved in the PC app do not automatically update this website; republish the site with an updated public product export when the catalogue changes.

## Publish

Upload the contents of this folder (including `seed-products.js`, `styles.css`, and `customer.js`) to the root of a public static hosting repository or static-site host. The home page is `index.html`. GitHub Pages can host this as a free static site; a public GitHub repository or hosting account is required. Keep the separate PC workspace private because it includes management functionality and locally stored data.

Source price/stock workbook was exported 15 Oct 2026. Ask customers to confirm current price and availability before fulfilment.
