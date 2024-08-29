## Infinite Driver graphics demo

As part of my computer graphics studies, my team implemented a real-time rendered physical simulation, showcased through a driving simulator. The simulation has following components: procedurally generated environments, physically based vehicle animations, and novel post-processing of the framebuffer output, achieving a unique non-photorealistic visual aesthetic.

My role in the project was to build a rendering pipeline and to implement a non-photorealistic style. The core component of this is a post-processing method of dithering an image (in the style of 1-bit computer displays) optimised for real-time 3D interactive use, using a spherically-mapped dither pattern to avoid flickering artefacts when the camera rotates. This technique was developed for the 2018 game Return of the Obra Dinn. I then extended this to create new visual effects: a 1-bit-per-channel RGB colour mode, a halftone dots comic/print dither pattern, and some experimental dither patterns created by hand.

I also implemented several other rendering algorithms: Blinn Phong shading, shadow mapping, and outline shading. In addition I developed C++ classes and functions for framebuffers and shader uniforms, extended and used Phuwasate’s OpenGL/C++ interface functions which ensure OpenGL objects are always properly created, destroyed, bound, and unbound, and integrated the rendering pipeline into the component-based scene graph.

Team members: myself (Rendering), Anfri Hayward (City and terrain generation), Phuwasate Lutchanont (Scene graph, physics library integration)

<iframe width="500" height="497" src="https://www.youtube-nocookie.com/embed/g4Fx0o5dygc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

![Rendering pipeline diagram](imgs/infinite-driver-pipeline.png)

{% capture titles %}{{ titles | append: "Infinite Driver|" }}{% endcapture %}
{% capture ids %}{{ ids | append: "infinite-driver-graphics-demo|" }}{% endcapture %}
