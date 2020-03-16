---
title: bus_hop
layout: default
---

<article class="projContainer" markdown="1">
<section markdown="1">
#bus_hop

An easy to use, quick to consume mobile transit app focused on upcoming bus arrivals. Bus_hop is made for commuters on the go.

I created the prototype from the ground up with the Bloc.io team following Material Design guidelines. Based on surveys, discussions, competitive analysis, and my knowledge from a decade of assisting transit riders, I crafted:
- Two sets of mockups [version 1](https://www.figma.com/file/yY9aQhuxDcGeErba71UB5U/BusyBus-prototype?node-id=3147%3A29724), [version 2](https://www.figma.com/file/yY9aQhuxDcGeErba71UB5U/BusyBus-prototype?node-id=3072%3A253)
- A responsive page highlighting the [main screen](https://ctavispost.github.io/busHop/) of version 1
- A [clickable prototype](https://www.figma.com/proto/yY9aQhuxDcGeErba71UB5U/BusyBus-prototype?node-id=3085%3A170&scaling=min-zoom) of version 2
</section>

<section class="smallestBreak" markdown="1">
<details aria-expanded="true/false" tabindex="0" role="button" class="smallerBreak screenOnly">
<summary>Role: UX research and design</summary>
<div>
Working with the Bloc.io design team, I researched user needs and competition to create a simple and direct solution that helped people find out when their bus was coming. I went on to create a clickable prototype in a different style with suggested branding.
</div>
</details>

<h3 class="speechOrPrintOnly">Role: UX research and design</h3> <!-- accessible version of above -->

Working with the Bloc.io design team, I researched user needs and competition to create a simple and direct solution that helped people find out when their bus was coming. I went on to create a clickable prototype in a different style with suggested branding.
{:.speechOrPrintOnly}

<details aria-expanded="true/false" tabindex="0" role="button" class="smallerBreak screenOnly">
<summary>Deliverables</summary>
<div>
competitive analysis, survey, user stories, sketches, wireframes, paper prototype, usability tests, mockups, responsive screen demo, clickable prototype, slide deck
</div>
</details>

<h3 class="speechOrPrintOnly">Deliverables</h3> <!-- accessible version of above -->

competitive analysis, survey, user stories, sketches, wireframes, paper prototype, usability tests, mockups, responsive screen demo, clickable prototype, slide deck
{:.speechOrPrintOnly}

<details aria-expanded="true/false" tabindex="0" role="button" class="smallerBreak screenOnly">
<summary>Tools</summary>
<div> <!-- to include brand logos? -->
Google Docs suite, Figma, pencil and paper, paper prototype, HTML5, CSS, Atom, GitHub
</div>
</details>

<h3 class="speechOrPrintOnly">Tools</h3> <!-- accessible version of above -->

Google Docs suite, Figma, pencil and paper, paper prototype, HTML5, CSS, Atom, GitHub
{:.speechOrPrintOnly}
</section>

<section markdown="1">
##Problem
{:.margBottZero}

(brief)[https://docs.google.com/document/d/12o20-S8OPshgl6bsCzl_cKxz7MoSiYrGIc1LjMBx194/edit?usp=sharing]

There are more buses serving the same stops causing confusion.

###Users

To avoid waiting or rushing pointlessly, people need to know:
- Which bus is next
- When their bus is coming

###Client

The city has data to share with riders, but needs information architecture and an app design focused on arrivals for one stop, Washington & State.
</section>

<section markdown="1">
##Solution

A three screen app with a:
- List of incoming buses showing destinations, arrival times, and alerts
- Map with stops
- Search feature, including basic trip planning
</section>

<section markdown="1">
##Questions for potential users
{:.margBottZero}
[survey](https://docs.google.com/forms/d/e/1FAIpQLScta3oU7pXSdqC31nyIDzshC71xTrdRr5biklxgS3jgwlzJYA/viewform?usp=sf_link)
[analysis](https://docs.google.com/document/d/1nlu3RdxrZhwP33wylIKgzW3MeOnFl1qYjl-vQGMwnXk/edit?usp=sharing)

I began with the assumption that a list of bus ETAs and basic route details would be integral to the solution. To begin to test this, I ran a survey:

<!-- insert some charts and graphs with CSS, time permitting -->
###17 respondents

Top priority in travel: quickness of trip (64.7%)

Regular transit app users most want to:
- Check when their bus arrives (57%)
- Plan trips (57%)

Almost two thirds of respondents considered quickness of travel important or very important. This was more than any other value tested, and was true across types of travel, including mass transit. Most people value their time. So, BusyBus is intended to save user’s time and not waste it.

Regular riders were evenly split between two online priorities: checking arrivals and planning trips. These are thus among the highest needs of veteran transit app users. To see how these needs are being met (or missed), I studied other transit apps.
</section>

<section markdown="1">
##Competitive Analysis
{:.margBottZero}
[SWOT doc](https://docs.google.com/document/d/1K5i6k84EbnenNiANtIi5NzmKHkEEtuYV_zIts4BwRDg/edit?usp=sharing)

After referencing 8 apps across platforms, I ran a Strengths, Weaknesses, Opportunites, and Threats analysis (SWOT) on Transit Stop and Moovit. Both apps focus on one thing they do well, but underperform in other, arguably necessary areas. My observations helped me home in on an MVP.

###TransitStop

TransitStop is made for repeat users. It has a comfortable map and runs everything from a single screen, but comes with a steep learning curve.

The app lacks a trip planner, can be difficult to navigate, and features sometimes overwhelming lists. My main takeaway was to keep in mind everyone starts as a first-time user.

###Moovit

Moovit begins at a helpful trip planner screen. This is its main emphasis and best point. Each step is clear, even when boxy design gets in the way, and it finishes with voiced trip guidance.

However, its lists of lines and maps are somewhat cluttered. These screens can feel cramped and hard to use. The lists, like in TransitStop, can seem endless. I decided to narrow results prior to showing lists whenever possible.
</section>

<section markdown="1">
##MVP
[user stories](https://docs.google.com/document/d/1ftVLoCqZ4QMU2RTPFkDTu74TQaqhDNa0m3xgfCiY_5k/edit?usp=sharing)

To gain a fuller picture of an MVP, I made user stories for new and returning users.

All users share certain key high priorities:
- Plan a trip
- Check arrivals/departures
- Search by destination

Based on our assumptions, survey, SWOT, and user stories, a transit app should:
- Be easy for first time users
- Have navigable, interactive map
- Include functional trip-planning
- Give relevant, readable bus stop and route info
- Keep lists short
</section>

<section markdown="1">
##Another direction

[prototype](https://www.figma.com/proto/yY9aQhuxDcGeErba71UB5U/BusyBus-prototype?node-id=3085%3A170&scaling=min-zoom)
{:.margBottZero}
[mockup](https://www.figma.com/file/yY9aQhuxDcGeErba71UB5U/BusyBus-prototype?node-id=3072%3A253)

If I were to do this now, I would push for:

- rebranded from a rushed sounding 'BusyBus' to a fun 'bus_hop'
- redesigned to let users quickly find information about their route's arrival
- simplified to be more direct and readable
</section>
</article>
