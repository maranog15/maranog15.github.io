---
title: Research
layout: page
nav: Research
permalink: /research/
lede: "How drought, climate extremes and biotic disturbances reshape the growth, mortality and long-term dynamics of temperate forests — and what models can honestly tell us about it."
description: "Research of Gina Marano — drought-induced tree mortality, dynamic vegetation models, silviculture and adaptation in temperate forests."
---

My research develops and uses dynamic forest models to assess the impacts of abiotic disturbances — mainly drought and climate extremes — and biotic disturbances — pests and management — on forest dynamics in temperate forests, with a particular emphasis on the stand scale. I am dedicated to dissecting the processes, signals and tipping points that ultimately lead to extreme impacts on forest structure and dynamics.

My scientific and practical reasoning is grounded in close-to-nature silvicultural principles and rooted in forest ecology. Models are powerful allies in this, but they are neither a dogma nor the absolute truth: they give us a glimpse of what forest ecosystems might experience under "what if" scenarios, and we owe the people who use those answers a careful account of the uncertainty attached to them.

## Drought-induced tree mortality

The core of my doctoral and current work is a parsimonious representation of drought-induced tree mortality, inspired by Manion's decline-disease theory. The framework separates three things that are usually collapsed into one:

- **predisposing stress** — the slow, cumulative loss of vitality over years or decades;
- **inciting stress** — the acute drought event that pushes a weakened tree over the edge;
- **contributing factors** — biotic agents such as bark beetles, and management, that finish the process.

Implemented in the forest gap model ForClim, this framework has been tested against recent mortality patterns of European beech, Norway spruce and Scots pine in Switzerland and Germany. I am now transferring it to the process-based [3D-CMCC-FEM](https://www.forest-modelling-lab.com/the-3d-cmcc-model), where long-term predisposition can be linked directly to non-structural carbohydrate dynamics rather than relying on slow growth as a proxy for declining vitality. A key open question is how chronic carbon limitation interacts with acute drought stress and hydraulic constraints.

## Dynamic vegetation models

I work across the spectrum from empirical to fully process-based models, which I find far more informative than defending one school against another.

<div class="cards">
  <div class="card">
    <h3>ForClim v4.1–4.2</h3>
    <p>Stand-scale forest gap model. Main developer of versions 4.1 and 4.2, extending its
    sensitivity to climate extremes. Open source, C# and Python. Ongoing applications with ETH
    Zurich, the University of Auckland and Universidad Santiago de Chile.</p>
  </div>
  <div class="card">
    <h3>MASSIMO</h3>
    <p>Empirical, stochastic, individual-tree simulator behind the Swiss National Forest
    Inventory. I am enhancing its climate sensitivity through a climate meta-model and
    hybridising it with process-based approaches. Java.</p>
  </div>
  <div class="card">
    <h3>3D-CMCC-FEM</h3>
    <p>Process-based forest ecosystem model. Contributor since 2018 as external research
    associate at the CNR Forest Modelling Lab. Currently implementing a carbon-aware mortality
    formulation in C.</p>
  </div>
  <div class="card">
    <h3>Forest Studio</h3>
    <p>Forest growth and management model developed at the ETH Zurich Forest Resources
    Management professorship, where I provide scientific support. Rust.</p>
  </div>
</div>

## Silviculture, adaptation and decision support

I am deeply interested in designing silvicultural scenarios that stay close to actual forest practice, and in using dynamic forest models to test whether adaptation to future climatic conditions is feasible at all. That includes species-choice guidance under climate change, the protective function of mountain forests, and the interaction between stand structure, age diversity and resilience.

The other half of this is delivery. Foresters carry the ambitious — and often dangerous — job of shaping today's forest for a future they will not see, frequently with very limited tools for complex and conflicting decisions. I particularly enjoy working with practitioners on decision support that is genuinely usable, from geospatial systems such as [LANDSUPPORT](https://www.landsupport.eu/) to the model-based products of the Swiss National Forest Inventory.

> Once my silviculture professor, Dr. Mario Pividori, gave a definition that has stayed with me: rather than the craft of chopping trees, silviculture is the art of allowing the forest to properly grow. This is how I picture forest management each time I step into a stand, asking the fundamental questions — who are you, what were you, where are you going?

## Current projects

<div class="cv-block">
  <div class="entry">
    <div class="entry__when">2025 — 2028</div>
    <div class="entry__what">
      <p class="entry__title">ReForMASSIMO</p>
      <p class="entry__where">WSL &middot; funded by the Federal Office for the Environment (BAFU)</p>
      <p class="entry__note">Improving the modelling of Swiss forest development under relevant
      climate scenarios with the MASSIMO model. Project supervisors: Dr. Golo Stadelmann,
      Dr. Esther Thürig. Scientific officers: Dr. Nele Rogier, Dr. Andreas Schellenberger.</p>
    </div>
  </div>
  <div class="entry">
    <div class="entry__when">2018 — ongoing</div>
    <div class="entry__what">
      <p class="entry__title">Drought mortality in 3D-CMCC-FEM</p>
      <p class="entry__where">CNR Forest Modelling Lab, Italy</p>
      <p class="entry__note">Reformulating and implementing the mortality equations, parameterising
      and initialising the model, and evaluating simulations for beech- and spruce-dominated
      stands, with crown-defoliation data from ICP Forests and possible extensions to Scots pine,
      oak and drought-mediated bark beetle risk.</p>
    </div>
  </div>
</div>

## Networks

I am a core member of the [International Tree Mortality Network](https://www.tree-mortality.net/people/), where I bring expertise on dynamic vegetation forest models. I also serve as scientific advisor to the British Ecological Society [Forest Ecology Group](https://forest640.wixsite.com/bes-forest/committee), and as communication officer of the Modelling Working Group of [SISEF](https://sisef.org/).

**[Publications →]({{ '/publications/' | relative_url }})**

<figure class="band">
  <img src="{{ '/assets/images/iufro3.jpg' | relative_url }}" alt="Presenting at the IUFRO World Congress">
</figure>
