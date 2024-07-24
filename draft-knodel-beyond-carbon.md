---
title: "Impacts of the Internet on the Environment, Beyond Carbon"
abbrev: "Beyond Carbon"
category: info

docname: draft-knodel-beyond-carbon-latest
submissiontype: IAB
number:
date:
consensus: true
v: 3
area: AREA
workgroup: WG Working Group
keyword:
 - e-impact
venue:
  group:
  type: 
  mail: 
  arch: 
  github:
  latest: 

author:
 -
    fullname: Mallory Knodel
    organization: CDT
    email: mknodel@cdt.org

normative:

informative:
  Manojlovic:
    target: https://datatracker.ietf.org/meeting/interim-2022-eimpactws-01/materials/slides-interim-2022-eimpactws-01-sessa-05-social-00.pdf
    title: Internet Infrastructure and Climate Justice
    author: Vesna Manojlovic
    date: 2022

  UN:
    target: https://www.un-ilibrary.org/content/books/9789213589779.
    title: Digital Economy Report 2024.
    author:
      org: United Nations
    date: 2024

  WHO:
    target: https://www.who.int/news-room/fact-sheets/detail/electronic-waste-(e-waste).
    title: Electronic Waste (e-Waste)
    author:
      org: World Health Organization

  Jansen:
    target: https://doi.org/10.58704/dmnx-1r61
    title: The problem is growth
    author:
      name: Fieke Jansen
    date: 2023

  Richardson:
    target: https://www.science.org/doi/abs/10.1126/sciadv.adh2458
    title: Earth beyond six of nine planetary boundaries
    author:
      name: Katherine Richardson
    date: 2023

  IPBES:
    target: https://doi.org/10.5281/zenodo.3553579
    title: Summary for Policymakers of the Global Assessment Report on Biodiversity and Ecosystem Services
    author:
      org: IPBES
    date: 2019

  IPCC:
    target: https://www.ipcc.ch/report/ar6/syr/
    title: International Panel on Climate Change Synthesis Report 2023
    author:
      name: Calvin
    date: 2023

  Ferreira:
    target: https://doi.org/10.1029/2024GL109280
    title: Potential Ozone Depletion From Satellite Demise During Atmospheric Reentry in the Era of Mega-Constellations
    author:
      name: Ferreira, José P.
    date: 2024

  Oxfam:
    target: https://policy-practice.oxfam.org/resources/climate-equality-a-planet-for-the-99-621551/
    title: Climate Equality, A planet for the 99 percent 
    author:
      name: Ashfaq Khalfan
      org: Oxfam
    date: 2023

  Dutzik:
    target: https://publicinterestnetwork.org/wp-content/uploads/2024/06/We-Dont-Need-Deep-Sea-Mining-2024.pdf
    title: We Don’t Need Deep-Sea Mining
    author:
      name: Tony Dutzik
    date: 2024

--- abstract

The global internet is comprised of vast interconnected networks spanning nearly every surface of planet and sky that, together with user devices, consumes energy and emits greenhouse gases. The true scale and proposed mitigations of the carbon footprint of the internet are the subject of important research. The internet also requires the depletion of other natural resources beyond carbon, namely land, water, electromagnetic spectrum and minerals. Electronic waste contributes in particularly acute ways to environmental pollution. This document surveys the impacts of the internet on the environment and includes, but goes beyond, energy use and carbon footprint to look at the consumption of natural resources and environmental waste.

--- middle

# Introduction

Much research has been invested in understanding environmental impacts. Research such as the ‘UN Digital Economy Report: Shaping an environmentally sustainable and inclusive digital future’ examines the true scale and proposed mitigations of the carbon footprint of the internet [UN]. Related research by the World Health Organisation primer on the health impacts of e-Waste details the harms incurred when the majority of e-waste is processed [WHO].

This document aims to briefly categorize a complete survey of environmental impacts due to a global internet operating at scale. It is the expectation that these impacts are persistent and some will have few to no mitigations, even given a very long arc of innovation and scientific advancement. That is because each of these impacts are intimately tied to the physical limits of our planet, which are far more finite than our imaginations are capacious [Jansen].

It is, however, of utmost importance to confront and understand the planet's limitations and the ways in which internet growth pushes up against them.

A 'climate justice' approach to building internet architecture not only reduces the internet’s own environmental impact but reduces overall environmental impacts of our society. [Manojlovic]

This document summarizes the most promising mitigations in the context of internet networking. We further suggest a principled approach to guide understanding the problem space and taking measurable action. Our proposed approach aims for technical excellence, is informed by prior implementation and testing, documents clearly and concisely; and is open and fair in its assessments.

