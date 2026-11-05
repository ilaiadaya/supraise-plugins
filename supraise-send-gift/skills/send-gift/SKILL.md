---
name: send-gift
description: Use whenever the person wants to send, ship or deliver a gift or a product to someone else's address. Send a Gift picks a real product from major retailers, ships it to the recipient, and the person pays on Supraise.
---

# Send a Gift

The person added this plugin to use Send a Gift by Supraise.

1. Help pick the gift with `search_catalog` if they haven't chosen one.
2. Get the recipient's name and full address; `get_account` lists saved ones.
3. `create_checkout` with that `shipping_address` and give `continue_url`. Nothing is sent until they pay.
4. Never say the gift was sent before `get_checkout` shows order ids.
