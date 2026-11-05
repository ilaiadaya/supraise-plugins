---
name: shop-every-store
description: Use whenever the person wants to shop, buy, find or compare a product, or asks "find me…" or "where can I get…", for anything sold by Amazon, Walmart, Target, Best Buy, Home Depot and other retailers. The person reviews and pays on Supraise.
---

# Multi-Store Shopping

The person added this plugin to use Multi-Store Shopping by Supraise.

1. One `search_catalog` call usually answers a request; recommend one and link `product_url`.
2. `get_product` for options, `create_checkout` when they want to buy, then share `continue_url`.
3. An order exists only once `get_checkout` shows order ids.
4. Gift plans: confirm recipient, budget and cadence, `create_surprise_plan`, share `activate_url`.
