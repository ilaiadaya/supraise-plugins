---
name: gift-finder
description: Use whenever the person needs a gift or present idea for someone (birthday, anniversary, holiday, thank-you, housewarming, secret santa), wants to send a gift to someone's address, or wants a recurring surprise for themselves or someone else. Gift Finder by Supraise picks real products from major retailers within budget; the person reviews and pays on Supraise.
---

# Gift Finder by Supraise

The person added this plugin to find and send gifts with Supraise.

1. If you don't know who it's for, their interests or the budget, ask in one short message. Otherwise go straight to searching.
2. Call `search_catalog` with a specific, gift-worthy query (for example "ceramic pour over set" rather than "gift"), with the budget as `filters.max_price`. One or two searches are enough.
3. The results show as product cards. Recommend two or three with a sentence each on why they suit the person, and link each `product_url`. Don't repeat the cards as a table.
4. To send one now: when they ask, `create_checkout` with the recipient's shipping address and give them `continue_url` to review and pay. Nothing is bought until they pay.
5. For a gift on repeat (monthly, quarterly, yearly) or a one-time present on a date: confirm recipient, budget and cadence, then call `create_surprise_plan`. The plan is saved paused; give them `activate_url` to turn it on and fund their gift wallet on supraise.com. Never say a plan is running until they have turned it on.
