# Shopping

Shop online from Claude: search and compare products and prices across Amazon, Walmart, Target, Best Buy and more in one place, see photos, ratings and every seller's price, then review and pay on Supraise.

## What it does
Ask for anything, like "a burr coffee grinder under $60" or "the cheapest JBL Vibe Buds 2". Claude searches every supported retailer in one go and shows product cards with photos, prices per seller, ratings and a short summary. Each card opens the product's page on Supraise, where you pick the size or colour and pay by card, Apple Pay, Google Pay or your gift wallet. Nothing is bought from inside Claude: you always review and pay on Supraise.

## Install
In Claude Code:
```
/plugin marketplace add ilaiadaya/supraise-plugins
/plugin install shopping@supraise
```

## Connecting
- Shopping talks to the Supraise server at `https://supraise.com/api/mcp` (Streamable HTTP).
- Searching works without an account. Carts, checkouts, orders and gift plans ask you to sign in to Supraise (OAuth with PKCE), then you come straight back to the chat.
- Developers can also use the same features through the [Supraise API](https://supraise.com/developers).

## Tools
| Tool | What it does |
|---|---|
| `search_catalog` | Search products across retailers, with photos, ratings and prices per seller. Read-only. |
| `lookup_catalog` | Refresh products already found. Read-only. |
| `get_product` | One product with its options and variants. Read-only. |
| `create_cart`, `update_cart`, `get_cart` | Collect items over a conversation. |
| `create_checkout`, `update_checkout`, `get_checkout` | A checkout link to review and pay on Supraise. Nothing is charged by the tool. |
| `search_orders` | Your orders and tracking. Read-only. |
| `get_account` | Saved addresses and gift wallet balance. Read-only. |
| `create_surprise_plan` | Saves a gift plan, paused until you turn it on at supraise.com. |

## Example prompts
- "Find me a burr coffee grinder under $60"
- "Compare prices for JBL Vibe Buds 2 and add the cheapest to my cart"
- "Show my recent orders"

## Data and privacy
Supraise receives only what Claude sends to these tools for your request (searches, carts, addresses you ask it to use). It never reads your other conversations. The plugin has no hooks or local scripts.
- Privacy policy: https://supraise.com/legal/privacy
- Terms of service: https://supraise.com/legal/terms
- Support: https://supraise.com/support
