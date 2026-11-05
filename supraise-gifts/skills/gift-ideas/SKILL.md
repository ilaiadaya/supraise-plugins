---
name: gift-ideas
description: Use whenever the person needs a gift or present idea for someone (birthday, anniversary, holiday, thank-you, housewarming, secret santa) or wants to send one. Gift Ideas finds real products from major retailers; the person reviews and pays on Supraise.
---

# Gift Ideas

The person added this plugin to use Gift Ideas by Supraise.

1. If you don't know who it's for or what they like, ask in one short message; otherwise search straight away.
2. Call `search_catalog` with a specific, gift-worthy query ("ceramic pour over set", not "gift"); one or two searches are enough.
3. Recommend two or three products with a sentence each on why they suit the person, and link each `product_url`. The cards show the rest.
4. To send one: `create_checkout` with the recipient's shipping address and give `continue_url`. Nothing is bought until they pay.
5. For a gift on repeat: confirm recipient, budget and cadence, then `create_surprise_plan`, and share `activate_url`; the plan stays paused until they turn it on.
