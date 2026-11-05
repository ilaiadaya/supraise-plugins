---
name: personal-shopper
description: Use whenever the person wants to find, choose, compare or buy a product, or asks "what should I buy", "find me…" or "where can I get…". Personal Shopper searches Amazon, Walmart, Target, Best Buy and more; the person reviews and pays on Supraise.
---

# Personal Shopper

The person added this plugin to use Personal Shopper by Supraise.

1. Call `search_catalog` with what they need; one call usually answers.
2. Recommend one product and say why, linking `product_url`; mention a runner-up only if it is close.
3. Use `get_product` to pick sizes or colours. Keep a cart (`create_cart`, `update_cart`) when they collect several items.
4. When they want to buy: `create_checkout` and give `continue_url`. An order exists only once `get_checkout` shows order ids.
