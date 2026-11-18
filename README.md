[README.md](https://github.com/user-attachments/files/35030677/README.md)
<p align="center">
  <img src="icon.png" width="96" height="96" alt="SpoilerShield icon">
</p>

<h1 align="center">SpoilerShield</h1>

<p align="center"><strong>Hide game spoilers before they reach your screen.</strong></p>

<p align="center">
  <a href="https://mikaelkristian.github.io/spoilershield/"><strong>Download page</strong></a> ·
  <a href="https://mikaelkristian.github.io/spoilershield/privacy-policy.html">Privacy policy</a>
</p>

---

SpoilerShield is a Chrome extension that removes **Grand Theft Auto VI** posts, videos, thumbnails, comments and search suggestions from **YouTube, Reddit, X, Instagram, TikTok and Google**, before they appear on screen.

Everything runs inside your browser. There's no account, no data collection and no network requests.

## Features

- **Hides whole items, not just words.** A matching video card, tweet, Reddit post or comment thread disappears completely.
- **Catches disguised spellings:** hashtags (`#GTA6`), punctuation tricks (`G.T.A. 6`), look-alike letters, accents and leetspeak (`GT4 V1`).
- **Covers whole pages** that are about the game, such as a video, a search, a subreddit or a hashtag page. The video is paused and the tab title is hidden. You can still choose to show a page.
- **Works on endless feeds** that load more posts as you scroll.
- **No flashes:** it starts before the page is drawn, so matching items never appear first.
- **Strict mode:** every card stays hidden until it has been checked. Cards with no text to check, such as image-only tiles, stay hidden.
- **Your own keywords:** block other games, shows or topics too.
- **Counts** of how many items were hidden, per page and in total.

## Install

### Chrome Web Store

SpoilerShield has been submitted to the Chrome Web Store and is **waiting for review**. Once it's approved, it will install with one click and update automatically. The link will be added here.

### Install manually (available now)

Works in Chrome, Edge, Brave and other Chromium browsers on a computer.

1. Download **[spoilershield-1.0.0.zip](https://mikaelkristian.github.io/spoilershield/spoilershield-1.0.0.zip)**.
2. Unzip it. On a Mac, double-click the zip. On Windows, right-click it and choose *Extract All*.
3. Move the `spoilershield-1.0.0` folder somewhere permanent, such as Documents. Chrome loads the extension from this folder every time, so don't delete it.
4. Go to `chrome://extensions`. In Edge use `edge://extensions`, in Brave `brave://extensions`.
5. Turn on **Developer mode** (top right).
6. Click **Load unpacked** and select the `spoilershield-1.0.0` folder (the one that contains `manifest.json`).
7. Reload any open YouTube, Reddit, X, Instagram, TikTok or Google tabs.

Chrome may sometimes remind you that developer-mode extensions are turned on. That's expected for extensions installed this way.

## Settings

Click the SpoilerShield icon in the toolbar to:

- turn it on or off, everywhere or for the current site
- switch between **Normal** and **Strict** mode
- see how many items were hidden

Open **Keywords & settings** to turn keyword categories on or off, add your own words, and test whether a phrase would be hidden.

> **Heads-up:** by default SpoilerShield also hides anything containing the words *Lucia*, *Jason*, *ending*, *death* or *dies*, even when it isn't about GTA. If that hides too much, turn off the **Spoiler words** category in Keywords & settings.

## Privacy

- No data collection, no analytics, no accounts, no AI services.
- The extension makes no network requests.
- Settings are stored only in your browser (`chrome.storage.local`) and are never synced.
- Permissions: only `storage`, plus access to the six supported sites.

Full details are in the [privacy policy](https://mikaelkristian.github.io/spoilershield/privacy-policy.html).

## Limitations

- **Text only.** SpoilerShield reads titles, captions, comments, image alt text and links. It does **not** analyse images or video, so a spoiler that exists only inside a thumbnail can get through. Strict mode hides cards that have no text to check.
- **Websites change.** If a site redesigns its pages, some items may slip through until the extension is updated. Strict mode with **fail-closed** turned on covers pages SpoilerShield can't recognise.
- Doesn't work in mobile browsers. Chrome on phones doesn't support extensions.

## Something got through?

Open an issue in this repository with the site, and the title or text that wasn't hidden. Please don't paste spoiler details in the issue title.

---

SpoilerShield is an independent project and is not affiliated with, endorsed by or sponsored by Rockstar Games or Take-Two Interactive. Grand Theft Auto is a trademark of its owners.
