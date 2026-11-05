# Personal Shopper

A personal shopper across Amazon, Walmart, Target, Best Buy and more: find the right product, compare sellers and check out on Supraise.

## What it does
Say what you need, like quiet running earbuds or a cast iron skillet that lasts, and get a recommendation from real products at Amazon, Walmart, Target, Best Buy and other retailers, with photos, ratings, a short summary and every seller's price.

Collect items in a cart as you go and check out once. Nothing is bought inside Claude: you always review and pay on supraise.com (card, Apple Pay, Google Pay or your Supraise gift wallet), and Supraise then orders from the retailer. Track your orders from the chat.

Searching needs no account. Carts, checkouts and orders need a Supraise account.

Ships to the United States, Canada, the United Kingdom, Ireland, Germany, France, Spain, Italy, the Netherlands, Belgium, Austria and Australia. Outside the US, results are limited to sellers that ship there. Supraise does not sell weapons, adult products, tobacco, drugs or prescription medicine.

## Install
In Claude Code:
```
/plugin marketplace add ilaiadaya/supraise-plugins
/plugin install supraise-personal-shopper@supraise
```

## Connecting
- Personal Shopper talks to the Supraise server at `https://supraise.com/api/claude/personal-shopper/mcp` (Streamable HTTP).
- Searching works without an account. Anything you buy or save asks you to sign in to Supraise (OAuth with PKCE), then you come straight back to the chat.
