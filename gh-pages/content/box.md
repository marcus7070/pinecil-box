---
author: "Marcus"
title: "Pinecil and tips case"
stlviewer: true
---

This model is created using Python and the [CadQuery](https://github.com/CadQuery/cadquery) module. 

{{< display-stl uid="topcap" file="top_cap.stl" >}}

The STL you see below is not exported on my machine. It is created from the source code by a GitHub action while preparing this website. Thanks to Nix and my [cq-flake](https://github.com/marcus7070/cq-flake), this process is byte-for-byte reproducible and you can fork the [pinecil-box repo](https://github.com/marcus7070/pinecil-box) and reproduce the same process yourself. 

Why would you want to do this? Because I'm using Python to generate the model. This comes with a whole bunch of advantages (`import numpy as np`), however I now have the freedom to create an enviroment so complex it's impossible to reproduce. But I'm not on my own here, I can just reuse the industry standard software development tools, like cloud servers and GitHub actions.
