---
layout: post
category: xbeat
tags: [xbeat]
---
{% include JB/setup %}

Hello, everyone!

More progress with the [_XBeat_][1] game! 

Now the bone transformations aren't done every frame, but only when needed.
For this to work, a new vertex buffer was created, along with two new shaders: a passthru vertex shader
and a geometry shader.

With this, performance should improve a bit. Still, the code is not fully working (there are some screen
artifacts introduced with this, so I am trying to fix them) and hasn't been committed yet.

Also, I feel that I am really close to definitely finish this bone issue, since the deformations aren't
giving weird results anymore (there is still something wrong, but the results are getting better).

Soon I'll post screenshots of the new state :)

[1]: http://github.com/shirayukikitsune/xbeat/
