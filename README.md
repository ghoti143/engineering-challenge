## Description

Thanks to your [Part 107 Commercial Drone Pilot's license](https://www.faa.gov/uas/), you've been hired by a local electrical company to inspect several of their power lines using aerial drone videography. To understand if you are legally allowed to fly in this area, you've requested data from the FAA to indicate what airspace, if any, near your flight is [controlled](https://www.faa.gov/uas/recreational_fliers/where_can_i_fly/airspace_101/) and thus not eligible for drone flights. The FAA returned you an array of coordinates in [geoJson](https://geojson.org/) representing a single polygon of controlled airspace. Your job is to create a web application that will allow you to sketch various possible flights to visualize and quantify which portions of your flight will be in controlled airspace, so you can adjust as necessary.

## Requirements

Your required tools are listed in the Tools section below. At its most basic, your app should load a map centered over the FAA polygon, which is also visible. The user should have the ability to draw shapes on the map, and after the sketch is complete, it will be visualized with a different color than the one used for the FAA shape. You should also be able to clearly visualize which portion of your flight area is NOT in controlled airspace (in other words, the area that doesn't intersect). Finally, display a message on the page indicating whether this flight area will be approved or not.

At Airspace Link, we feel strongly about good communication. Make sure to provide a `README.md` which explains your approach, both from a functional and code perspective. Pay attention to grammar; good writing will always win us over. The README should also give us instructions about how to get it up and running after the repo is cloned. You can also write up a list of great ideas you'd love to tackle on this app if you had infinite time to work on it.

The FAA polygon is included in this repo. Begin by forking the repo. When you are finished, send us a link to the completed project. If your repo is private, add `ddbradshaw`, `fieldsco`, and `jmburns` so we can review your work.

#### Extra credit ideas

- Output the area (in square meters or km) of controlled airspace that intersects your flight area
- Deploy your project to [Github Pages](https://pages.github.com/)
- Provide a layer control to toggle the visibility of your flight area and the FAA polygon
- <insert your awesome idea here!>

## Tools

We use [ReactJS](https://reactjs.org/) at Airspace Link, and we strongly prefer this challenge to follow suit. We also use [TypeScript](https://www.typescriptlang.org/) and would love to see that implemented as well. For the map and sketch tools, you can use [LeafletJS](https://leafletjs.com/) and [Leaflet Draw](http://leaflet.github.io/Leaflet.draw/docs/leaflet-draw-latest.html). For the geoprocessing, [TurfJS](https://turfjs.org/) is your best bet.

## Evaluation

If there has to be a tradeoff, we'd rather see clean, well-organized code and attention to detail over feature completeness. The point of this exercise is to give us insight into your style, creativity, and (I'll say at again) _attention to detail_. We're not a "code comments on every line" group of engineers, but they are welcome in sections you think might help a code reviewer better understand your logic.

You have the base requirements, but feel free to go above and beyond. This is your chance to truly show off your skills and creativity! Happy coding, and don't hesitate to reach out with any questions.
