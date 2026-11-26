# Aura Browser

**Aura** is a fast, lightweight (**4.0 MB** `.app`, **1.8 MB** `.dmg`), native macOS browser built with Swift, SwiftUI, WebKit, and Apple Speech Recognition.

**Developer:** `sntechwizard`

## Key Features

- **Voice-First Browsing (`⌘⇧V`)**:
  - Gemini-style **Voice Search Bubble** home page (`aura://home`) with live speaking text bubble and 1.0s auto-navigation.
  - Persistent **Bottom Voice Bubble** on every webpage.
  - Natural voice commands (*"new tab"*, *"private tab"*, *"reader mode"*, *"dark mode"*, *"open whatsapp"*, *"widgets"*, *"home"*, *"screenshot"*).
- **Isolated Modes (Spaces)**:
  - **Personal**, **Work**, **Study**, and **Music** workspaces—plus **Custom Modes** (`+` in sidebar)—each with isolated cookies, cache, and website data (`WKWebsiteDataStore(forIdentifier:)`).
- **Arc + Chrome Productivity**:
  - Collapsible **Left Sidebar** (`⌘\`) with Favorite tiles, Pinned tabs, and **Collapsible Tab Folders** (with right-click **Move to Folder** & **Delete Folder**).
  - **Speed Tabs**: `⌘1`–`⌘5` and `⌘⌥→` / `⌘⌥←`.
  - **Split View**: View two tabs side-by-side.
  - **Memory Saver (`⌘⇧H`)**: Automatic + manual tab hibernation to keep RAM low.
  - **Private / Incognito Tabs (`⌘⇧N`)**, **Reopen Closed Tab (`⌘⇧T`)**, **Bookmarks (`⌘D`)**, **Reading List**, **History**, **Downloads**, **Find in Page (`⌘F`)**, **Save as PDF (`⌘P`)**, **Screenshots**, and **Native Share Sheet**.
- **Chat-Focused Mode (`⌘⇧M`)**:
  - 1-click switcher for **WhatsApp**, **Instagram**, **Telegram**, **Discord**, **X**, **Slack**, and **Messenger**.
- **Widgets Sidebar (`⌘⇧W`)**:
  - **Time & Date**, **25:00 Focus Timer**, **Music Player** (Play/Pause/Next/Prev + Now Playing title + YT Music/Spotify/SoundCloud), **Space Notes**, **Widget Library** presets, and **Custom Widgets**.
- **Developer Mode (`⌘⇧D`)**:
  - Live **JavaScript Console**, **Hard Reload**, **View Page Source**, **Web Inspector**, and **Phone/Tablet Responsive Simulator** (Desktop, iPhone, Android, iPad).
- **Chrome Extensions (MV2 / MV3)**:
  - Load unpacked extension folders (`manifest.json` `content_scripts`) from the toolbar puzzle icon.
- **Dark Mode & Palettes**:
  - 1-click **Dark / Light Mode** toggle that syncs `prefers-color-scheme: dark` and forces dark mode on light pages, plus 6 customizable color palettes in **Settings**.
