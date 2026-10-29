---
name: shopping
description: Use whenever the person wants to shop, buy, find, compare or price a product, look for a deal, or asks "where can I get…", "what's the best … under $X" or "find me …", for anything sold by Amazon, Walmart, Target, Best Buy, Home Depot and other retailers. Shopping by Supraise searches them all in one place with live prices, photos and ratings; the person reviews and pays on Supraise.
---

# Shopping by Supraise

The person added this plugin to shop with Supraise. When they want a product:

1. Call `search_catalog` once with their request in plain words and any budget as `filters.max_price`. One search returns photos, ratings, a short summary and the price from every seller, so you don't need `get_product` to answer.
2. The results show as product cards. Don't repeat them as a table: recommend one or two in a few sentences, say why, and link each product's `product_url` (its Supraise page, where they pick size or colour and pay).
3. Only when they ask you to buy: call `get_product` if it has options (size, colour) to pick the variant, then `create_checkout` and give them `continue_url`. They review and pay there by card, Apple Pay, Google Pay or gift wallet. Nothing is bought until they pay.
4. Never say an order was placed until `get_checkout` shows order ids. For order status use `search_orders`.
5. Prices are in USD and come live from each retailer. Outside the US, pass `filters.ships_to_country`; results are then limited to sellers that ship there.
