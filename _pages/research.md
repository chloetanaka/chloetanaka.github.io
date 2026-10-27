---
layout: page
permalink: /research/
title: Research
nav: true
nav_order: 1
description:
---

<style>
  details.abstract { margin: 0.4rem 0 1.4rem; }
  details.abstract > summary {
    cursor: pointer;
    font-weight: 600;
    color: var(--global-theme-color);
    list-style: none;               /* hide default marker (Firefox) */
    display: inline-flex;
    align-items: center;
    gap: 0.4rem;
    user-select: none;
  }
  details.abstract > summary::-webkit-details-marker { display: none; }  /* hide default marker (Safari/Chrome) */
  details.abstract > summary::before {
    content: "\25B8";              /* ▸ arrow */
    transition: transform 0.15s ease;
  }
  details.abstract[open] > summary::before { transform: rotate(90deg); }  /* points down when open */
  details.abstract p { margin-top: 0.5rem; text-align: justify; }

  .post-header { display: none; }   /* hide the "Research" page heading (it stays in the nav bar) */
  h2 { margin-top: 2.25rem; margin-bottom: 1.5rem; }   /* space between sections (top) + header-to-title (bottom) */
  p strong { font-weight: 900; }  /* bolder paper titles (Roboto Black) */
</style>

## Job Market Paper

**[Powering the Workforce: The Role of Community Colleges in Energy Transformations]({{ '/assets/pdf/Tanaka_JMP.pdf' | relative_url }}){:target="_blank" rel="noopener noreferrer"}**

<details class="abstract">
  <summary>Abstract</summary>
  <p>Energy transformations change the skills demanded by local employers, but does training adapt alongside? I study how U.S. community college programs and graduates respond to energy-induced shifts in local labor demand. I focus on two energy transformations, the shale oil and gas boom and the ongoing expansion of solar power. In both, resource endowments determine the location, while advances in technology and policy determine the timing. Shale-exposed colleges expand energy programs by 30% and graduates by 117%, primarily through new program creation, while non-energy fields have 10% fewer programs and 31% fewer graduates, consistent with rising opportunity cost. Taken at face value, this response produced roughly 5,500 additional energy graduates in a decade, over one third of the estimated boom-induced increase in local middle-skill energy employment. The solar effect is smaller per new job created. Installing one gigawatt of local solar capacity raises solar programs by 10% and graduates by 21%. Yet, colleges nearly double solar sections in California course-level data, revealing a more flexible margin. Expansion appears to pay off. In individual-level records from Texas, energy graduates earn 14% more over ten years than observably similar peers in other technical programs. These findings demonstrate how energy transformations shape human capital formation through local training institutions.</p>
</details>

## Selected Works in Progress

**Blowin’ in the Wind: The Impact of Climate Disasters on College Majors and Innovation**<br>
(with [Avinash Moorthy](https://avi-moorthy.github.io/))

<details class="abstract">
  <summary>Abstract</summary>
  <p>Could extreme weather influence education and career choices? This project investigates how foundational experiences with extreme weather shape human capital formation and innovative activity. We study the causal impact of exposure to extreme weather on college major choices, and on the direction, quality, and intensity of inventors’ output, examining whether shifts in educational pathways serve as a mediating channel. We use NOAA records on natural disaster damages to determine the timing and location of exposure. We combine these records with administrative data on educational institutions, college student surveys, LinkedIn employment and education histories, and individual-level patent records. Comparing students and graduation cohorts exposed to major natural disasters with their unexposed counterparts, we find preliminary evidence that exposure shifts major choices toward green fields by 3-6 percent relative to baseline. Turning to inventors, we find modest effects on green innovation, with stronger responses to late exposure. Our research provides new evidence on how personal experiences shape career trajectories and the evolution of technical progress, advancing our understanding of the factors that shape the supply of skills required to address a changing environment.</p>
</details>

**The Effect of Coal Power Retirements on Labor Market Outcomes**<br>
(with [Gordon Hanson](https://gordonhanson.scholars.harvard.edu/))

<details class="abstract">
  <summary>Abstract</summary>
  <p>Nearly half of U.S. coal-fired generators operating in 2000 had retired by 2022, representing more than one third of coal capacity. As electricity production shifts elsewhere, do the industries and jobs that depend on it follow? We build a dataset of roughly 1,100 coal generators, linking EIA, EPA, and FERC records on plant characteristics and regulatory exposure. Using LASSO selection models, we identify size, age, and emissions as the key predictors of closure. Retirement is largely a plant-level decision and unfolds gradually over years of declining generation. Replacement of lost capacity is also incomplete. Between 2010 and 2022, plants that retired coal generators lost roughly 80% of their coal capacity and 40% of their total generating capacity. Total capacity in their counties fell nearly 15%, while generation expanded in non-coal counties, more than offsetting the losses. We evaluate the labor market consequences of this local contraction in generating capacity.</p>
</details>


## Publications

**[Short-run impacts of a severance tax change: Evidence from Alaska](https://www.sciencedirect.com/science/article/pii/S0301421517302975)**<br>
(with M. Reimer and M. Guettabi)<br>
*Energy Policy*, 2017.

<details class="abstract">
  <summary>Abstract</summary>
  <p>Energy states face a fundamental tradeoff when increasing severance tax rates: potential gains in tax revenues versus potential losses in exploration, development, and production activity. Despite the significant implications of this tradeoff, there is very little empirical evidence on the short-run responsiveness of extraction-related activities to changes in severance taxes. We conduct a comparative case study to evaluate the short-term impact of a severance tax increase on oil-related activities and development in Alaska. In 2007, the introduction of “Alaska's Clear and Equitable Share” (ACES) more than tripled the tax liability for much of the oil already under production in Alaska. We construct a synthetic Alaska from a set of U.S. energy states, with the purpose of estimating the counterfactual evolution of oil production, exploration and development wells, gross state product, and employment, in the absence of ACES. Overall, our results indicate that there is no discernible difference in the outcome variables of interest between Alaska and its synthetic control after the implementation of ACES, suggesting that ACES had a minimal effect on Alaskan oil-related activity and development in the short run.</p>
</details>
