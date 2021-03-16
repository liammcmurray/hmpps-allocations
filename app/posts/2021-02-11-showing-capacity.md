---
title: Showing capacity
description: The purpose of this first sprint was to look at ways we can provide an overview of a PP's capacity.
date: 2021-02-11
---

The purpose of this first sprint was to look at ways we can provide an overview of a PP's capacity.

- Points don't mean anything
- Case mix is important for allocation
- 

More text here about each screen below. I guess.

{% from "screenshots/macro.njk" import appScreenshots with context %}

{{ appScreenshots({
  items: [{
      text: "Team view",
      img: { src: "screenshot-localhost_3000-2021.02.11-10_11_50.png" }
    }, {
      text: "Probation Officer view",
      img: { src: "screenshot-localhost_3000-2021.02.11-10_12_32.png" }
    }, {
      text: "Probation Service Officer view",
      img: { src: "screenshot-localhost_3000-2021.02.11-10_13_18.png" }
    }, {
      text: "Active cases view",
      img: { src: "screenshot-localhost_3000-2021.02.11-10_14_03.png" }
    }]
}) }}
