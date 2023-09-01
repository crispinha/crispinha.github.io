## Live Performance Tool

{% capture titles %}{{ titles | append: "Live Performance Tool|" }}{% endcapture %}
{% capture ids %}{{ ids | append: "live-performance-tool|" }}{% endcapture %}

This is a live performance tool for looping and processing sampled and live-recorded loops and field recordings using granular synthesis. I built it as the technological component for my final performance in the taonga puoro course taught by [Rob Thorne](http://www.robthorne.co.nz/), so I could design the project around what I needed for that performance and for the way I play taonga puoro — in particular a focus on improvisation, continuous or flowing gestures rather than quantised or “grid-based” ones, and a focus on supporting or extending the natural timbre of the puoro rather than distorting or synthesising timbre. 

This was built using p5.js, and features audio recording and processing (in part using the [granular-js library](https://github.com/philippfromme/granular-js)) and a heretical UI system that allows for signal chains to be added and removed.

Click screenshot to open, [source code on Github](https://github.com/crispinha/cmpo-major-project).

[![Screenshot of synthesiser]({{site.url}}/imgs/385-final.png)](https://editor.p5js.org/crispinha/full/kaFg2uICc)