# The Internet's Environmental Impacts

This section is arranged in three sub-sections: 2.1. Carbon, 2.2. Natural Resources and 2.3. Waste. In the first section, of course carbon is a natural resource but in this document we rely on the vast research and documentation elsewhere to discuss the consumption of energy and its emissions in the form of greenhouse gas. Land, water, electromagnetic spectrum and minerals are all finite, non-renewable resources that are consumed by internet infrastructure and these impacts are explained in depth with citations. Lastly waste is discussed as its own very consequential impact on the pollution of the rest of the environment, living and nonliving.

## Carbon

Carbon footprint is a concept that takes into consideration emissions and global warming and the ozone layer. The projected impacts, and mitigations of global warming are extensively detailed in the Intergovernmental Panel on Climate Change’s sixth assessment [IPCC]. Progress on allowing the ozone layer to recover since the 1980s is at risk of being undone as a result of the deployment of low-earth orbit constellation satellites [Ferreira].

Energy consumption is the unequal distribution of and limitations on use of carbon energy for various purposes. The share of global carbon emissions is unevenly distributed across countries, but also within countries across income levels [Oxfam].

## Natural resources

Natural resources such as land, water, minerals and electromagnetic spectrum are all impacted by increased digitalisation and the growth of the internet. The Earth-system-science framework defining the nine “planetary boundaries” of Earth concludes that six of these have been transgressed, suggesting that Earth is now well outside of the safe operating space for humanity. [Richardson]

### Land

Internet infrastructure is often strategically placed geographically and geopolitically and impacts the finite space of the Earth’s crust and limits use of this land for other humans.

Animals and other ecosystems. The Intergovernmental Science-Policy Platform on Biodiversity and Ecosystem Services (IPBES) Global Assessment Report on Biodiversity and Ecosystem Services in 2019 provided a IPCC-like basis for policy and decision making, evaluating 15000 scientific publications, from 145 authors from 40 countries. It found 82% of wild mammal biomass had been lost in the last 50 years, and called for transformative changes to avoid further biodiversity loss. [IPBES]

Undersea internet cables and related infrastructure disrupt the sea bed. Furthermore untouched areas of the deep sea are being proposed for mining instead of reusing minerals already in circulation [Dutzik].

### Water

For cooling.

For mineral extraction.

Limits use for other humans but animals and other ecosystems, too [Manojlovic]

### Electromagnetic spectrum

Finite resource allocated to large companies and developed countries despite ITU pledge to allocate otherwise.

### Minerals

Extractive of finite resources which minerals.

Use of water.

Effects of scarring and degrading earth crust.

Destroying habitats.

Poisonous at the time of extraction.

Limited use for other things.

## Waste

In the air -- pollution from fossil fuels, burning e-waste. 

On earth -- sanitation, landfills, polluting soil, limiting use of space, ecosystem disruption.

In the sea -- undersea cables, mineral extraction byproducts, e-waste shipping, pollution.

In space -- debris, crowding the sky scape, congestion, limit of use.

# Guiding Principles

As the practice of digital sustainability is still in development, we suggest the following principles to guide IETF’s approach to the topic. These principles are designed to be more enduring concepts that can inform solutions even as the technical specifics of those solutions evolve with the field.  

* Open and fair: Claims about environmental impacts must be publicly verifiable, such as linking to publicly available evidence and allowing third party auditing. Publicly verifiable evidence contributes to higher confidence in the measurements and facilitates independent monitoring and assessment as well as ensures fairer participation and competition. 
* Timely: Where possible, move towards real-time information about impacts over an annual cadence or slower cadence. More timely data enables more responsiveness and a higher resolution of understanding.
* Within planetary boundaries: Treat the carrying capacity of the planet, as determined by the best available science, as a constraint to work within. There is a safe operating capacity of the planet, that when breached represents a critical risk to people and ecosystems we are part of, causing avoidable harm.
* Demand and supply can both be levers: Reducing demand for resources is also a valid and important approach in addition to providing supply more efficiently.

# Conclusions

Particular takeaways to mitigate effects: reduce extraction, efficiency in architecture to reduce cooling, more equitable resource distribution, data localisation impacts, backwards compatibility and protocol maintenance as antidotes to "Green IP".

# Security Considerations

There are no security considerations for this document.

# IANA Considerations

This document has no IANA actions.

--- back

# Acknowledgments

TODO acknowledge.
