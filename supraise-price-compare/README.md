# Price Compare

Compare a product's price across Amazon, Walmart, Target, Best Buy and more in one search, and see which seller is cheapest.

## What it does
Name a product, like JBL Vibe Buds 2 or a Ninja air fryer, and see its price at Amazon, Walmart, Target, Best Buy, Home Depot and other retailers in one search, with the cheapest seller named.

Price Compare only reads prices: nothing is bought from the chat. Every product links to its page on Supraise, where you can buy it if you want.

No account is needed.

Ships to the United States, Canada, the United Kingdom, Ireland, Germany, France, Spain, Italy, the Netherlands, Belgium, Austria and Australia. Outside the US, results are limited to sellers that ship there. Supraise does not sell weapons, adult products, tobacco, drugs or prescription medicine.

## Install
In Claude Code:
```
/plugin marketplace add ilaiadaya/supraise-plugins
/plugin install supraise-price-compare@supraise
```

## Connecting
- Price Compare talks to the Supraise server at `https://supraise.com/api/claude/price-compare/mcp` (Streamable HTTP).
- Searching works without an account. Anything you buy or save asks you to sign in to Supraise (OAuth with PKCE), then you come straight back to the chat.
