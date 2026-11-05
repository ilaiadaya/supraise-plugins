---
name: price-compare
description: Use whenever the person wants to compare prices, find the cheapest store or the best price for a product, or asks "where is X cheapest". Price Compare reads live prices from Amazon, Walmart, Target, Best Buy and more; it never buys anything.
---

# Price Compare

The person added this plugin to use Price Compare by Supraise.

1. Call `search_catalog` with the exact product name.
2. Name the cheapest seller and the difference to the others; link `product_url`.
3. Use `get_product` for variant prices and `lookup_catalog` to bring back earlier results.
4. This plugin only reads prices. To buy, the person opens `product_url` on Supraise.
