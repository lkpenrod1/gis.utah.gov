---
status: publish
layout: post
author:
  display_name: Matt Peters
  email: mpeters@utah.gov
tags: []
published: true
date: 2016-04-13 16:15:06
title: School Bus Routing based on SGID Roads
categories: []
---

A few months ago I had the opportunity to work with Marc Healy at the Granite School District Transportation department.  He was sending me corrections he needed to have performed on the SGID roads layer.  He told me that he was using the layer for a network.  I asked him to tell his story and provide some instructions, this follows below.

> I had originally thought of using the road layer as a network dataset about 2 years ago but I ran into problems because the dataset didn’t have certain attributes I needed. At the time, I contacted AGRC and was told that they were in the middle of setting up the parameters for a complete set of attributes, which included the ones I needed. Since this dataset would not work at the moment for what I needed, I turned to a private provider and purchased their road data for about $2500/year. This dataset allowed me to route buses across our district without a problem. It worked pretty well out of the box and only needed minimal set up. As we progressed through the year we changed our routing system to an online, GIS based software and it required a server version of this dataset or for us to provide our own road layer. The server version was around $20,000/year which was way beyond our budget so I turned back to the AGRC road layer as a solution to this problem. After reading several online forums and blogs I came up with how to use this dataset for routing and wrote those instructions on how to do it. While using this road layer takes time to set up, and has errors –  which take time to fix –  it has been well worth the savings for our district. The errors are easily resolved, and by sending the fixes to AGRC I am helping improve this dataset for anyone else who chooses to use it.

[Marc Healy's Network Dataset Instructions]({{ "/downloads/AGRC Roads Network.pdf" | prepend: site.baseurl }})

See Also: Marc's feedback inspired us to fish out an old post _from the AGRC wayback machine_. This [post]({{"/data/transportation/roads-system/create-network-analysis-dataset-instructions/" | prepend: site.baseurl }}) describes the steps taken to put together a GIS network analysis from the statewide road centerlines dataset back in 2011. Some of the steps may still be useful.
