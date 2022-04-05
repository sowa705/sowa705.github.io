---
layout: post
title:  "Anet A8 auto bed leveling with Marlin"
description: "Custom Z height probe for Anet A8"
date:   2022-04-05 10:15:00 +0200
categories: 3dprinting
thumbnail: /assets/bedlevelprobe_image.png
---
Anet A8 is a pretty terrible printer, it has absolutely zero frame rigidity and it cant really handle any printing speeds above 35mm/s. However the most annoying thing about it is how hard it is to level the bed, so after seeing [this post](https://www.reddit.com/r/ender3/comments/chs7qa/hello_all_im_a_new_happy_owner_of_an_ender_3/) showing an easy way to build an auto leveling probe on reddit i got inspired to build my own.

Of course that design wouldn't fit my Anet so i designed my own:
![Custom probe in F360](/assets/bedlevelprobe_design.png)
![Custom probe after printing](/assets/bedlevelprobe_image.png)

Stock firmware Anet comes with cannot handle auto bed leveling so i had to flash Marlin and configure it for my probe.
<iframe width="640" height="360" src="https://www.youtube.com/embed/G695zXSLUuM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

If there is any interest I'll publish the files but I'm not sure if the switch I used is available (I used a switch from an old microwave).