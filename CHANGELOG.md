# Changelog

## 1.1.0
- Skills and rules now use the tool names the StealAds server lists today: `find_winning_ads` (was `find_bangers`), `get_competitor_analysis` (was `get_breakdown`) and `get_ad_status` (was `get_generation_job`). The old names still work on the server as hidden aliases, so older copies of these skills keep working.
- `adapting-a-winning-ad` knows both addresses: on the full address it previews the cost, asks, makes the ad and checks its status; on the Claude address (`https://mcp.stealads.ai/mcp/claude`, which has no image tool) it uses the new hand-off tool to give a link that opens the ad in StealAds.
- Added the Claude address to the README, `docs/tools.md`, `docs/troubleshooting.md` and `AGENTS.md`, and described what each address offers.
- The support tool is now mentioned: ask your AI to contact StealAds support from the chat. Cursor rules route help requests to it.
- README: results may come back as text in some hosts; the hero image is labeled illustrative and no longer says every host shows a gallery.
- Plugin manifests bumped to 1.1.0.

## 1.0.0
- Initial release: StealAds server configuration, seven skills (competitor ads, brand Playbook, winning ads in a category, what a category keeps and drops, longest-running ads, adapting a winning ad, Monday drop), two Cursor rules.
