---
layout: post
title: Personal Embeds
date: 2023-11-24
categories: 
tags: 
aliases:
  - Personal Embeds
cover-img: https://source.unsplash.com/ugm-yDj9Hi4
permalink: 
description: 
image: 
created: 2023-11-24T12:38+11:00
updated: 2023-11-25T13:40+11:00
---
# Personal Embeds
Having been writing on this blog for a while now, I'd like to find the best way to embed quick videos for reference.

I currently use google photos, but annoyingly there is no evergreen way to link to a video hosted on google photos (their photos seem to work okay if you use )

## Google Photos
Video share link created on 2023-11-25, using [this tool](https://www.publicalbum.org/blog/embedding-google-photos-image).
However this doesn't display in a jekyll website nor in a website hosted by obsidian, so I have a feeling this method won't work unfortunately. Strangely, it will display in my local obsidian files - more investigation needed.
<div style="width:100%;height:480px;background-color:black;text-align:center;">
  <video style="height:100%;" controls>
    <source src="https://lh3.googleusercontent.com/pw/ADCreHdueV-upAkPNX1AaAqbfizHrdGRYxqR9c0ciRugZLKrQPreYTpkG762vavlD68NDyEJOcblgZldEo3IDXEvBiLi7dd93UkWAP5YgVDN2C6enoPyS2jB=m18" type="video/mp4">
  </video>
</div>
Trying with an iframe does not work either.

## Google Drive
Next up is google drive. Since google photos and drive [removed the ability to access google photos in drive](https://blog.google/products/photos/simplifying-google-photos-and-google-drive/)

I have an image I'm linking to from Dropbox:
![](https://www.dropbox.com/scl/fi/oey3qw850g2ofnkifxzz6/Screenshot-2023-08-01-183417.png?rlkey=ejp3dhekzaqnposal7mr3escd&raw=1)
And a dropbox video:
<div style="width:100%;height:480px;background-color:black;text-align:center;"> <video style="height:100%;" controls> <source src="https://www.dropbox.com/scl/fi/7i1vg22caklsxvx5kmgqw/MVI_0935.MOV?rlkey=lgwtwk0pqv67w53rcgknqqtug&raw=1" type="video/mp4"> </video> </div>
