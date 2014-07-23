---
layout: post
category: xbeat
tags: [xbeat]
---
{% include JB/setup %}

Hello, everyone!

More progress with the [_XBeat_][1] game! 

Added support for loading multiple models :)
![Hello from SeeU and Miku!][2]

Also, I fixed the lighting calculation when bones are rotated (vertex normals weren't being updated)

_Update notes_: These weren't commented on git:

  - Bone transformations aren't using Bullet's quaternions anymore, only DirectX's Math library.
  - Cleaning more deprecated code in PMXBone (related to vertex updates)
  - Disabled some of the post-process effects (they work, disabled just for better screenshots :P)

[1]: https://github.com/shirayukikitsune/xbeat/
[2]: http://i.imgur.com/pix3Wt3.png
