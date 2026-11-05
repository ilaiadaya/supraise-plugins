# Send a Gift

Send a real gift from Amazon, Walmart, Target and more to anyone's address: pick it in chat, pay on Supraise, Supraise orders it.

## What it does
Pick a gift, a thank-you, a birthday present or a care package, among real products at Amazon, Walmart, Target, Best Buy and other retailers, give the recipient's name and address, and Supraise orders it and ships it to them.

Nothing is bought inside Claude: you always review and pay on supraise.com (card, Apple Pay, Google Pay or your Supraise gift wallet), and Supraise then orders from the retailer. Your saved addresses are offered so you don't retype them, and you can follow the order from the chat.

Searching needs no account. Sending needs a Supraise account.

Ships to the United States, Canada, the United Kingdom, Ireland, Germany, France, Spain, Italy, the Netherlands, Belgium, Austria and Australia. Outside the US, results are limited to sellers that ship there. Supraise does not sell weapons, adult products, tobacco, drugs or prescription medicine.

## Install
In Claude Code:
```
/plugin marketplace add ilaiadaya/supraise-plugins
/plugin install supraise-send-gift@supraise
```

## Connecting
- Send a Gift talks to the Supraise server at `https://supraise.com/api/claude/send-gift/mcp` (Streamable HTTP).
- Searching works without an account. Anything you buy or save asks you to sign in to Supraise (OAuth with PKCE), then you come straight back to the chat.
