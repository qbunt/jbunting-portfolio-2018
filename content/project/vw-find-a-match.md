---
title: VW Find a Match
date: 2018-02-12 21:26:06 -0800
agency: Deutsch
draft: false

---
Volkswagen's 3.0 release of their website is a landmark achievement for Deutsch LA and the automotive industry. With a history of large, hard to use websites, entrenched technology, and slow moving clients, this site signals a sea-change in how agencies build large corporate sites.

Envoy LA engineered a brand new, end to end system with partners worldwide to surface VW vehicles in a brand new light. With vehicle specific artwork, specifications and beautiful renders, this site shows Volkswagen vehicles in a way that made the entire auto industry pay attention. This site garnered major attention from [Fast Company](http://www.fastcocreate.com/3030032/the-new-vwcom-takes-a-page-from-online-dating-to-help-you-find-a-car) and [Digiday](http://digiday.com/brands/vw-new-site/). The site has been a huge success and has triggered an industry-wide refocus on digital efforts far beyond Volkswagen.

On the technical side, the site was built with a large, enterprise CMS, using Backbone applications for single page applications across the site. I functioned as technical lead for the Find A Match component and lead a team-wide refactoring effort. The refactor focused on improving performance, stability and setting the team up for long-term success as the site scaled over time. I also engineered a shared data controller to manage the inventory data across all front-end components in the site in an organized way. The front-end uses an event aggregator pattern to share data and signal events across many standalone, decoupled components.

This site has won multiple awards, including a [Bronze Pencil in the 2015 One Show](http://www.oneclub.org/#olmag=/_ajax/archive/?action=arc_work%26value=23022%26rndm=817).

The code I wrote for these components is in production use today.
