# What the tools do

Your agent sees the exact tool names and descriptions when it connects. This page describes them by job so it stays accurate as names are refined.

| Job | What you get |
| --- | --- |
| Find an advertiser | Matches a brand name or website to an advertiser so its ads can be searched |
| Search ads | A capped sample of public Meta ads by brand, keywords, industry, format, hook, minimum run time and audience, with the hook and run length for each ad |
| Find long-running ads in a category | A category sample of ads with observed delivery evidence (long-running) for a category and related angles, without implying sales performance |
| Summarize rival ad patterns | Supported patterns plus source ads from your tracked rivals, or an optional category sample |
| Read one ad | The hook (spoken and on-screen), copy, format and how long it has run |
| Show ads | A gallery of the ads you chose (in clients that can display one) |
| Competitors | Add a rival, see which rivals you track (with read-only flags for stale, off-category and possible duplicate rivals), read an analysis of how they advertise, open their Playbook (what they keep, drop and are testing), check tracking status |
| New ads from rivals | The ads your tracked rivals started running since a date (last seven days by default, 30 at most), with when StealAds first saw each one |
| Tracked rival ads | A page of ads from your tracked rivals, including ads that stopped running, newest first or one rival at a time |
| Tables | Tracked rival ads and the competitor analysis can come back as a CSV table for the page you asked for. Library searches do not |
| Research-only brands | Create a brand from just a name to organize research. Add the brand's details before making ads |
| What this connection can do | Page sizes, how long a cursor lasts, the request rate, your daily reading allowance, which tools ask for approval |
| Weekly drop | Check whether this week's Monday drop arrived and its status |
| Save | Save ads to a swipe file and organize them into collections |
| Brands | See the brands in your account |
| Make an ad | Check the cost and approve it before anything is made. On the Claude address (`https://mcp.stealads.ai/mcp/claude`) this step is a link that opens the ad in the StealAds app instead |
| Account | Check your credits and the connected account |
| Help | Ask for help, report a problem or request a feature |

Searches return a capped number of results per call. There is no bulk export and no library total.

Permissions: **read** for searching and viewing, **write** for saving and tracking, **spend** for anything that uses credits. You approve these when you connect and can revoke them in StealAds Settings.

## Two versions of the connection

- `https://mcp.stealads.ai/mcp` offers the full set of tools. Use it for custom connectors and coding agents.
- The Claude directory version does research, tracking, saved ads, copy and brand tools, support, and a hand-off link for making an ad in the StealAds app. It does not generate images. Claude users get it in one click from the Connectors directory once StealAds is listed, so there is no link to paste.
