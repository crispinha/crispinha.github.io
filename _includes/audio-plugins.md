## Audio (VST) Programming

I have been teaching myself lower-level audio programming to further combine my sonic arts and computer graphics practices. I have been doing this with C++ and the JUCE framework to create VST/AU/etc audio plugins. I created the Delrus plugin, which applies a chorus effect to the feedback path of a delay, to practice creating a whole plugin start to finish, and to implement all the features essentially every plugin will need: audio processing, DAW-accessable and saveable parameters, UI controls and layout, UI theme, JUCE modules, and building with CMake and the Projucer.

[Source code on GitHub](https://github.com/crispinha/audio-plugins)

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/nBEYRxro17U?si=2K1OeTbIVTPqVHdv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

{% capture titles %}{{ titles | append: "Audio (VST) Programming|" }}{% endcapture %}
{% capture ids %}{{ ids | append: "audio-vst-programming|" }}{% endcapture %}