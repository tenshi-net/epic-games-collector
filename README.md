# Epic Games Collector

This filter list removes almost every site element and feature from the website version of the Epic Games Store. I only use the website to collect freebies, so I used my ad blocker to remove things and make it more about the free games claim box so I can quickly check for and claim new free games on the site.

It does leave the menu bar with the search bar, wishlist, cart, etc. as well as the sitemap (couldn't filter specifics so I left it) and the menu bar at the very top of the site. I didn't want to completely remove functionality, just clean up the home page. Game pages, the search pages and everything else appear to be working just fine after applying these filters.

This filter might be relatively niche but if you mostly use Epic for the free games, maybe it'll make your life a little less annoying!

#  How to use

There are two ways you can add this. The simplest way is to add the URL of the `epic-collector.txt` file to your ad blocker's filter lists. Alternatively, you can add a non-updating version by directly copying the data from the file and pasting it as a custom filter rule.

## Brave Shields

Click on the Brave Shields icon in the address bar and selecting the **Filter lists** button at the bottom of that menu. Navigate to **Add custom filter lists** and paste the [URL to the file](https://raw.githubusercontent.com/tenshi-net/epic-games-collector/refs/heads/main/epic-collector.txt) in the text box.

_For the non-updating version:_ copy the data from `epic-collector.txt`. Navigate to the **Create custom filters** section and enable Developer mode. From there, copy the contents of `epic-collector.txt` and paste them at the bottom of the **Create custom filters** menu and save your changes.

## uBlock Origin

Open your uBlock settings menu. Navigate to the **Filter lists** tab. Scroll to the bottom, to the section labeled "Import...". Paste [the URL](https://raw.githubusercontent.com/tenshi-net/epic-games-collector/refs/heads/main/epic-collector.txt) into that text box and select **Apply changes**.

_For the non-updating version:_ copy the data from `epic-collector.txt`. Navigate to the **My filters** tab. Paste the contents of `epic-collector.txt` to the bottom of the text section. Ensure "Enable my custom filters" is ticked and then **Apply changes**.
