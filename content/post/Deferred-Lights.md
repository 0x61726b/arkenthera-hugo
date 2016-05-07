+++
date = "2016-05-07T19:27:14+03:00"
draft = false
title = "Deferred Lights"
image = "plight1.jpg"
blogpost = "http://arkenthera.github.io/blog//Deferred-Lights-in-Yume-Engine-using-stencil-test/  "
+++

Since Yume is fully deferred,there has to be a way to implement lights.In a deferred pipeline,we must create a pass for each light,be it directional, point or spot light.
For each point light,we draw a tesellated sphere,move it to lights
