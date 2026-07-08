Course Portfolio — ITAI 4370

Artificial Intelligence in 5G / 6G Communications & Open RAN

Student: Win Ko Aung
Course: ITAI 4370
Instructor: Tawanda Chiyangwa
Last updated: July 7, 2026


About this portfolio

This is a living record of what I did in ITAI 4370 and what I took away from it. The course started with the basics of how signals move through a network and ended with me putting machine-learning models inside the network and squeezing them down small enough to run on an edge device. Instead of collecting assignments into a pile, I've tried to organize this around the story of that progression — where I started, what I built, where I got stuck, and what changed in how I think about telecom.

Everything here is my own work from the semester. Every figure came from code I actually ran or from the logged output of a lab, not from placeholder numbers.


How this repository is organized

SectionWhat's insideReflectionsThree reflective essays: how my understanding of telecom evolved, how I applied AI to real telecom problems, and the skills I improved plus where I want to grow next.ProjectsFull documentation for every practical: problem statement, methods and tools, code, results, and my interpretation.AssessmentsThe graded artifacts — theory assignments, labs, the ethics assignment, and the case studies I worked through, with the outcome of each.Growth evidenceA module-by-module map of how I moved from basic telecom concepts to advanced AI applications, with concrete before/after evidence.assets/The figures embedded throughout, generated from my own lab runs.


Selected works (quick tour)

A few artifacts that best show the range of what I did this semester:


RF propagation model — a Free-Space Path Loss simulation I wrote and plotted from the log-distance equation.
Show Image
AI-driven 5G slice allocation — a resource allocator splitting 500 units across URLLC, eMBB, and mMTC slices based on their traffic profiles.
Show Image
Network traffic prediction — a Random Forest that reached a test R² of 0.893, later extended into a full time-series study with ARIMA, Linear Regression, and an LSTM I built from scratch.
Show Image
Edge / model compression — pruning, INT8 quantization, and knowledge distillation on an IoT classifier, taking a 51 KB model down to under 5 KB.
Show Image


Diagrams, notes, and reading summaries live inside the projects and assessments sections.


The arc of the course, in one table

StageModulesWhat I was learningRepresentative artifactFoundations1–2Signals, analog vs digital, topologies, RF propagationTelecom fundamentals write-up; FSPL + Wireshark lab5G systems3–45G core, network slicing, MEC, the RAN5G core assignment; slice-allocation labIntelligence in the RAN5–6AI/ML for resource allocation, Open RAN, RIC, SONOpen RAN assignment; Random Forest traffic labApplied ML7Time-series forecasting, edge deployment, compressionLab 4 (ARIMA/LR/LSTM); Lab 5 (prune/quantize/distill)Frontier & responsibility10–13Digital twins, 6G AI-native networks, AI ethicsEthics assignment; 6G / DTN reading summaries

Full detail is in growth/progression.md.


Reflections at a glance


How my understanding of telecommunications evolved
Applying AI to telecommunications problems
Skills I improved and where I want to grow



This portfolio is maintained on a free, accessible platform and has been updated throughout the course.
