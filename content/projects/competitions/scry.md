---
title: "Scry"
tags: ["ReactJS"]
aliases:
- /scry.html
---

{{< banner path="/images/detail/ScryBanner.png" >}}

{{< section-header kind="description" title="Description" >}}

For DeveloperWeek 2021, I worked with my friends Shuzheng (Tom) Zhang and Jake Roggenbuck to build Scry, a web application that allows users to quickly view important information about their server (such as open ports, logins, and storage).

Scry includes a local server and client application. The server gathers data about the monitored server, and the client presents that data in an appealing, easy-to-read format. The server runs commands in the background to collect system information and stores it in a MongoDB database. The client is a ReactJS application that displays stored data in the user’s web browser. I was responsible for creating the client while Jake built the backend, and Tom contributed to both.

Please visit our GitHub repository for the project {{< standard-anchor link="https://github.com/JakeRoggenbuck/Scry" content="here" >}} if you're interested!


{{< section-header kind="code" title="Technologies and Languages" >}}

The frontend was built using **ReactJS** while the backend was built using **FastAPI (Python)** and **MongoDB**.



{{< section-header kind="desktop" title="Desktop Screenshots" >}}

{{< image-carousel path_name="scry" kind="desktop" >}}


{{< section-header kind="video" title="Videos" >}}

{{< video-carousel link="https://www.youtube.com/embed/D87Blido5tQ" >}}