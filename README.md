# Team Minik 101 Assistant

A chat-style search page for the Team Minik 101 agent resource site:
https://sites.google.com/teamminik.com/team-minik-101/home

Agents type what they need (for example "expired listing script" or "open house kit") and get the matching files, training videos, links and site pages, plus quick answers for common questions.

Live page: https://transactionsupport.github.io/Team-Minik-101/

## Files
- `index.html` is the chat page. It runs entirely in the browser, with no API key and no cost.
- `kb.json` is the knowledge base. It holds every page, embedded file and link from the Google Site, plus the quick answers.

## Updating
When the Google Site changes, `kb.json` needs to be rebuilt from the site and re-uploaded. The page picks up the new file automatically.

Tip: `?q=` in the URL runs a search, e.g. `.../Team-Minik-101/?q=fsbo%20script`.
