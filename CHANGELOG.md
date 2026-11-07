# Changelog

## 1.2.1
- Added `glama.json` so Glama can list the server, and `gemini-extension.json` so Gemini CLI can install it as an extension (remote `https://mcp.stealads.ai/mcp`).
- `assets/logo.svg` is now the StealAds mark the site uses as its icon, so the Cursor listing matches stealads.ai.
- Manifests bumped to 1.2.1.

## 1.2.0
- New skill `checking-new-rival-ads`: reads the ads your tracked rivals started running since a date (seven days by default, 30 at most) with `list_new_competitor_ads`, and writes a short weekly report. "New" means first seen by StealAds, not the launch date.
- `researching-competitor-ads` points to the new skill for "what did they launch lately".
- Docs, AGENTS.md and the Cursor rule cover tools that exist on the server today: `list_new_competitor_ads`, `list_tracked_rival_ads`, `get_capabilities` (page sizes, cursor lifetime, request rate, daily reading allowance), table (CSV) output for tracked rival ads and the competitor analysis, research-only brands (create a brand from a name) and read-only rival flags in `list_competitors`.
- README install table now matches how each app connects: Claude's Connectors directory (one click once listed) or the full link as a custom connector, ChatGPT, Cursor ("Add to Cursor" link), Claude Code, Codex, Gemini CLI and scripts. The Claude directory version is no longer offered as a link to paste.
- Added `server.json` for the official MCP Registry (`ai.stealads/stealads`).
- Plugin manifests bumped to 1.2.0.

## 1.1.0
- Skills and rules now use the tool names the StealAds server lists today: `find_winning_ads` (was `find_bangers`), `get_competitor_analysis` (was `get_breakdown`) and `get_ad_status` (was `get_generation_job`). The old names still work on the server as hidden aliases, so older copies of these skills keep working.
- `adapting-a-winning-ad` knows both addresses: on the full address it previews the cost, asks, makes the ad and checks its status; on the Claude address (`https://mcp.stealads.ai/mcp/claude`, which has no image tool) it uses the new hand-off tool to give a link that opens the ad in StealAds.
- Added the Claude address to the README, `docs/tools.md`, `docs/troubleshooting.md` and `AGENTS.md`, and described what each address offers.
- The support tool is now mentioned: ask your AI to contact StealAds support from the chat. Cursor rules route help requests to it.
- README: results may come back as text in some hosts; the hero image is labeled illustrative and no longer says every host shows a gallery.
- Plugin manifests bumped to 1.1.0.

## 1.0.0
- Initial release: StealAds server configuration, seven skills (competitor ads, brand Playbook, winning ads in a category, what a category keeps and drops, longest-running ads, adapting a winning ad, Monday drop), two Cursor rules.
