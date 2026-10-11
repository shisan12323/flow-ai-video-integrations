---
title: Flow AI Video for Webflow
---

# Flow AI Video for Webflow

Add an existing HTTPS MP4 video to a Webflow page from Designer. Create a clip on [Flow AI Video](https://flowaivideo.org/), host it at a public direct MP4 URL, then use the extension to place it on your page.

**Availability:** the extension is in testing and is not yet listed in the Webflow Marketplace. It is an independent companion, not a Webflow product.

## Add a video

1. Install the Flow AI Video Designer Extension and open it in Webflow Designer.
2. Select a section or div that can contain child elements.
3. Paste a public HTTPS URL that points directly to an MP4 file. Add an optional HTTPS poster-image URL.
4. Select **Add video**. The extension inserts a native HTML video element with playback controls.
5. Preview and publish the site, then play the video to confirm that the media host serves it correctly.

The extension does not upload, host, or generate video inside Webflow. Video generation happens separately on [flow ai video](https://flowaivideo.org/) and may require an account or paid plan. The extension itself is free and does not require a separate Flow AI Video account.

Only publish video and images you own or have permission to use. Do not paste private or signed URLs.

## Troubleshooting

- If **Add video** asks you to select a section or div, select a compatible container in Designer and try again.
- If a link is rejected, use an HTTPS URL pointing directly to a video file or image, not a webpage.
- If the element appears in Designer but playback fails on the published site, check whether the media host permits public retrieval and whether the URL has expired.

## More information

- [Privacy notice](webflow-privacy.html)
- [Terms of use](webflow-terms.html)
- [Support](webflow-support.html)
- [AI video generator website](https://flowaivideo.org/)
