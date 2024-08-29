## Physical Modelling DSP plugin for VCV Rack

As part of my Honours study I created three instruments using physical modelling techniques for the VCV Rack virtual modular platform. The three instruments showcase different DSP techniques: waveguides and Karplus-Strong string synthesis, modal synthesis, and reed modelling. I programmed the instruments in C++ and have developed a C++ library of DSP classes. I have created a user interface for each instrument which distils the underlying DSP parameters into a smaller set which is musically interesting and does not require the composer or performer using the instrument to understand the technical construction of the instrument.

![Modules in VCV Rack](imgs/vcv-modules.png)

{% capture titles %}{{ titles | append: "VCV Rack plugin|" }}{% endcapture %}
{% capture ids %}{{ ids | append: "physical-modelling-dsp-plugin-for-vcv-rack|" }}{% endcapture %}
