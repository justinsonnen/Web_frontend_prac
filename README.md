# DRIFTWOODPINES

* Author: JUSTIN SONNEN


## Overview
This project, Driftwoodpines.com, is a landing page for a mock outdoor recreation vacation home rental company.  
The purpose of this site was to gain experience with front end development tools and industry standard design principals.  

## Usage

Navigate to https://www.driftwoodpines.com

## Discussion

This project, Driftwoodpines.com, is a landing page for a mock outdoor recreation vacation home rental company.  
The purpose of this site was to gain experience with front end development tools and industry standard design principals.

The tools used to build this site are HTML and SCSS. For this project I used VScode and pushed my commits to github.  This site was then loaded onto HostGators Cpanel where it is being hosted.

My goal was to develop my UX/UI skills.  My focus was on using a popular color palette, design forward fonts, neomorphism design styles for text boxes, and an appropriate use of whitespace and many images.

Rather than develop design styles in CSS I opted for SCSS.  I found this to be much more organized, and the ability to nest sibling tags was easier to read and follow visually.  

Although being new at it, I tried to maintain a BEM (block, element, modifier) naming convention for my class names.

For code reusability I wrote mixins to manage my media queries.  I designed nine layouts for a variety of mobile, tablet, and desktop sizes, and included both portrait and landscape for devices that support both.

For units of measurement, I used rem so I would be able to automate adjusting all measurements at once by changing the font-size within the html block.  This sped up the process of making the site responsive.  

The current degree of completion is enough to satisfy my initial goal, however, there is a lot of updates I plan to make to this site in the future.  Currently, all animations are managed by SCSS.  This site does not have a navigation menu.  This is because I have not implemented any JavaScript, but plan to in the near future.  I would like to add a backend to this site, a database, and connect to an api. I would also like to add some logic that could provide a service or solve some problem.  These are all skills I plan to improve upon progressively. 

I did have one issue when making this site responsive, and that is, when I view this site on a mobile apple device it does not size/respond correctly.  When using the chrome developer tools to test all nine screen sizes my code renders perfectly.  I have added appropriate webkit prefixes and accounted for retina displays but have not yet discovered the fault.  This will take some time to debug.  In the future I plan to build mobile first, then increase progressively to desktop.  Front end development being new to me I was too far along before i learned of the benefits of mobile first.

I utilized many resources to learn how to build this site:


Udemy tutorials
Stackoverflow
favicon.cc
color hunt
daily UI
youtube
google fonts
