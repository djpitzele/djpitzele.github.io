---
title: "Autonomous Audio Navigation"
collection: projects
type: "University of Maryland"
permalink: /projects/audio-nav-818v
venue: "CMSC818V - Machine Learning for Sensing and Perception"
date: 2025-12-02 # just for ordering
location: "College Mark, MD"
---

For the semester project of a graduate course I took, a partner and I completed a project involving autonomous robot navigation using only audio signals. The task was for a "blind" robot to navigate to a goal point that was constantly emitting audio signals using only a microphone array at its location. We aimed to show that the information encoded in audio waveforms could be sufficient for navigation of an unknown scene. We created a dataset of randomly generated "cave-like" environments and precomputed the audio responses on a grid within those caves. We also solved for the "best" move at any given position in the cave. We then conducted supervised training of a navigation agent using these cave environments and the precomputed audio responses. Our results can be viewed in the form of a <a href="{{ '/files/CMSC818V_Final_Project_Report.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">final project report</a>.