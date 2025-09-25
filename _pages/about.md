---
layout: about
title: Overview
permalink: /
subtitle: 


selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

---

Although many LLM-based agents have recently been developed, progress on agents that are capable of solving complex, real-world problems is severely limited. One such important and challenging area is that of addressing IT management tasks, including solving IT incidents, which often require extensive human expertise and effort. To enable the development of agents for these tasks, in this lab, we introduce IT-Bench, an open benchmark for IT automation that simulates realistic environments where agents interact with IT systems and multi-modal operational data, including logs, metrics, alerts, and traces. 

ITBench provides a two-tiered benchmark: a static dataset (ITBench<sub>static</sub>) that closely mirrors the live, gym-like environment (ITBench<sub>live</sub>). Together, they provide a testbed for benchmarking agentic systems across a host of critical challenges, such as planning and reasoning over massive and heterogeneous IT data, safety, and stochasticity in live IT systems. Through demonstrations, participants will learn all of these challenges. 

ITBench<sub>static</sub> is more beginner-friendly, enabling rapid benchmarking of agents against a smaller set of unique IT-domain challenges. ITBench<sub>live</sub> enables more advanced researchers and practitioners familiar with IT systems to develop and test their agents against the full suite of challenging IT problems. 

We will guide attendees to use both ITBench<sub>static</sub> and ITBench<sub>live</sub> to develop baseline multi-agent systems and benchmark their performance. No prior IT or site reliability engineering (SRE) experience is required.
