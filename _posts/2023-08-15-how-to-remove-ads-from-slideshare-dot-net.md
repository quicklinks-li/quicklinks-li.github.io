---
title: How to remove ads from slideshare.net
date: 2023-08-15 14:58:00 -0500
categories: [Ads]
tags: [websites, google, abp]     # TAG names should always be lowercase
---
## Step 1
Go to:
```
chrome-extension://cfhdojbkjhnklbpkdaibdccddilifddb/options.html
```
## Step 2
Click on advanced and scroll to the bottom.

## Step 3
Copy this into the "My filter list" box:
```
slideshare.net###google_ads_iframe_\/15184186\,22797863291\/slideshare_pushdown_0
slideshare.net##iframe[src="https://89a79d28fed867280a3ca0b7da948f5c.safeframe.googlesyndication.com/safeframe/1-0-40/html/container.html?upapi=true"]
slideshare.net##.wrapper-slideshare_pushdown.fs-pushdown
slideshare.net###slideshare_pushdown-pushdown-cls
slideshare.net##.fs-pushdown-sticky
slideshare.net###alongslide-player-ad
slideshare.net##.up-show
slideshare.net##.ImageInterstitialAd_container__QkHIG
slideshare.net##.InterstitialAd_root__1_iHN.InterstitialAd_active__bJxM8
slideshare.net##.AlongslidePlayerAd_root__foVJh
slideshare.net##.Modal_overlay__r_3vn
```
