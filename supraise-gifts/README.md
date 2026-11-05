# Gift Ideas

Gift ideas for anyone from real products at Amazon, Walmart, Target and more; send one to their address or set up a gift on repeat.

## What it does
Describe the person, like a dad who loves grilling or a friend who just started running, and get gift ideas that are real products from Amazon, Walmart, Target, Best Buy and other retailers, each with a photo, rating and a sentence on why it suits them.

Every idea opens its page on Supraise. Send it straight to their address, or set up a gift on repeat for birthdays and holidays; plans created in Claude start paused until you turn them on at supraise.com. Nothing is bought inside Claude: you always review and pay on supraise.com (card, Apple Pay, Google Pay or your Supraise gift wallet), and Supraise then orders from the retailer.

Ideas need no account. Sending a gift and gift plans need a Supraise account.

Ships to the United States, Canada, the United Kingdom, Ireland, Germany, France, Spain, Italy, the Netherlands, Belgium, Austria and Australia. Outside the US, results are limited to sellers that ship there. Supraise does not sell weapons, adult products, tobacco, drugs or prescription medicine.

## Install
In Claude Code:
```
/plugin marketplace add ilaiadaya/supraise-plugins
/plugin install supraise-gifts@supraise
```

## Connecting
- Gift Ideas talks to the Supraise server at `https://supraise.com/api/claude/gifts/mcp` (Streamable HTTP).
- Searching works without an account. Anything you buy or save asks you to sign in to Supraise (OAuth with PKCE), then you come straight back to the chat.
