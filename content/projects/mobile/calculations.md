---
title: "Vet Calculations"
tags: ["Swift"]
aliases:
- /calculations.html
---

{{< banner path="/images/detail/CalculationsBanner.png" >}}

{{< section-header kind="description" title="Description" >}}

Vet Calculations is an iOS application I built in collaboration with the Sacramento County Animal Shelter medical team to help them perform fluid and blood product calculations quickly and easily.

This application has separate sections for canine and feline records because dosage formulas differ between species. Each section is further divided into pages for fluid, blood transfusion, plasma for albumin deficit, and plasma records.

When creating new records, users enter important information about the animal (such as name, weight, and gender), which is then used by pre-programmed formulas to calculate dosages and rates. The application doesn't allow invalid input to prevent errors and return accurate results consistently. Users may save these records into a list to view, update, or delete later.

Vet Calculations has many other features that provide veterinarians and technicians with a smooth experience. For example, every record list has a search bar that allows users to search for their patients by name. The application also allows users to choose between kilograms or pounds when entering patient information, share their calculated results via email for record-keeping purposes, and add an image of the patient for easy identification.


{{< section-header kind="code" title="Technologies and Languages" >}}

This application was developed with **Swift**, uses a **storyboard UI**, and stores patient data locally with **Core Data**.


{{< section-header kind="mobile" title="Mobile Screenshots" >}}

{{< image-carousel path_name="calculations" kind="mobile" >}}


{{< section-header kind="video" title="Videos" >}}

{{< video-carousel link="https://www.youtube.com/embed/SpqQWa9nIw0" >}}