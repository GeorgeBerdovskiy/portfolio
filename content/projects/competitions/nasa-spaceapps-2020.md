---
title: "NASA Space Apps 2020"
tags: ["Flask"]
aliases:
- /spaceapps20.html
---

{{< banner path="/images/detail/SpaceApps2020Banner.png" >}}

{{< section-header kind="description" title="Description" >}}

For NASA Space Apps 2020, I worked with my friend Shuzheng (Tom) Zhang to build the HEASARC and NEOSSat Data Viewer. This Flask web application allows users to explore data about astronomical objects collected by NASA and the Canadian Space Agency. 

Cosmic objects such as stars, galaxies, and asteroids are displayed on a rotating JavaScript sky map developed by {{< standard-anchor link="https://github.com/zonia3000/SkySphere" content="Sonia Zorba" >}}. Users can click on an object they're interested in, and detailed information about it will be displayed below. This data is retrieved from XML files stored online. Users can also enter information about an object they're interested in and download a FITS image, which is done using the Astropy and PyVO Python libraries. 

We developed this application in around three days, and because it was our first time working with Flask and Astropy/PyVO, the experience was intense but very educational! I focused more on the frontend and XML data collection while Tom developed the image retrieval feature.

Please visit our GitHub repository for the project {{< standard-anchor link="https://github.com/GeorgeBerdovskiy/nasa-spaceapps-2020" content="here" >}} if you're interested!

{{< section-header kind="code" title="Technologies and Languages" >}}

This application was created using **Flask**, the lightweight Python web framework. We took advantage of the **Astropy** and **PyVO** libraries to collect and interact with astronomical data.


{{< section-header kind="desktop" title="Desktop Screenshots" >}}

{{< image-carousel path_name="spaceapps2020" kind="desktop" >}}


{{< section-header kind="video" title="Videos" >}}

{{< video-carousel link="https://www.youtube.com/embed/NC497kBiet4" >}}