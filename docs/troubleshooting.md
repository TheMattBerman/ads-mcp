# Troubleshooting

**"Couldn't reach the server" or the connection fails.** Use the exact address `https://mcp.stealads.ai/mcp`, including `/mcp`.

**The agent can search but cannot make an ad.** If you connected the Claude address (`.../mcp/claude`), that is by design: it hands you a link to finish the ad in the StealAds app. Otherwise your connection may not include the spend permission; reconnect and approve spending, or finish the ad in the app.

**It answers from memory instead of searching.** Name the tool or the product in your prompt ("Use StealAds to..."), and install the skills and rules from this repository.

**A search returns nothing.** The agent will widen it once. Try a nearby category, or lower the minimum run time.

**Sign-in loops.** Sign out of StealAds in your browser, remove the connection in your agent, and add it again.

Still stuck? Ask your agent to contact StealAds support, or email hello@stealads.ai with a short description. Do not include tokens or keys.
