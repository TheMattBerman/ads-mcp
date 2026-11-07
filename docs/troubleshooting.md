# Troubleshooting

**"Couldn't reach the server" or the connection fails.** Use the exact address `https://mcp.stealads.ai/mcp`, including `/mcp`.

**The agent can search but cannot make an ad.** If you connected StealAds from Claude's Connectors directory, that is by design: it hands you a link to finish the ad in the StealAds app. To make ads in the chat, add `https://mcp.stealads.ai/mcp` as a custom connector instead. Otherwise your connection may not include the spend permission; reconnect and approve spending, or finish the ad in the app.

**A table comes back as text, or is refused.** Only your tracked rivals' ads and the competitor analysis can be returned as a table, one page at a time. Library searches are text or JSON only.

**A read says to try again later.** Tracked and saved ads share a daily reading allowance. Ask your agent for the limit, then wait for the time it gives.

**It answers from memory instead of searching.** Name the tool or the product in your prompt ("Use StealAds to..."), and install the skills and rules from this repository.

**A search returns nothing.** The agent will widen it once. Try a nearby category, or lower the minimum run time.

**Sign-in loops.** Sign out of StealAds in your browser, remove the connection in your agent, and add it again.

Still stuck? Ask your agent to contact StealAds support, or email hello@stealads.ai with a short description. Do not include tokens or keys.
