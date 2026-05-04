# 🇮🇹 OpenIPTVItaly

**OpenIPTVItaly** is an **open-source, public and curated Italian IPTV playlist**, designed to become **the reference playlist for free-to-air Italian TV channels**.

> 🎯 Goal: quality, reliability and transparency. No broken links, no pay-TV, no DRM.

## 📺 Content

The playlist includes **only publicly available and legally accessible streams**:

* 📡 National and local free-to-air TV channels
* 🧒 Kids channels
* 📰 News
* 🎬 Entertainment
* 🏟️ Free sports
* 📻 Radio (when available)

❌ **Not included**:

* Pay-TV channels
* DRM-protected streams
* Pirated or redistributed content

## 🧩 Playlist Structure

The playlist follows common IPTV standards:

* Consistent `tvg-id` for EPG matching
* Official `tvg-name`
* High-quality `tvg-logo`
* `tvg-chno` (LCN where applicable)

## 🔗 Playlist URL

### Main Playlist (with metadata)

Includes full channel metadata and standard playlist structure.

```md
https://raw.githubusercontent.com/danispagna78-beep/OpenIPTVItaly/refs/heads/main/OpenIPTVItaly.m3u
```

### Minimal Playlist (No EPG)

Simplified version with no EPG and no external dependencies.  
Recommended for maximum compatibility with basic IPTV players and Smart TVs.

```md
https://raw.githubusercontent.com/xN1ckuz/OpenIPTVItaly/refs/heads/main/OpenIPTVItaly_No_EPG.m3u 
```

## 📡 EPG Source

When available, EPG data is obtained from publicly accessible sources provided by **epgshare01.online**.

The EPG is used for informational purposes only and reflects standard TV scheduling
data that is already publicly available.
