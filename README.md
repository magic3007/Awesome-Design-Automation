# Awesome Design Automation

![license](https://img.shields.io/github/license/magic3007/Awesome-Design-Automation) ![last commit](https://img.shields.io/github/last-commit/magic3007/Awesome-Design-Automation)

🤹‍♀️ Awesome - A curated list of amazing VLSI design automation papers, software and resources.

## Table of Contents

[TOC]

## Conference Papers

Papers of significance are marked in **bold**. My comments are marked in *italic*. Papers of other fields may also included, and we use the following tags to categorize different fields.

- ![#f03c15](README.assets/000000) Machine learning in EDA
- <img src="http://placehold.it/15/0abab5/000000?text=+" alt="#0abab5" /> FPGA
- <img src="http://placehold.it/15/01b312/000000?text=+" alt="#01b312" /> Global Routing
- <img src="http://placehold.it/15/f4f442/000000?text=+" alt="#f4f442" /> Detailed Routing

### 2020 DAC

- <img src="http://placehold.it/15/01b312/000000?text=+" alt="#01b312" /> CUGR: Detailed-Routability-Driven 3D Global Routing with Probabilistic Resource Model(Jinwei Liu, CUHK) [[code]](https://github.com/cuhk-eda/cu-gr)
### 2019 DAC

- **![#f03c15](README.assets/000000) DREAMPlace: Deep Learning Toolkit-Enabled GPU Acceleration for Modern VLSI Placement(Best Paper Award, *Yibo Lin*, PKU)** [[code]](https://github.com/limbo018/DREAMPlace)

### 2018 TODAES

- <img src="http://placehold.it/15/0abab5/000000?text=+" alt="#0abab5" /> UTPlaceF 2.0: A High-Performance Clock-Aware FPGA Placement Engine (1st-Place Award of ISPD 2017 Contest, *Wuxi Li*, UTA)

### 2017 ICCAD

- <img src="http://placehold.it/15/0abab5/000000?text=+" alt="#0abab5" /> UTPlaceF 3.0: A Parallelization Framework for Modern FPGA Global Placement(*Wuxi Li*, UTA)
  - *Rather than empirically making partitions on physics level, the paper leverages matrix-blocking technique on mathematics level*

### 2016 ICCAD

- <img src="http://placehold.it/15/0abab5/000000?text=+" alt="#0abab5" /> UTPlaceF: A Routability-Driven FPGA Placer with Physical and Congestion Aware Packing(*Wuxi Li*, UTA)
  - *A routability-driven FPGA packing and placement engine*
  - *Routing congestion level is indicated by cell area that may be inflated during FIP flow*

## How to Start Up Your Experiments?

To conduct a experiment, datasets, toolchains, hardware configuration, evaluation statistics, prior work  and its results should be taken into consideration. This collection is hosted on [*Google Sheet*](https://docs.google.com/spreadsheets/d/1Xtd4_ZrPQTgrsA7bieR5n3hLcjWxKuWoUsz-HyZn0do/edit?usp=sharing) for the convenience of editing. Also, some toolkits may help improve the quality of life! 🚀

### Toolkits

- [Limbo](https://github.com/limbo018/Limbo): Library for VLSI CAD Design Useful parsers and solvers' API.
- [rsyn-x](https://github.com/RsynTeam/rsyn-x): This framework integrates parsers for common academic and industrial formats as Bookshelf, LEF/DEF, Verilog, Liberty, SDC and SPEF. It provides support for benchmarks from several EDA contests (e.g ISPD, ICCAD).
- [Innovus®](https://www.cadence.com/content/cadence-www/global/en_US/home/tools/digital-design-and-signoff/soc-implementation-and-floorplanning/innovus-implementation-system.html): Design rule checking and evaluation.

## Important Issues

### Tutorials & Survey

- [EE 382V: VLSI Physical Design Automation](http://users.ece.utexas.edu/~dpan/EE382V_PDA/) (Prof. David Z. Pan, UT ECE) [[slides]](https://www.dropbox.com/sh/35ea7idub21022t/AACDG6tbubgGD9wK92VbLMGta?dl=0)
- An series of VLSI physical design courses(NPTEL, India) [[youtube]](https://www.youtube.com/channel/UCTSQnoUHhScO2ceUfqRHaKw/videos)
- [EE382V: Optimization Issues in VLSI CAD]() (Prof. David Z. Pan, UT ECE)

