# Multi-Store Shopping

Shop Amazon, Walmart, Target, Best Buy and more in one search; buy on Supraise and send gifts once or on repeat.

## What it does
Search Amazon, Walmart, Target, Best Buy, Home Depot and other retailers at once and get real products with photos, ratings, a short summary and the price from each seller.

Every product opens its page on Supraise, where you choose size or colour and check out once, even with items from several stores. Nothing is bought inside Claude: you always review and pay on supraise.com (card, Apple Pay, Google Pay or your Supraise gift wallet), and Supraise then orders from the retailer.

Gifts: send one to someone's address or set up a gift on repeat; plans created in Claude start paused until you turn them on at supraise.com.

Searching needs no account. Carts, checkouts, orders and gift plans need a Supraise account.

Ships to the United States, Canada, the United Kingdom, Ireland, Germany, France, Spain, Italy, the Netherlands, Belgium, Austria and Australia. Outside the US, results are limited to sellers that ship there. Supraise does not sell weapons, adult products, tobacco, drugs or prescription medicine.

## Install
In Claude Code:
```
/plugin marketplace add ilaiadaya/supraise-plugins
/plugin install supraise-shop@supraise
```

## Connecting
- Multi-Store Shopping talks to the Supraise server at `https://supraise.com/api/claude/shop/mcp` (Streamable HTTP).
- Searching works without an account. Anything you buy or save asks you to sign in to Supraise (OAuth with PKCE), then you come straight back to the chat.
