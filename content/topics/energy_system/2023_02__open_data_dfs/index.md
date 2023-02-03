---
title: "The case for (open) data in our future energy system 📈"
slug: data_for_the_future_energy_system
date: 2023-02-01
tags: ["Energy System"]
draft: false
---

> This blog is supported by a [web app that shows the impact of National Grid ESO's new Demand Flexibility Service](https://ryanjenkinson-consumerflex-dfs.streamlit.app). The code is [open-source on Github](https://www.github.com/RyanJenkinson/consumer-flex-app).

Note: This article is geared towards the GB energy system. Other energy systems may differ!

# The scale of the challenge ahead

Our energy system needs to change. As we increasingly electrify our homes and industry, we will be placing our energy infrastructure under demand it hasn't previously seen before. It still operates based on an old premise: when consumers (households and businesses) increase their energy demand, we increase supply to match it.

This way of thinking made sense when we used lots of coal power plants. We could easily "dispatch" this generation (i.e - turn it on) to meet demands, usually a few hours ahead. Household demand was also fairly predictable: there was a slight uptick in the morning, which dipped during the day while people were at work (on weekdays), before peaking again in the evening when everyone cooked dinner.

As we integrate more renewables into the generation mix, we have the unbelievable advantage of low-cost, green electrons. Increasing renewable generation and decarbonising our power system is a critical pillar to reaching net zero, and credit to the GB energy system for rapidly integrating renewable generation into our grid. However, we introduce more _variability_ (e.g the amount of wind and sun changes throughout the day, and throughout the year). We need to be able to:

* Better forecast the generation potential from wind and solar assets, and maximise the amount of time we can absorb these cheap, green electrons.
* Have adequate storage for times where we have too much supply to ensure we can capture these renewable electrons for use later.

With more households adopting low-carbon technologies (like solar, batteries, electric vehicles and electric heating systems) the old methodology would conclude there is a problem. We will increase our demand from households in a potentially unpredictable way. But what if these households (both with, and without, low carbon technologies) were actually part of the solution? Instead of changing supply to meet demand, we _change demand to meet supply_.

# The Demand Flexibility Service (DFS)

The Demand Flexibility Service (DFS) was a new service introduced by National Grid Electricity System Operator (ESO) in Winter 22/23. It enabled _providers of flexibility_ (think: energy suppliers, but could also be businesses that operate assets like a chargepoint) to _bid in_ their forecasts for the amount of energy they can reduce in a given time window. This time window was determined by ESO day-ahead.

## Putting consumers at the heart of the energy transition

The DFS was so important because consumers were _rewarded_ for providing this change in energy. Instead of paying for expensive coal and gas to turn up, we can instead pay consumers to turn down. This mindset shift is key to enabling the  future energy system. While right now consumers are generally taking manual actions (for example: shifting the time they cook dinner to one hour later), in the future this _same principle will become more automated_. In response to signals from the grid, appliances in the home will charge intelligently, at the greenest times. And customers will be paid to say thank you.

These payments might be small most of the time, only rising to large payments when the grid really needs it. But in the same way that consumers love yellow stickers in supermarkets - save pennies, but also reduce the amount of wasted food - consumers can now save pennies to be actively involved in the maximisation of renewable energy onto our energy system. In the words of a large supermarket chain: every little helps.

# Why we need data

Data drives better decision making. Open data makes it possible for everyone to look at the same records, and build tools geared towards specific use cases. Open grid data can ensure:

* Efficient planning and streamlined processes for building out grid infrastructure
* Sharing of learnings while we iterate on new products, services and ideas
* More informed policymaking

If we modernise our grid physically, shouldn't we also modernise how the information flows digitally? In the same way Open Banking transformed finance, we can transform the grid into one that embraces renewables and operates more effectively. Data portals, like the one built for the flexibility service, can be used to build dashboards. For example, I used the [ESO open data portal](https://data.nationalgrideso.com/dfs) to build [an application to visualise the impact of the Demand Flexibility Service (DFS)](https://ryanjenkinson-consumerflex-dfs.streamlit.app). Using this, we can learn how the DFS is going so far, and dig into the specifics from particular events. This could inform how we design future services that put consumers at the heart of the energy system.

# Conclusion

The Demand Flexibility Service has transformed how we think about and engage with energy. Consumers can now be active participants in the energy system, and by interacting with it they can maximise the renewables we use on our grid, and reduce system costs for everyone. It's also a more fundamental mindset shift: we have proven that consumers, and industry, embrace the concept of _shifting demand to meet supply_ - thereby helping us to operate the grid more intelligently.

This marks the first step towards a more intelligent energy system. And I'm pretty excited for the opportunities this creates.
