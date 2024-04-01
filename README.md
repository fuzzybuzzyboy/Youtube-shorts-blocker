# What is this repository?

This repository is for those who absolutely hate seeing YouTube shorts on their homepages and other places.

## How do I block YouTube shorts?

- Install an ad blocker (I use uBlock Origin).
- Open the `.txt` file in this repository and copy the text from there.
- Go to your ad blocker's custom filter settings and paste the copied text into the filter.
- Save the custom filter.

> Go to YouTube and check to see if YouTube shorts are blocked.
> -
> If these steps do not work, please create an issue in this repository.

## Extra features I added

If you're wondering about the filters for YouTube Kids, YouTube Premium, and the Explore area, it's because I added them to the filter. To remove them, simply go back to your filter and delete the following:

```txt
! Block YouTube Kids from the homepage sidebar
www.youtube.com##ytd-guide-section-renderer.style-scope:nth-child(4) > div:nth-child(2) > ytd-guide-entry-renderer:nth-child(4) > a:nth-child(1) > tp-yt-paper-item:nth-child(1) > yt-formatted-string:nth-child(3)
www.youtube.com##ytd-guide-section-renderer.style-scope:nth-child(4) > div:nth-child(2) > ytd-guide-entry-renderer:nth-child(4) > a:nth-child(1) > tp-yt-paper-item:nth-child(1)
www.youtube.com##ytd-guide-section-renderer.style-scope:nth-child(4) > div:nth-child(2) > ytd-guide-entry-renderer:nth-child(4) > a:nth-child(1)
! Block YouTube Premium from the homepage sidebar
www.youtube.com##ytd-guide-section-renderer.style-scope:nth-child(4) > div:nth-child(2) > ytd-guide-entry-renderer:nth-child(1) > a:nth-child(1) > tp-yt-paper-item:nth-child(1) > yt-formatted-string:nth-child(3)
www.youtube.com##ytd-guide-section-renderer.style-scope:nth-child(4) > div:nth-child(2) > ytd-guide-entry-renderer:nth-child(1) > a:nth-child(1) > tp-yt-paper-item:nth-child(1)
www.youtube.com##ytd-guide-section-renderer.style-scope:nth-child(4) > div:nth-child(2) > ytd-guide-entry-renderer:nth-child(1) > a:nth-child(1)
! Block 'explore new blah blah'
www.youtube.com##ytd-guide-section-renderer.ytd-guide-renderer.style-scope:nth-of-type(3)
```

If these steps don't work, please create an issue on this repository.
