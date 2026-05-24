# ANI-STREAM Site Map & Export Guide

I've organized your project screens into a logical site structure. When you export these as HTML files, you can use the suggested filenames to link them together easily.

## 1. Public Discovery (Landing)
- **File:** `index.html`
- **Screen:** {{DATA:SCREEN:SCREEN_4}} (ANI-STREAM | New Releases Countdown)
- **Purpose:** The main entry point for new visitors.

## 2. User Experience (The App)
- **File:** `home.html`
- **Screen:** {{DATA:SCREEN:SCREEN_10}} (ANI-STREAM | Home)
- **Purpose:** The main dashboard for logged-in users.

- **File:** `search.html`
- **Screen:** {{DATA:SCREEN:SCREEN_15}} (Search Results - Hover Preview)
- **Purpose:** Discovery and filtering.

- **File:** `details.html`
- **Screen:** {{DATA:SCREEN:SCREEN_2}} (Anime Series Details)
- **Purpose:** Information about specific titles.

- **File:** `watch.html`
- **Screen:** {{DATA:SCREEN:SCREEN_13}} (Watch | Episode 01)
- **Purpose:** The video player interface.

- **File:** `profile.html`
- **Screen:** {{DATA:SCREEN:SCREEN_6}} (My Dashboard | ANI-STREAM)
- **Purpose:** User history and watchlist.

## 3. Admin Control Center (AniControl)
- **File:** `admin-dashboard.html`
- **Screen:** {{DATA:SCREEN:SCREEN_12}} (Admin Dashboard - Overview)
- **Purpose:** High-level platform metrics.

- **File:** `admin-library.html`
- **Screen:** {{DATA:SCREEN:SCREEN_11}} (Admin - Library Management)
- **Purpose:** Managing the anime catalog.

- **File:** `admin-analytics.html`
- **Screen:** {{DATA:SCREEN:SCREEN_14}} (Admin - User Analytics)
- **Purpose:** Deep dive into user behavior.

- **File:** `admin-moderation.html`
- **Screen:** {{DATA:SCREEN:SCREEN_8}} (Admin - Content Moderation)
- **Purpose:** Managing user reports and safety.

---

### How to Link Your Pages
In the HTML code of your navigation bars, replace placeholders with these filenames. 
*Example:* `<a href="admin-dashboard.html">Admin</a>`