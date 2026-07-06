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
 -
    fullname: Chris Adams
    organization: Green Web Foundation
    email: 
 -
    fullname: Michelle Thorne
    organization: Green Web Foundation
    email: michelle@thegreenwebfoundation.org

normative:

informative:
  Manojlovic:
    target: https://datatracker.ietf.org/meeting/interim-2022-eimpactws-01/materials/slides-interim-2022-eimpactws-01-sessa-05-social-00.pdf
    title: Internet Infrastructure and Climate Justice
    author:
      name: Vesna Manojlovic
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

  Hogan:
    target: https://ephemerajournal.org/sites/default/files/pdfs/contribution/18-3hogan.pdf
    title: Big Data Ecologies
    author:
      name: Mél Hogan
    date: 2018

  Akese:
    target: https://research.library.mun.ca/14273/
    title: "Electronic Waste (e-Waste) Science and Advocacy at Agbogbloshie: The Making and Effects of the World's Largest e-Waste Dump"
    author:
      name: Grace Abena Akese
    date: 2019

  Bender:
    target: https://dl.acm.org/doi/10.1145/3442188.3445922
    title: "On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?"
    author:
      name: Emily M. Bender
    date: 2021

  King:
    target: https://github.com/intarchboard/e-impact-workshop-public/blob/main/papers/King-Krishnan-Pignataro-Thubert-Voit_On-Principles-for-a-Sustainability-Stack.pdf
    title: On Principles for a Sustainability Stack
    author:
      -
        name: Michael King
      -
        name: Suresh Krishnan
      -
        name: Carlos Pignataro
      -
        name: Pascal Thubert
      -
        name: Eric Voit
    date: 2022

  Nordman:
    target: https://github.com/intarchboard/e-impact-workshop-public/blob/main/papers/Nordman_Applying-Internet-Architecture-to-Energy-Systems.pdf
    title: Applying Internet Architecture to Energy Systems
    author:
      name: Bruce Nordman
    date: 2022

  JansenCath:
    target: https://doi.org/10.5281/zenodo.11059837
    title: "Down with Data Centres: Developing Critical Policy"
    author:
      -
        name: Fieke Jansen
      -
        name: Corinne Cath
    date: 2024

  EcodesignServers:
    target: https://eur-lex.europa.eu/eli/reg/2019/424/oj
    title: "Commission Regulation (EU) 2019/424 Laying Down Ecodesign Requirements for Servers and Data Storage Products"
    author:
      org: European Commission
    date: 2019

  EED:
    target: https://eur-lex.europa.eu/eli/dir/2023/1791/oj
    title: "Directive (EU) 2023/1791 on Energy Efficiency (recast)"
    author:
      org: European Union
    date: 2023

--- abstract

The global internet is comprised of vast interconnected networks spanning nearly every surface of planet and sky that, together with user devices, consumes energy and emits greenhouse gases. The true scale and proposed mitigations of the carbon footprint of the internet are the subject of important research. The internet also requires the depletion of other natural resources beyond carbon, namely land, water, electromagnetic spectrum and minerals. Electronic waste contributes in particularly acute ways to environmental pollution. This document surveys the impacts of the internet on the environment and includes, but goes beyond, energy use and carbon footprint to look at the consumption of natural resources and environmental waste.

--- middle

# Introduction

Much research has been invested in understanding environmental impacts. Research such as the ‘UN Digital Economy Report: Shaping an environmentally sustainable and inclusive digital future’ examines the true scale and proposed mitigations of the carbon footprint of the internet [UN]. Related research by the World Health Organisation primer on the health impacts of e-Waste details the harms incurred when the majority of e-waste is processed [WHO].

This document originated in discussions at the 2022 IAB Workshop on Environmental Impact of Internet Applications and Systems [RFC9547].

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

Data centers themselves form a distinct land-use ecology, reshaping the geography, water tables, and energy grids of the regions that host them [Hogan].

Two broad approaches to data center governance have emerged. One is centered on market efficiency, intellectual property protection, and continued growth, often citing competitive advantages such as favorable climate or existing infrastructure. The other treats land, water, and energy as scarce resources rather than assuming their abundance, and argues for centring people and planet over profit and capital [JansenCath]. Product-level standards, such as the EU's ecodesign requirements for servers and data storage products, offer a standards-based lever that could help operationalize this latter approach in law, constraining resource use and waste regardless of ownership model [EcodesignServers].

### Water

Water is used to cool data centers and other internet infrastructure.

Water is also consumed in the extraction and processing of minerals used to build that infrastructure.

This limits the availability of water for other human, animal, and ecosystem needs [Manojlovic].

### Electromagnetic spectrum

Electromagnetic spectrum is a finite resource that continues to be allocated disproportionately to large companies and wealthier countries, despite ITU commitments to more equitable allocation.

### Minerals

Mineral extraction depletes finite resources.

Extraction requires significant water use.

It scars and degrades the Earth's crust.

It destroys habitats.

Extraction processes are toxic at the point of extraction.

This limits the availability of land for other uses.

## Waste

In the air -- pollution from fossil fuels, burning e-waste. 

On earth -- sanitation, landfills, polluting soil, limiting use of space, ecosystem disruption, as documented at e-waste processing sites such as Agbogbloshie, Ghana [Akese].

In the sea -- undersea cables, mineral extraction byproducts, e-waste shipping, pollution.

In space -- debris, crowding the sky scape, congestion, limit of use.

# Guiding Principles

As the practice of digital sustainability is still in development, we suggest the following principles to guide IETF’s approach to the topic, building on prior proposals for a sustainability stack for Internet architecture [King]. These principles are designed to be more enduring concepts that can inform solutions even as the technical specifics of those solutions evolve with the field.  

* Open and fair: Claims about environmental impacts must be publicly verifiable, such as linking to publicly available evidence and allowing third party auditing. Publicly verifiable evidence contributes to higher confidence in the measurements and facilitates independent monitoring and assessment as well as ensures fairer participation and competition, as in mandatory public reporting regimes such as the EU's data center sustainability indicators [EED].
* Timely: Where possible, move towards real-time information about impacts over an annual cadence or slower cadence. More timely data enables more responsiveness and a higher resolution of understanding, as called for in ongoing work on green networking metrics and management [I-D.cx-opsawg-green-metrics] [RFC9845].
* Within planetary boundaries: Treat the carrying capacity of the planet, as determined by the best available science, as a constraint to work within. There is a safe operating capacity of the planet, that when breached represents a critical risk to people and ecosystems we are part of, causing avoidable harm.
* Demand and supply can both be levers: Reducing demand for resources is also a valid and important approach in addition to providing supply more efficiently, including by applying Internet architecture principles to energy systems directly [Nordman].

# Conclusions

Key mitigations include reducing extraction, improving architectural efficiency to reduce cooling needs, and distributing resources more equitably. Data localisation choices also affect environmental impact. Backwards compatibility and protocol maintenance can serve as antidotes to premature hardware obsolescence, sometimes termed "Green IP". The rapid growth of computationally-intensive applications, such as large language models, is a significant new driver of this resource demand [Bender].

# Security Considerations

There are no security considerations for this document.

# IANA Considerations

This document has no IANA actions.

--- back

# Acknowledgments

TODO acknowledge.
