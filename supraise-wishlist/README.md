# Gift Wishlist

Build a wishlist of real products from Amazon, Walmart, Target and more, and share one link so friends buy the right gift without doubling up.

## What it does
Tell it what you'd love, like a cast iron skillet, wireless earbuds for running or a cozy reading lamp, and it finds real products from Amazon, Walmart, Target, Best Buy and other retailers, with photos, ratings and the price from each seller. Keep the ones you want in a wishlist, add a note such as the size or colour, and get one link to share.

Friends and family open the link on supraise.com, pick an item, buy it as a gift and mark it bought, so nobody gets you the same thing twice. Turn on surprise mode and you won't see what has been bought. Nothing is bought inside Claude: you always review and pay on supraise.com (card, Apple Pay, Google Pay or your Supraise gift wallet), and Supraise then orders from the retailer.

Searching needs no account. Saving a wishlist needs a Supraise account; the people you share it with don't need one to see it.

Ships to the United States, Canada, the United Kingdom, Ireland, Germany, France, Spain, Italy, the Netherlands, Belgium, Austria and Australia. Outside the US, results are limited to sellers that ship there. Supraise does not sell weapons, adult products, tobacco, drugs or prescription medicine.

## Install
In Claude Code:
```
/plugin marketplace add ilaiadaya/supraise-plugins
/plugin install supraise-wishlist@supraise
```

## Connecting
- Gift Wishlist talks to the Supraise server at `https://supraise.com/api/claude/wishlist/mcp` (Streamable HTTP).
- Searching works without an account. Anything you buy or save asks you to sign in to Supraise (OAuth with PKCE), then you come straight back to the chat.
