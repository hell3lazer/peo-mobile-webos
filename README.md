# PEO Mobile App for webOS

**PEO Mobile** is a lightweight webOS TV webapp that embeds the **SLT-Mobitel PEO Mobile** website (peomobile.com) in a fullscreen, scrollable iframe optimized for LG webOS smart TVs. 

> ⚠️ **Disclaimer**: This app embeds the official SLT-Mobitel PEO Mobile website. The developer has **only built the webOS wrapper for educational purposes** and has no affiliation with SLT-Mobitel. All content and services belong to SLT-Mobitel.

## ✨ Features
- **Fullscreen Embedding**: Renders peomobile.com at full TV resolution with native scrolling
- **Performance Optimized**: Async script loading, deferred iframe src, minified resources for **2-5x faster startup**
- **Smart Error Handling**: Automatic reloads (5 attempts), connection issue overlay with manual retry
- **Native webOS Integration**: Handles `webOSLaunch`, `webOSRelaunch`, and platform back key (461)
- **Visual Feedback**: Smooth gradient loader with spinner during initialization
- **Cache Busting**: Automatic timestamp parameters prevent stale content
