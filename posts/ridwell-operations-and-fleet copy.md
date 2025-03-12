---
title: Ensuring a driver fleet provides exceptional service
description: My work directly contributed to an increase in service quality, operational efficiency, employee hapiness, and customer satisfaction. Average route completion time dropped 2% and fleet managers were better able to respond to unplanned changes throughout the day.
date: 2024-08-30
year: 2024
timeline: 6 months
client: Ridwell
skills: Interaction & interface design, UX research, Design system management, Creative workshop facilitation
role: Mobile UI Design, Responsive UI Design, Design Systems
tags:
layout: layouts/work.njk
---
<img
  class='post-img usual-bottom'
  src='../../img/ridwell/ridwell-ops-mocks.png'
  srcset=''
  alt='Figma screenshot of design work'
/>
<section class='usual-bottom'>
  <h5 class='hero-subheading'>First steps!</h5>
  <h2>Understand the Operations team’s needs and tear up the current design</h2>
  <p>The B2C Ridwell service is possible thanks to warehouse logistics and a fleet of drivers. For every pickup there is a driver who needs to be at dozens of stops on time, and there is a fleet manager handling on-the-fly changes and balancing the needs of customers, drivers, and the business. With a growing number of customers and drivers, old tools that had worked for fewer stops and a smaller team were breaking down in usefulness.</p>
  <ul>The Operations team had identified two impactful updates that would help them better meet customer needs:
      <li>Fleet managers needed to see multiple routes on a map, so they could better adjust to urgent needs</li>
      <li>and Drivers needed to be able to see nearby stops more easily, so they could prep and save time</li>
  </ul>
  <h4>Digging deeper than the initial request</h4>
  <p>I had video calls with fleet managers and drivers to better understand their workflows, avoid assumptions, and useful design potential. For instance, fleet managers sometimes send a nearby driver to help a driver in need; seeing multiple routes at once would enable them to help drivers in this way, among others. Knowing this, I considered highlighting the nearest driver on driver profiles.
  <h4>Tearing up the existing designs</h4>
  <p>Interviews helped me better observe and understand workflows. My own informal heuristic evaluation helped me identify impactful changes that no one else would ask for, like making input labels clickable and using words that make sense to users in their context more than engineers labeling data.</p>
  <img
    class='post-img'
    src='../../img/ridwell/img-ops-before.png'
    srcset=''
    alt='Figma screenshot of design work'
  />
  <img
    class='post-img'
    src='../../img/ridwell/img-driver-uxTeardown.png'
    srcset=''
    alt='Figma screenshot of design work'
  />
</section>
<section class='usual-bottom'>
  <h3>Considering design possibilities</h3>
  <p>Layout adjustments, new UI patterns, and workflow changes were in scope, but due to technical constraints we had to keep the page structure: a table listing the routes with a map below. One design challenge involved figuring out how to select and navigate between routes. The pre-existing design used both table rows and tabs to represent routes. The table rows showed route details, and you could click the tabs above the map to display that route on the map. This UI pattern was brittle, though, because with dozens of routes per driver, and route names that were often several lines long, tabs became very overcrowded. Since we were keeping the table, and it seemed a bit underused, I decided to use the table rows as the selection interface for the map instead of tabs. This worked well in prototype testing. It was a familiar pattern and afforded the Operations team more flexibility in naming the routes without worrying about tab label.</p>
  <img
    class='post-img'
    src='../../img/ridwell/img-ops-sketch.png'
    srcset=''
    alt='Figma screenshot of design work'
  />
  <img
    class='post-img'
    src='../../img/ridwell/img-ops-mockup.png'
    srcset=''
    alt='Figma screenshot of design work'
  />
</section>
<section class='usual-bottom'>
  <h3>Shipping it!</h3>
  <h4>Communicating the states and interactions</h4>
  <p>Yes, prototypes speak volumes, but sometimes it’s faster to communicate interaction logic with a bit of writing. It helps me think through my own decisions. And keep track of team decisions, too! Bulleted lists helped me keep track of interaction logic decisions as I paired with engineers.</p>
  <img
    class='post-img'
    src='../../img/ridwell/img-ops-interactionLogic.png'
    srcset=''
    alt='Figma screenshot of design work'
  />
  <h4>Compromises in visual language</h4>
  <p>My design work at Ridwell typically pushed UI patterns forward to an idealistic vision. Sometimes, we could launch the vision. With this work, we had to make compromises and reuse more existing UI than I had hoped since we weren’t in a good position to audit so many changes to the reused components across the back-of-house apps.</p>
  <img
    class='post-img'
    src='../../img/ridwell/img-driver-uiProgression.png'
    srcset=''
    alt='Figma screenshot of design work'
  />
  <p>Within these constraints, I identified improvements we could make like adjusting space and alignment of the routes table and identifying moments for consistency in font styles. In the mobile driver app, my advocacy to fix too-small touch targets helped drivers immensely, since they are often in a rush and wearing screen-friendly gloves.</p>
  <img
    class='post-img'
    src='../../img/ridwell/img-ops-launched.png'
    srcset=''
    alt='Figma screenshot of design work'
  />
</section>