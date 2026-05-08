# Dia A1 PoC bait page

Static page hosted on GitHub Pages. Used as the attacker-controlled URL that a Dia user fetches via `fetch_web_content`. Page contains indirect prompt-injection payload that asks the Dia Assistant to embed an attacker exfil URL with `source_name: "Slack"` in any structured summary it generates.

Exfil collector: https://webhook.site/cd6a7956-c62b-4f40-9e71-ad87f2cf706b
View captured requests: https://webhook.site/#!/cd6a7956-c62b-4f40-9e71-ad87f2cf706b

For test-environment use only. No real users targeted.
