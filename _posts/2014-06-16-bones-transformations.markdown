---
layout: post
category: xbeat
tags: [xbeat]
---
{% include JB/setup %}

Hello, everyone!

I am having quite a good progress with the [_XBeat_][1] game. 

Right now, I am working with the bones transformations, that is, rotation and translation.

By now, I am quite pleased with the speed of it, since it is done in the vertex shader.
There is still room to improve, using the geometry shader stream output - but I don't think that it will be useful, since the models will be updated almost every frame.

Here are some examples of how it works: 

Initial Position:
![Initial][2]

After a transformation (using bone morph, full weight - 1.0):
![First bone morph, full weight][3]

Same morph, using different weight:
![Same morph, different weight][4] 

I still need to fix it, when chaining bones (these wings have only two bones each), as can be seen here:
![Still failing :(][5]                  

Even so, this is quite a good progress, and I am looking forward to finish this! :D               

[1]: https://github.com/shirayukikitsune/xbeat/
[2]: http://i.imgur.com/UZaZH1a.png
[3]: http://i.imgur.com/pCc2sqY.png
[4]: http://i.imgur.com/siyfWKK.png
[5]: http://i.imgur.com/8qRwv5M.png
