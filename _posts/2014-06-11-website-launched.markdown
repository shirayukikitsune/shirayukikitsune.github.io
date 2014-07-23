---
layout: post
category: site
tags: [site, xbeat]
---
{% include JB/setup %}

Hello, everyone!

This website will contain general development tips and tricks. Also, it will be home to the news related to my project: the _XBeat_ game, which is hosted at GitHub, [here][2].

The game is a clone of the _Project Diva_ series, launched for a few [Sony](www.sony.com) [Playstation](www.playstation.com) consoles.

Using a DirectX 11 renderer, many jobs are done directly in the GPU, decreasing the need of a high-end CPU.

Right now, this is what is working:

  - Renderer is initializing
  - Skybox created
  - OBJ models for stages
  - PMX models are loaded
  - Postprocessing! [Image 1][1] [Image 2][3]
  - DirectInput for keyboard and mouse
  - Dynamic lighting, supporting up to 4 lights
  - Vertex and material morphs (these are still done on CPU)
  
What does _not_ work:

  - Bones transformations
  - The game itself :(
  - MENU! WE NEED A MENU!
  
Updates are going to be posted here :D

Current renderer status:

<img class="img-responsive" src="http://i.imgur.com/hGMwF7D.jpg"/>

[1]: http://i.imgur.com/w6MNCrK.jpg
[2]: https://github.com/shirayukikitsune/xbeat/
[3]: http://i.imgur.com/CAWGkoH.png
