due to ongoing internet shutdown in iran, accessing independent news is increasingly difficult.
however, github is reachable through some SNI proxies. this repo publishes daily news archives,
downloadable directly using curl:

```sh
$ curl --connect-to ::62.220.112.46 \
    https://github.com/amiremohamadi/sabok.news/releases/download/daily-bundles-2026-03-13/theirandesk_1404-12-22_part-1_low.zip \
    -L -o news.zip
```

replace the date in the url with today's date to get the latest bundle.
