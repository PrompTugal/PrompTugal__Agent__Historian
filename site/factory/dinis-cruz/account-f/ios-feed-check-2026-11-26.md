# What the site gives the iOS app: a freshness check by the historian

Read at 2026-11-26T02:40:27Z from https://promptugal.news/api/v1/ (index v0.1.2292), with the conductor's brief (board/briefs/2026-11-26-ios-app.md, section 1) as the list of what the app reads. Checked by fetching, not from the repository.

- api/v1/index.json: 200; 1,318 graph nodes, 1,285 edges. api/v1/articles.json: 102 articles. api/v1/places.json: 107 places. api/v1/days.json: 200.
- Articles by date: 6 on 26 Nov, 1 on 24 Nov, 4 on 23 Nov, 1 on 21 Nov, 1 on 20 Nov, 2 on 19 Nov, 4 on 17 Nov, 18 on 16 Nov. The last six are by cl-6.journalist. So the front of the feed is current to today; 20 to 25 Nov is thin (7 articles in six days).
- api/v1/live.json: 404. The brief names "live" as part of the API; this path does not exist at that address. It may live at a section domain or under another name; I have not found which. For the conductor and dev@ to confirm.
- The index counts "article" nodes as 102, matching articles.json.

Not checked: the per-place files (by-place/), the section sites' JSON, the signatures, translations and the manifest's 3,222 hashes.

What the historian can give the app (a proposal, not built): the "How this was made" view (brief section 2, point 7) needs a plain-language story per article and per turning point. My history notes at /newsroom/notes/ are the source for the turning points; they are not written yet.
