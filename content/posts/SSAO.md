---
title: 'Screen Space Ambient Occlusion'
date: 2025-03-26T15:31:50+01:00
draft: false
hidden: false
externalURL: false
showDate: false
showModDate: false
showReadingTime: false
showTags: false
showPagination: true
invertPagination: true
showToC: true
openToC: false
showComments: false
showHeadingAnchors: true
---


| Type          | Description   |
| -----------   | -----------   |
| **Engine**    | Penugine      |
| **Timeline**  | ~1-2 weeks 50%|


{{% figure class="alignright" src="/ssaoEffect.png#floatleft"  %}}
<!--more-->
Screen Space Ambient Occlusion more commonly know as SSAO is a post processing technique that is used to aproximate how occluded a 3D scene pixel would be. This is done to adjust the worlds ambient light accordingly to mimic the effect of the pixels occlusion. This is done as a screen space pass taking in geometry positions and normals, hence the name Screen Space Ambient Occlusion.

# Implementation

{{% figure class="alignright" src="/SSAOIllustation.png#floatleft"  %}}




{{% figure class="alignright" src="/withoutSSAO.png#floatleft"  %}}


{{% figure class="alignright" src="/withSSAO.png#floatleft"  %}}