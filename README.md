# Token Barometer issues

This is the public issue tracker for [tokenbarometer.com](https://tokenbarometer.com), a daily LLM API price tracker with price history and a cloud vs local calculator.

The site code is not in this repo. It is closed for now. The data is open (CC BY 4.0), and so is everything about how it is produced: see the [methodology page](https://tokenbarometer.com/methodology).

## When to open an issue

- A price on the site does not match what the vendor shows
- A model or host is missing
- A model is mapped to the wrong vendor or the wrong page
- Something is broken or renders badly
- A calculator result looks wrong and you can say why

Use the "Wrong price" template for the first three. For a wrong price, the vendor's own pricing page URL is the thing I need most.

## What happens next

I check the vendor page, fix the parser or the alias, re-run the import, and close the issue with a link to the corrected page. Fixes usually show up after the next daily refresh (05:10 UTC).

If several sources disagree, the most authoritative one wins (vendor page, then OpenRouter, then aggregators). If I cannot verify a report, I will say so in the issue rather than guess.

## Not here

Feature requests are welcome but go on the [roadmap page](https://tokenbarometer.com/roadmap) first; open an issue only if something there is unclear. For anything else, I am [@dstrbad](https://x.com/dstrbad) on X.
