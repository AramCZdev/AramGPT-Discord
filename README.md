# AramGPT

An AI Discord bot, powered by [Groq](https://groq.com). Runs on Cloudflare Workers — free to host, no server to babysit.

## Features

- Chat by pinging the bot: `@AramGPT What's 1+1?`
- `/aiprivacypolicy` or `/clearmemory` — shows the bot's privacy policy
- `/clearmemory` — clears your conversation history in the current channel
- Fast inference via Groq's LLM API (GPT OSS 120B)
- Stays online on its own — no manual restarts (Durable Object keeps the gateway alive, a cron job revives it if Discord drops the connection)
- A short 5-second cooldown between calls to keep things tidy — no daily request limit

## How to use

Ping the bot in a channel it can see:

```
@AramGPT What's 1+1?
```

AramGPT replies. That's it.

You can also use `/aiprivacypolicy` to see the bot's privacy policy, or `/clearmemory` to delete your conversation history in the current channel.

> Note: a freshly registered slash command can take up to **1 hour** to show up globally on Discord.

## Where is AramGPT?

The only public server that has AramGPT is [AramCZ's Basement](https://discord.gg/x8m4NjEaSs)

## Can I add AramGPT to my server?

Not the hosted public bot, sorry. But if you run a public server and want AramGPT, [contact me](mailto:aramcz@protonmail.com) — or host the bot yourself. It's free.

Made by [AramCZ](aramcz.is-a.dev)
