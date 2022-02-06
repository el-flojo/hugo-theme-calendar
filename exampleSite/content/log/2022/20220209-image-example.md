---
title: "image example"
date: 2022-02-09T20:46:49-06:00
tags: ["nasa", "images","shortcodes"]
borderColor: '#378006'
backgroundColor: red
author: el-flojo
draft: false
output: ["json", "html"]
type: log
---

This log entry is an example about how to include images in log entries. 

Hugo ships with several [Built-in Shortcodes](https://gohugo.io/content-management/shortcodes/#use-hugos-built-in-shortcodes) for rich content, e.g. `figure`

{{< highlight md >}}

{{< figure src="../images/sun.jpg" width=500 title="The sun" >}}

{{< / highlight >}}

The Sun is the star at the center of the Solar System. It is a nearly perfect sphere of hot plasma, with internal convective motion that generates a magnetic field via a dynamo process. It is by far the most important source of energy for life on Earth.

[{{< figure src="../images/sun.jpg" width=500 title="The sun" >}}](../images/sun.jpg)

Images from the [NASA Image and Video Library](https://images.nasa.gov/details-GSFC_20171208_Archive_e000393.html).
