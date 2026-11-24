---
layout: academic
title: "Research"
description: "Yanming Chen’s research in environmental health, biomedical image analysis, and applied machine learning."
permalink: /experiences/
author_profile: false
---

# Research

## Mapping PFAS in U.S. rivers and lakes

<p class="entry-meta">Yale University · M.S. capstone with <a href="https://medicine.yale.edu/profile/kei-cheung/">Kei-Hoi Cheung</a> · Fall 2026–present</p>

I’m developing a mapping approach to help field teams decide where to sample next. The pilot combines PFOS and PFOA measurements from 773 sampling visits in New York, Pennsylvania, and Virginia with watershed characteristics and Sentinel-2 imagery. On drainage basins held out during training, watershed data alone identified elevated river PFOS and PFOA with 84.1% and 80.2% balanced accuracy, respectively.

I presented this work at GIS Day at Yale in November 2026. A next question is whether these maps can help researchers trace potential exposure from upstream sources to drinking-water intakes.

## Medical image analysis

<p class="entry-meta">University of Nottingham Ningbo China · Computer Vision and Intelligent Perception Lab, with Xiangjian He · May 2023–July 2025</p>

- **[MambaVesselNet](https://doi.org/10.1145/3696409.3700231):** I designed a model that combines convolutions with a Mamba state-space model to trace small blood vessels in 3D MR angiograms. It reached 87.0% Dice on 15 held-out IXI angiograms.
- **[MambaVesselNet++](https://doi.org/10.1145/3757324):** We extended the architecture to tasks ranging from 3D vessel segmentation to 2D cell nuclei segmentation. Across four external datasets, it improved on the strongest baseline by 1.2–3.6 Dice percentage points.
- **[Retinal biomarker detection](https://doi.org/10.1117/12.3019655):** I investigated how to use clinical measurements to guide training of an OCT classifier when expert annotations are scarce. Detection improved for all six biomarkers on the OLIVES test set.

## Reinforcement learning for rescue drone planning

<p class="entry-meta">University of Nottingham Ningbo China · Research assistant with Saeid Pourroostaei Ardakani · July 2022–October 2025</p>

We developed a Q-learning planner that helps a rescue drone prioritize high-risk locations while avoiding collisions and retaining enough battery to return. In [three simulated fire scenarios](https://doi.org/10.1109/TSUSC.2026.3678502), the planner reached more rescue locations and took a higher share of collision-free flight steps than the baselines.

## Software engineering internship

<p class="entry-meta">University of Nottingham Ningbo China · Smart Medicine Lab, with Vladimir Brusic · May–August 2023</p>

I led a team that built an Android app for older adults to view readings from home blood pressure monitors and weighing scales. The project resulted in two registered software copyrights and a [poster presentation]({{ '/files/SMPoster.pdf' | relative_url }}).
