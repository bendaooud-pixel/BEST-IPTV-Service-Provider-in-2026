# What Are M3U Playlists and Xtream Codes? IPTV Connection Formats Explained

> A beginner-friendly explanation of the two main ways to connect to an IPTV service: M3U playlist URLs and Xtream Codes API. Learn the difference, which to use, and how to set them up.

**New to IPTV?** [96 TV LIVE](https://96-tv-live.com) supports both M3U and Xtream Codes on every device. Get started with a free 24-hour trial.

---

## The Two Ways to Connect to IPTV

When you subscribe to an IPTV service, you receive credentials to access the channel list. These credentials come in one of two formats:

1. **M3U Playlist URL** — a single web link that contains your entire channel list
2. **Xtream Codes API** — a server address plus a username and password

Both do the same thing: connect your IPTV player app to the provider's servers. The difference is in how they work and which apps support them.

## What Is an M3U Playlist?

M3U (Moving Picture Experts Group Audio Layer 3 URL) is a plain-text file format that lists media streams. In IPTV, an M3U file contains:

- Channel names
- Stream URLs for each channel
- Group/category tags (Sports, Movies, News, etc.)
- EPG (program guide) references

### What an M3U URL Looks Like

Your provider gives you a URL like:

```
http://provider.com:port/get.php?username=XXX&password=YYY&type=m3u_plus
```

You paste this URL into your IPTV player app, and it downloads the full channel list.

### Pros and Cons of M3U

| Pros | Cons |
|---|---|
| Universal — works in virtually every IPTV app and media player | Large file — can be slow to load with 45,000+ channels |
| Works in VLC, Kodi, and basic players | No built-in account management |
| Easy to share across devices | Channel list updates require refreshing the URL |

### Best Apps for M3U Playlists

- VLC Media Player (Windows, Mac, Android, iOS)
- GSE Smart IPTV (iOS, Android)
- Smart IPTV (Samsung, LG Smart TVs)
- SS IPTV (LG webOS)

## What Is Xtream Codes API?

Xtream Codes is a more structured login system designed specifically for IPTV. Instead of one long URL, you enter three fields:

- **Server URL** — the provider's address (e.g., `http://provider.com:port`)
- **Username** — your account username
- **Password** — your account password

The app then connects to the server's API and pulls your channel list, EPG data, VOD library, and account information in an organized format.

### Pros and Cons of Xtream Codes

| Pros | Cons |
|---|---|
| Faster loading — channels are fetched on demand, not all at once | Not supported by basic media players like VLC |
| Better organized — categories, EPG, and VOD are separate | Requires an app that supports the Xtream Codes API |
| Account info visible — see your expiry date and active connections | Slightly more fields to fill in during setup |
| Automatic updates — no need to manually refresh the playlist | |

### Best Apps for Xtream Codes

- TiviMate (Android, Fire Stick, Android TV) — best overall
- IPTV Smarters Pro (Android, iOS, Fire Stick, Apple TV, Windows, Mac)
- XCIPTV (Android, Fire Stick)

## Which Should You Use?

**Use Xtream Codes if your app supports it.** It's faster, better organized, and gives you more features (account info, auto-updating EPG, separated VOD library).

**Use M3U if:**
- You're using VLC or another basic media player
- Your Smart TV app only supports M3U URLs
- You want to use the playlist in Kodi

Most IPTV providers, including [96 TV LIVE](https://96-tv-live.com), provide both formats with every subscription. Your welcome email includes your Xtream Codes credentials and your M3U URL — use whichever your app supports.

## How to Find Your Credentials

After subscribing, your IPTV provider emails you:

1. **Server URL** — e.g., `http://provider.com:port`
2. **Username** — your unique login
3. **Password** — your unique password
4. **M3U URL** — the full playlist link (constructed from the above)

If you only received the M3U URL, you can extract the Xtream Codes credentials from it:

```
http://[SERVER]:[PORT]/get.php?username=[USERNAME]&password=[PASSWORD]&type=m3u_plus
```

---

## Get Started with 96 TV LIVE

[96 TV LIVE](https://96-tv-live.com) provides both Xtream Codes and M3U credentials with every plan. 45,000+ channels, 4K quality, and setup support for any device or app.

- **[Start your free trial →](https://96-tv-live.com/pricing.html)**
- **[WhatsApp support →](https://wa.me/212708437808)**
