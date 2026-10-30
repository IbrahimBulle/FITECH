# FITECHPhones Kenya

A responsive one-page phone storefront with iPhone-first browsing plus Samsung, Google Pixel, Tecno, Infinix and “ask us for other models” options. Features include live search, brand filters, price sorting, a budget-and-priority phone finder, model detail cards, specs, a unit-specific battery-health guide, WhatsApp/call/email enquiry links, social sharing, FAQ, and SEO/social metadata.

## Shop contact details already entered

- WhatsApp/call: `0708453775` (international link uses `254708453775`)
- Email: `abdi@gmail.com`
- Shop name: `FITECHPhones`

To change these, update the `shop` object near the bottom of `index.html`, plus the links and JSON-LD store contact fields in the head/footer.

## Before publishing

1. Prices are dated Kenyan market guide points, checked 30 October 2026. They are not a live inventory feed or FITECH's confirmed offers. Update the `phones` array prices, variants, and descriptions to the exact stock, condition and selling prices. In particular, set the iPhone Duo price only after a local quote is available.
2. Add the real hosted URL as a canonical URL and Open Graph URL, and replace the generic product photo with licensed FITECHproduct/store imagery. The social share links use the current browser URL, so they start working on the production URL.
3. If FITECHcreates Instagram, TikTok or Facebook profile accounts, add those real profile URLs. The current social buttons share the site on Facebook/X and WhatsApp; they do not pretend an unprovided profile exists.
4. Check exact device region, SIM type, storage, condition, warranty and return policy with each buyer. Battery health is unique to a used handset; do not promise a specific percentage until you've checked the actual device.
5. Set up Google Search Console, submit a sitemap, and publish a real `robots.txt`/`sitemap.xml` on the final domain.

## Price references consulted

These public Kenyan listings informed the October 2026 guide points; different shops and variants have different prices:

- iPhone 18 Pro Max / 18 Pro: [Techsmartke Apple price index](https://techsmart.co.ke/apple-price-index-kenya), [Avechi iPhone 18 Pro](https://avechi.co.ke/product/apple-iphone-18-pro/), [iTey iPhone list](https://iteystore.co.ke/price-list/iphone)
- iPhone 17 Pro Max / Pro / 17 / Air / 17e: [Techsmartke Kenya iPhone price guide](https://techsmart.co.ke/iphone-price-in-kenya), [iPhone.ke iPhone 17](https://iphone.ke/products/iphone-17), [iTey iPhone list](https://iteystore.co.ke/price-list/iphone)
- iPhone 15 / 16: [Techsmartke iPhone 15 guide](https://techsmart.co.ke/price/iphone-15-price-in-kenya), [Swift Tech Nairobi](https://www.swifttech.co.ke/), [Phones World Store](https://phonesworldstorekenya.co.ke/product-category/iphone/)
- Samsung A56 and Pixel 9: [Phone Kenya A56](https://phonekenya.co.ke/product/samsung-galaxy-a56), [Avechi Pixel 9](https://avechi.co.ke/product/google-pixel-9-5g/)
- Tecno Spark 30 and Infinix Note 50S: [Phone Place Tecno Spark 30](https://www.phoneplacekenya.com/product/tecno-spark-30/), [FKAY Infinix Note range](https://www.fkaysmartphone.co.ke/blog/infinix-phones-and-prices-in-kenya-185/infinix-note-series-prices-in-kenya)

## Spec and battery references

- [Apple iPhone 18 Pro Max specs](https://support.apple.com/en-euro/148591), [Apple iPhone 18 Pro specs](https://support.apple.com/en-euro/148590), [Apple iPhone 17 specs](https://www.apple.com/ke/iphone-17/specs/), and [Apple model comparison](https://www.apple.com/iphone/compare/).
- [Apple battery and performance guidance](https://support.apple.com/en-gb/101575). Apple notes iPhone 14 and earlier are designed to retain 80% capacity at 500 complete charge cycles under ideal conditions. Actual battery health depends on the individual phone and its use.
- [Samsung Galaxy A56 specs](https://www.samsungmobilepress.com/media-assets/galaxy-a56-5g?tab=specs).

## Run locally

Open `index.html` directly, or use any static web server. The site has no build step or runtime dependencies.
