# uBlockOrigin AI Blocklist (for DuckDuckGo)
A huge blocklist of manually curated sites (1000+) that contain AI generated content, built for use on DuckDuckGo with uBlock Origin.
Tested with standard and HTML DDG, known to work on home page and images page.

### Installing it with uBlock Origin

1. Make sure that you have the uBlock Origin Extension for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/), [Chrome](https://chromewebstore.google.com/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm), or any browser that supports uBlock Origin

2. Click on the uBlock Origin Extension, and in the bottom right, there is a cog-wheel symbol--named the dashboard. Click it.

3. Once you are in the dashboard, look towards the top. Click on the tab that says "Filter lists".

4. Look towards the bottom, and expand the ```Import``` button.

5. Copy and paste this URL into the dialogue box: 
```
https://raw.githubusercontent.com/ImperitusSoftware/AI-Blocklist-For-DuckDuckGo/refs/heads/main/list.txt
```

6. Apply changes, and you're set!

> [!TIP]
> uBlock Origin will automatically refresh the filter list once a day, so you'll always have up-to-date filters.
> If you want to force an update of the filter list, pressing the stopwatch next to the newly added list, then pressing ```Update now``` will achieve that.


> [!IMPORTANT]
> Extension not working as expected? Try this! If your newly imported list isn't working, it may be because of an outdated web browsing session. If your web browser hasn't been closed in a long time, there's a chance the session won't update how it should, meaning importing this list into uBlock Origin or uBlacklist won't function correctly.
> Try creating a new session, aka closing <ins>**all**</ins> web browser windows, waiting until all processes are fully closed (4-5 second wait), then re-open your web browser. That should fix it. If not, then try clearing your browser's cache.

## Additional lists

As of right now, there are two lists. The [main](github.com/ImperitusSoftware/AI-Blocklist-For-DuckDuckGo/blob/main/list.txt) default list, and the [nuclear](github.com/ImperitusSoftware/AI-Blocklist-For-DuckDuckGo/blob/main/nuclear.txt) list.

The nuclear list has sites that contain a mix of authentic and AI generated imagery (eg. DeviantArt, Artstation, Stock Photography sites, etc), which make it tricky to outright block in the main filter list, so I've designated it to a separate list that you can toggle on and off if you so desire.


<details>
<summary>uBlock Origin Nuclear List (expand me) </summary>
<br>

```
https://raw.githubusercontent.com/ImperitusSoftware/AI-Blocklist-For-DuckDuckGo/refs/heads/main/nuclear.txt
```

</details>

## Extended Filtering

It is possible to filter AI results based on keywords. It was originally in the list, but it's been taken out to make it configurable and/or optional (since it is a blanket ruling, and doesn't care about context).

### uBlock Origin
In your personal filter list, you can use this template to add your own keywords you would like to block.

```
duckduckgo.com##:has(a[href*="example.com"])
```
Replace example.com with your preferred keywords. A short list of **optional** procedural filters that you can use for uBlock Origin are listed in a dropdown below:

## Happy Pride Month!
LGBTQ+ Rights! 🏳️‍🌈🏳️‍⚧️

## Special Thanks

Special thanks to: 

+ This [pastebin](https://pastebin.com/B8kP4imQ) (since it added even more sites to my blocklist)

+ u/AchernarB for the [awesome snip-bit of code.](https://www.reddit.com/r/uBlockOrigin/comments/13uyex5/how_to_block_results_from_a_specific_site_in_the/)

+ Raymond Hill, [uBlock Origin extension](https://github.com/gorhill/uBlock)

+ iorate, [uBlacklist extension](https://github.com/iorate/ublacklist)

## Related Projects

[Super SEO Spam Suppressor (SSSS)](https://github.com/NotaInutilis/Super-SEO-Spam-Suppressor) by NotaInutilis

> An anticapitalist blocklist targeting websites abusing SEO tactics to spam web searches with data pollution and security risks: content farms, scrapers, copycats, generative AI, scams, advertisements, malwares, and useless wasteful garbage in general. It is best used with uBlacklist. 

[Journey Buster 3](https://journeybuster.com/) by k0vac

> A Chromium extension that lets you know if an image is AI generated, for use on Twitter.

[Awesome List of uBlacklist Subscriptions](https://github.com/rjaus/awesome-ublacklist) by rjaus

> A compilation of awesome uBlacklist subscriptions to block various sites from appearing in Google, Bing, or DuckDuckGo search.

[Anti-AI Google Search Tips](https://github.com/laylavish/TipsTricksGoogleSearch) by yours truly

> Tips and tricks to make Google Search (and other search engines that have similar operators) return authentic imagery.
