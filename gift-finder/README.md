# Gift Finder

Find the right gift for anyone: describe the person and budget and get real products from major retailers, then send it once or set up a recurring surprise. You review and pay on Supraise.

## What it does
Tell Claude who the gift is for, what they like and how much to spend. It searches Amazon, Walmart, Target and more and suggests a few real products with photos, prices and a reason each one suits them. Send one to their address with a checkout you review and pay on Supraise, or set up a gift on repeat (monthly, quarterly, yearly) or a one-time present on a date. Plans start paused and only run after you turn them on at supraise.com.

## Install
In Claude Code:
```
/plugin marketplace add ilaiadaya/supraise-plugins
/plugin install gift-finder@supraise
```

## Connecting
- Gift Finder talks to the Supraise server at `https://supraise.com/api/mcp` (Streamable HTTP).
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
- "A gift for my dad who loves grilling, about $40"
- "Housewarming present for a plant person under $30"
- "Set up a monthly $25 surprise for me, I like coffee and hiking"

## Data and privacy
Supraise receives only what Claude sends to these tools for your request (searches, carts, addresses you ask it to use). It never reads your other conversations. The plugin has no hooks or local scripts.
- Privacy policy: https://supraise.com/legal/privacy
- Terms of service: https://supraise.com/legal/terms
- Support: https://supraise.com/support
