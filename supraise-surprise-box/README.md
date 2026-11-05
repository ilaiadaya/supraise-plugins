# Surprise Box

A surprise box for yourself or someone else: a gift chosen from their interests, once or every month, quarter or year.

## What it does
Tell Surprise Box what someone likes, like coffee and hiking, and how often: a gift is chosen from those interests and shipped once or every month, quarter or year. Make it a box for yourself, whose contents stay secret until it arrives, for someone you name, or for a stranger who opted in to receive gifts.

Plans created in Claude are saved paused: nothing is ordered or paid until you turn the plan on at supraise.com and add funds to your Supraise gift wallet there. Pause or stop it there at any time.

A Supraise account is needed.

Ships to the United States, Canada, the United Kingdom, Ireland, Germany, France, Spain, Italy, the Netherlands, Belgium, Austria and Australia. Outside the US, results are limited to sellers that ship there. Supraise does not sell weapons, adult products, tobacco, drugs or prescription medicine.

## Install
In Claude Code:
```
/plugin marketplace add ilaiadaya/supraise-plugins
/plugin install supraise-surprise-box@supraise
```

## Connecting
- Surprise Box talks to the Supraise server at `https://supraise.com/api/claude/surprise-box/mcp` (Streamable HTTP).
- Searching works without an account. Anything you buy or save asks you to sign in to Supraise (OAuth with PKCE), then you come straight back to the chat.
