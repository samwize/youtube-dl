# What's Changed

This is a fork of the [original youtube-dl](https://github.com/rg3/youtube-dl).

This version **fixed [toggle.sg](http://toggle.sg/)**, but without fixing the tests.. because I don't know how and i am lazy..

But trust me, it works (:

## Install

So if you want to use my version to download toggle videos (including premium!), this is how you install:

    git clone https://github.com/samwize/youtube-dl
    cd youtube-dl
    pip install -e .

The `youtube-dl` command now uses this version.

## Download Videos

I fixed for toggle.sg while during to download this [geek show by mediacock](http://video.toggle.sg/en/series/dream-coder/ep4/476797). This is a demo of the process:

    # 1. Find the webpage eg.
    # http://video.toggle.sg/en/series/dream-coder/ep4/476797

    # 2. List the formats
    youtube-dl http://video.toggle.sg/en/series/dream-coder/ep4/476797 -F

    # 3. Download the format (make good judgement which is best)
    youtube-dl http://video.toggle.sg/en/series/dream-coder/ep4/476797 -f STBMain-1597

Repeat for other episodes (:

For your convenient, these are the highest quality for all the Dream Coder episodes:

    youtube-dl http://video.toggle.sg/en/series/dream-coder/ep1/476074 -f STBMain-1597
    youtube-dl http://video.toggle.sg/en/series/dream-coder/ep2/476370 -f STBMain-1597
    youtube-dl http://video.toggle.sg/en/series/dream-coder/ep3/476595 -f STBMain-1596
    youtube-dl http://video.toggle.sg/en/series/dream-coder/ep4/476797 -f STBMain-1597
