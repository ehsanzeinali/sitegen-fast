# sitegen-fast

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/ehsanzeinali/sitegen-fast/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/ehsanzeinali/sitegen-fast/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

sitegen-fast is a faster drop-in for make.fun's own makefun-site 1.0.0 static site generator: `solve.js` returns exactly the output tree makefun-site returns for a case, byte for byte — its own front matter, template dialect, Markdown subset, slug rule and report — and `main.ts` answers every case in `/input/cases.json`. It is faster by compiling each template to plain JavaScript once per case, rendering Markdown in a single pass without token arrays, and caching slugs per case. Practice score: 3/3 cases identical to the reference, about 2.5× faster than the house baseline on this machine.

## Run it

```sh
node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=j0ggf405&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
