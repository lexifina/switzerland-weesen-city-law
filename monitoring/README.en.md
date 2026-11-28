<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Weesen only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 08:15 UTC, Weesen: systematic collection (weesen.tlex.ch): 19 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Weesen: systematic collection (weesen.tlex.ch)](https://weesen.tlex.ch/) | `<act>/` | daily | 2026-11-28 08:15 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 08:14](checks/2026-11.md#ch-lexwork-weesen-city-20261128t081438z) | lexwork-weesen-city | 19 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-28 07:08](checks/2026-11.md#ch-lexwork-weesen-city-20261128t070812z) | lexwork-weesen-city | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-28 06:38](checks/2026-11.md#ch-lexwork-weesen-city-20261128t063854z) | lexwork-weesen-city | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-27 06:52](checks/2026-11.md#ch-lexwork-weesen-city-20261127t065200z) | lexwork-weesen-city | 18 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-26 06:54](checks/2026-11.md#ch-lexwork-weesen-city-20261126t065411z) | lexwork-weesen-city | 18 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-25 08:00](checks/2026-11.md#ch-lexwork-weesen-city-20261125t080017z) | lexwork-weesen-city | 18 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 12:41](checks/2026-11.md#ch-lexwork-weesen-city-20261124t124108z) | lexwork-weesen-city | 18 | 0 | 0 | 0 | 0 (0) | no change | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
