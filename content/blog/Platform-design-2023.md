---
title: "Local Loop Merseyside platform design"
date: 2023-12-12T20:15:10+03:00
featureImage: images/Conceptual_merseyside_layersw5.png
draft: false
author: Tom Woodroof
tags:
- Tech
- Roadmap
- Mutual Credit Services
- Informal Systems
categories:
- Tech
- Roadmap
---

### High-level Service Overview

#### Catchment area

Mutual Credit Services is working to build a platform-based business network - Local Loop Merseyside - which will be the context for introducing a variety of Collaborative Finance mechanisms.

In addition to operating in Merseyside, we propose including an area of more rural character close to the city, in the hope of fostering local food trade connections.

{{< figure src="/images/MerseysideMap3.png" title="" class="img" >}}

The Local Loop platform will have three tiers: 'Base', 'Network', and 'Trade Credit Club'.

#### The Base tier - ON THE MAP

There is a significant quantity of public data available on businesses/organisations across the UK, and we intend to collect some of this to 'seed' the database.

{{< figure src="/images/MerseysideMap4.png" title="" class="img" >}}

We will publish a geo-spatial interactive map of this data, using the open-source [Murmurations](https://murmurations.network/) protocol, as in this example:

{{< figure src="/images/OTM_screenshot.jpeg" title="" class="img" >}}

This map will be the **Base tier**, consisting initially of public data. It will be free for organisations to get themselves 'On the Map' and share additional data through their profile. The Murmurations protocol is expressly designed to make it easy and simple for organisations to keep their information up-to-date. A limited subset of data from this tier may be visible via a public website/app landing screen.

In a diagrammatic form, the Base tier can be represented by a pale blue disc:

{{< figure src="/images/Conceptual_merseyside_layers-political.png" title="" class="img" >}}

where the organisation data will be placed, mostly consisting of individual organisations as unconnected data objects:

{{< figure src="/images/Conceptual_merseyside_layersw2.png" title="" class="img" >}}

#### The Network tier - IN THE LOOP

The main onboarding stage of our work - and the platform functionality that supports that phase - will be through a second, paid **Network tier** (represented in orange):

{{< figure src="/images/Conceptual_merseyside_layersw3.png" title="" class="img" >}}

This tier requires more active membership, i.e. getting 'In the Loop' by providing some number of claims as to local trade relationships, both buying and selling. As with many social networks, these claims will need to be accepted by the named businesses. The data provided by members will be used to create the key feature of this tier - the trade connections graph:

{{< figure src="/images/Conceptual_merseyside_layersw4.png" title="" class="img" >}}

It is expected that many Merseyside businesses will be excited by this as a networking tool, and so we will provide features such as a directory, enhanced profiles, business analysis tools, badges and the like (possible gamification: more data gets you 'points', and you can get enhancements with points), enabling us to grow membership of this tier effectively, especially if we co-design this with business networker-types. In Lancaster we were able to collect a significant amount of survey data on local trading relationships:

{{< figure src="/images/Local_Loop_obligation_graph.png" title="" class="img" >}}

Clearly, all sorts of conversations about the local economy become possible once these structures are made visible. It also sets the stage for us to apply some powerful network science techniques.

#### The Trade Credit Club tier - JOIN THE CLUB

Based on the density of their local connections, members of the Network tier may be invited to 'Join the Club' - get themselves into the **Trade Credit Club tier**.

This will allow members to access various Collaborative Finance tools as appropriate to their pattern of local trading.

{{< figure src="/images/Conceptual_merseyside_layersw5.png" title="" class="img" >}}

The simplest and most widely applicable of these will be multilateral offset - **Loop Clearing**:

{{< figure src="/images/Loop_figure.png" title="" class="img" >}}

This can be done without any need for handling payments, and we can expect to eliminate ~15% of members' debts on average, but this tool is somewhat constrained in terms of impact and flexibility.

**Fan Clearing**, which uses liquidity injections to overcome the limitations of Loop Clearing, will follow:

{{< figure src="/images/Fan_figure.png" title="" class="img" >}}

By targeting payments in the parts of the network where they will go the furthest, Fan Clearing achieves a significant multiplier effect on top of Loop Clearing. It will likely be delivered on the basis of a partnership with a payment services platform, who will provide a local payment method and 'virtual card'. This service may extend into the businesses in the Network tier, who may stand to benefit from Fan Clearing but not Loop Clearing.

In the future, MCS' Mutual Credit Clubs model will be developed to allow clusters of businesses with the highest levels of inter-trade to create endogenous liquidity.
