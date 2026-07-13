---
title: "Add live stock data to your AI agent in 20 lines (Marketstack + Claude tool use)"
url: "https://blog.apilayer.com/add-live-stock-data-to-your-ai-agent-in-20-lines-marketstack-claude-tool-use/"
date: "2026-06-18"
author: "Karam"
feed_url: "https://apilayer.com/blog/feed/"
---
Claude doesn’t know what TSLA closed at. Ask it anyway and it will hand you a confident number that is wrong, because the price isn’t in its training data and never will be. Tool use fixes this. You give Claude a function it can call, and when a question needs a real price, it calls your function instead of guessing. Alpha Vantage recently shipped an official MCP server for this. It works well, but it means wiring up an MCP client, a transport, and a connection first. If you want the full...
