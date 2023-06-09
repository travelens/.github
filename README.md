# travelens (Travels Through A Lens)

[Chris Tham](https://christham.net)'s travelogue web site. This site
documents all the trips we have taken over the years, to various
countries.

This site is currently under construction, as we load trips from the most recent all the way back to our first trip in the 1980s.

I started travelling in the 1980s, in high school, but did not go far because I did not have much money. After I started working in the late 1980s, I mainly travelled for work reasons. In those days, we were mainly trying to pay off our mortgage, so most of our trips were domestic. We started travelling overseas for fun in the late 1990s after paying off our mortgage, but then in the early 2000s we bought a new house so had to curtail our travel desires. Most of our travel overseas have been in the 2010s as we had more disposable income.</p>

The COVID19 worldwide pandemic in 2020 forced many people into lockdown, unable to leave their homes. I took the opportunity of load (or scan), edit and catalog all the photos of travels we have taken in the last 30 years.

I have decided to make all the content of this site, including photos, open source (MIT Licence) and hosted on Github Pages.

The website is written using [Astro](https://astro.build) and deployed as a static set of HTML5/CSS3/Javascript pages.

There is a master repository [travelens.github.io](https://github.com/travelens/travelens.github.io) that contains the high level pages. The master site is also responsible for hosting all the metadata required for site-wide client-side search (using lunr.js), a sitemap and RSS feed. Each trip is stored as a separate repository under the travelens organisation. An npm package [astro-travelens](https://www.npmjs.com/package/astro-travelens) contains common Astro components shared by the master site and all the trip repositories. All repositories are public - if you wish to use any content from these repositories please honour the conditions of the MIT licence.

Please join me in exploring the trips we have taken.
