---
title: "(ASDI) Plant Here!"
tags: ["Petite Vue", "AWS", "Python", "FastAPI"]
---

{{< banner path="/images/detail/ASDIBanner.png" >}}

{{< section-header kind="description" title="Description" >}}

For the Amazon Sustainability Data Initiative Global Hackathon (2022), I worked with UCD computer science undergraduates Jake Roggenbuck and Terry Tong to build Plant Here, a web application that allows users to determine the best locations to plant their crops (or what kind of crops to plant in their location) based on rainfall and soil data for that region.

The most challenging obstacle we encountered was collecting the datasets from their respective AWS S3 buckets, as the file sizes were very large! However, Jake and I developed a solution involving concurrency that downloaded these files, removed unnecessary data, and normalized that data in a short period of time.

For the frontend, I was very excited to use Petite Vue, a 6 kB subset of VueJS that can easily be embedded into vanilla JavaScript, HTML, and CSS webpages.

Please visit our GitHub repository for the project {{< standard-anchor link="https://github.com/TerryTong-Git/asdi-global-hackathon" content="here" >}} if you're interested!


{{< section-header kind="code" title="Technologies and Languages" >}}

The frontend was built using **Petite Vue**, **JavaScript**, and **HTML/CSS** while the backend was built using **FastAPI (Python)**. Rainfall data was downloaded and processed using **Pandas (Python)** and **AWS**.


{{< section-header kind="desktop" title="Desktop Screenshots" >}}

{{< image-carousel path_name="asdi" kind="desktop" >}}


{{< section-header kind="video" title="Videos" >}}

{{< video-carousel link="https://www.youtube.com/embed/UscTb9-_LgQ" >}}