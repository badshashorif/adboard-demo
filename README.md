# Adboard: live app demo

Adboard puts product and service offers from many companies into one app. Users browse full-screen offer cards, search by location and category, compare offers, and go to the company's own website.

**Live demo:** https://badshashorif.github.io/adboard-demo/

## What the demo shows

- **Home feed:** story-style offer cards and video ads, with music and a Bangla voiceover.
- **Search:** filter by location (current location, or division → district → upazila) and by category and subcategory.
- **Compare:** open an offer's details and compare it with other offers in the same category.
- **▶ tab (entertainment):**
  - **Athena Originals:** the first feed, AI animation, drama and thriller shorts from Athena Motion Studio.
  - **YouTube Shorts and TikTok:** tap the top-right button or swipe to switch. These are real public videos, played through the official [YouTube IFrame Player](https://developers.google.com/youtube/iframe_api_reference) and the [TikTok Embed Player](https://developers.tiktok.com/doc/embed-player/).

## Notes

- All brands, prices and offers are samples.
- The Athena clips and the music are Mixkit stock (free license) and stand in for the real content.
- YouTube and TikTok videos are embedded, not downloaded. Rights stay with their creators.
- The demo is a single static `index.html` with no build step. GitHub Pages serves it from the `main` branch.
