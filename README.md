# bang-bookmarks
A manually crafted bookmarks.html file importable with similar functionality to [DuckDuckGo's !bang shortcuts](https://duckduckgo.com/bang?c=Tech&q=security) using [Bookmark Keywords, or _Keymarks_ if you're a fancy](http://johnbokma.com/firefox/keymarks-explained.html).

Why use this? Well it won't share your search query with DuckDuckGo, and you also won't need to wait for your query to be redirected from DDG. So it might save you.. 20 minutes of your life? You're welcome.

### Caution: Backup your bookmarks first. If something screws up, I don't want you losing your links!

## Instructions

- Download the [latest bookmarks.html](https://raw.githubusercontent.com/jameshealyio/bang-bookmarks/main/bookmarks.html) from this repository to your local disk
- Open Bookmarks Manager in Firefox
- Under *Import and Backup* select *Import Bookmarks from HTML*
- Select the bookmarks.html
- Wait 5-10 minutes, there's more than 10,000 bookmarks/shortcuts to add. If you have syncing on, it'll likely sync before reflecting those changes first too.
- Try `!github test` in your address bar, see if it resolves to `github.com/search?q=test&type=Everything&repo=&langOverride=&start_value=1` without going to DuckDuckGo first

If you want to make further changes to these, or add your own - just edit the individual bookmark entries to see how they're done. The Keyword field is the !bang shortcut (if you want to change , and `%s` is usually where your search query will go in the URL field.
