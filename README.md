# Arc Electricals customer catalogue (public website)

Responsive customer page with search, wholesale prices, cart, optional variants and WhatsApp ordering to 0767539827. The repository contains only the public customer page and catalogue data; the PC admin app and its local orders remain separate.

## Automatic catalogue updates

The page starts from the packaged workbook snapshot and can read the current live catalogue from Supabase. Set `CLOUD_CATALOGUE.url` and `CLOUD_CATALOGUE.key` in `customer.js` to the project URL and public publishable/anon key. After one-time Supabase setup, each successful product, price, variant or photo save in the PC app updates the cloud catalogue; customers see the latest active catalogue when they open or refresh this page.

Customer enquiries open WhatsApp. They are not inserted into the PC app or cloud database automatically; copy the received WhatsApp message into the PC app's Orders page.

## Data notes

The public catalogue includes wholesale product names, item codes, prices, variants and product images. It omits supplier names and stock counts. Original workbook export date: 15 Oct 2026; confirm current prices and availability before fulfilment.

For one-time database setup instructions, see `SUPABASE-SETUP-SI.md` and `supabase-setup.sql` in the PC app package. Keep that PC admin package private.
