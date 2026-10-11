---
title: Companion Privacy Notice
---

# Flow AI Video Companion Privacy Notice

Effective date: 11 October 2026.

This notice covers the Flow AI Video companion for Canva. It does not replace the privacy terms of Canva, GitHub, or the external [Flow AI Video website](https://flowaivideo.org/).

## Data used by the companion

The companion processes the video URL and cover-image URL or local cover file that you supply. The inputs are held in the running app's memory to complete your requested import. It does not implement its own user database, account system, analytics tracker, or advertising tracker.

When you import, the companion sends the video URL and cover information to Canva through its Apps SDK. Canva retrieves and stores the imported assets and adds the video to your design. A local cover is resized in your browser and uploaded to Canva as an image asset. The companion requests a temporary Canva URL for that uploaded image to use it as the video cover.

The companion does not send your Canva design contents to Flow AI Video. Clicking the website link opens the external website, which operates separately and may process its own account, payment, and generation data.

## Storage and deletion

The companion has no separate server-side storage of your imported media. Canva retains imported assets and designs under its own settings and policies. Closing or reloading the app clears its in-memory input state, but does not delete assets already uploaded to Canva. Manage or delete those assets through your Canva account.

## Public links and hosting

Only use media links suitable for access by Canva. Avoid confidential content or links containing credentials. The media host receives requests when Canva retrieves a file. These documentation pages are hosted on GitHub Pages, which processes web requests under its own privacy policy.

## Permissions

The companion uses Canva asset upload/access and design-editing capabilities for the import you request. Reading an uploaded cover's temporary URL is part of that workflow. It does not scan your other designs or retrieve your account's asset library.

## Contact

For questions about the companion, email [support@flowaivideo.org](mailto:support@flowaivideo.org). Do not include passwords, API keys, private media, or payment details in a support message. Information you send in an email is processed through the support mailbox rather than the companion.
