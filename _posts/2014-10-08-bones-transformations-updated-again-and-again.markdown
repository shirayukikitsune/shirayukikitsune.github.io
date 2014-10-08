---
layout: post
category: xbeat
tags: [xbeat]
---
{% include JB/setup %}

Hello, everyone!

Even more progress with the [_XBeat_][1] game! 

This time it seems to be real - bone deformation is working.

Also, it has been a while since I last posted here, so I will add an update: physics are now working!

Yes, bone deformations due to rigid bodies are fully implemented and functional:

This is the debug rendering of joints (constraints):
<img class="img-responsive" src="http://i.imgur.com/dGlF795.png"/>

This is the debug rendering of rigid bodies (note that capsules are rendered using cylinders)
<img class="img-responsive" src="http://i.imgur.com/6CFADdw.png"/>

And this is the combined debug rendering: 
<img class="img-responsive" src="http://i.imgur.com/KHk6ejQ.png"/>

Also, note that the debug rendering does not consider the initial rotation, so the bodies and joints seems "off", but they work properly.

[1]: https://github.com/shirayukikitsune/xbeat/
