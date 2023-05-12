# travelens (Travels Through A Lens)

[Chris Tham](https://christham.net)'s travelogue web site. This [site](https://travelens.github.io) documents all the trips we have taken over the years, to various countries.

This site is currently under construction, as we load trips from the most recent all the way back to our first trip in the 1980s.

I started travelling in the 1980s, in high school, but did not go far because I did not have much money. After I started working in the late 1980s, I mainly travelled for work reasons. In those days, we were mainly trying to pay off our mortgage, so most of our trips were domestic. We started travelling overseas for fun in the late 1990s after paying off our mortgage, but then in the early 2000s we bought a new house so had to curtail our travel desires. Most of our travel overseas have been in the 2010s as we had more disposable income.</p>

The COVID19 worldwide pandemic in 2020 forced many people into lockdown, unable to leave their homes. I took the opportunity of load (or scan), edit and catalog all the photos of travels we have taken in the last 30 years.

I have decided to make all the content of this site, including photos, open source (MIT Licence) and hosted on Github Pages.

The website is written using [Astro](https://astro.build) and deployed as a static set of HTML5/CSS3/Javascript pages.

There is a master site repository [travelens.github.io](https://github.com/travelens/travelens.github.io) that contains the high level pages. The master site is also responsible for hosting all the metadata required for site-wide client-side search (using lunr.js), a sitemap and RSS feed. Each trip is stored as a separate repository under the travelens organisation and served separately in Github Pages. An npm package [astro-travelens](https://www.npmjs.com/package/astro-travelens) contains common Astro components shared by the master site and all the trip repositories. All repositories are public - if you wish to use any content from these repositories please honour the conditions of the MIT Licence.

Please join me in [exploring the trips we have taken](https://travelens.github.io).

- [travelens.github.io](https://travelens.github.io) ![deploy](https://github.com/travelens/travelens.github.io/actions/workflows/deploy.yml/badge.svg)
- [Tasmania 2023](https://travelens.github.io/tasmania-2023) ![deploy](https://github.com/travelens/tasmania-2023/actions/workflows/deploy.yml/badge.svg)
- [Muswellbrook 2022](https://travelens.github.io/muswellbrook-2022) ![deploy](https://github.com/travelens/muswellbrook-2022/actions/workflows/deploy.yml/badge.svg)
- [Hunter Valley 2022](https://travelens.github.io/hunter-valley-2022) ![deploy](https://github.com/travelens/hunter-valley-2022/actions/workflows/deploy.yml/badge.svg)
- [Cowra 2022](https://travelens.github.io/cowra-2022) ![deploy](https://github.com/travelens/cowra-2022/actions/workflows/deploy.yml/badge.svg)
- [YuleFest 2022](https://travelens.github.io/yulefest-2022) ![deploy](https://github.com/travelens/yulefest-2022/actions/workflows/deploy.yml/badge.svg)
- [Armidale 2022](https://travelens.github.io/armidale-2022) ![deploy](https://github.com/travelens/armidale-2022/actions/workflows/deploy.yml/badge.svg)
- [Tasmania 2018](https://travelens.github.io/tasmania-2018) ![deploy](https://github.com/travelens/tasmania-2018/actions/workflows/deploy.yml/badge.svg)
- [Japan 2018](https://travelens.github.io/japan-2018) ![deploy](https://github.com/travelens/japan-2018/actions/workflows/deploy.yml/badge.svg)
- [Singapore 2017](https://travelens.github.io/singapore-2017) ![deploy](https://github.com/travelens/singapore-2017/actions/workflows/deploy.yml/badge.svg)
- [Japan 2017](https://travelens.github.io/japan-2017) ![deploy](https://github.com/travelens/japan-2017/actions/workflows/deploy.yml/badge.svg)
