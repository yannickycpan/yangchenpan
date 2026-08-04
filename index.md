---
layout: page
title: Introduction
permalink: /
---

<div class="intro-wrap">
  <div class="photo-placeholder">Photo Placeholder<br/>(add your photo later)</div>
  <div class="bio-content">
    <h2>Bio</h2>
    <p>I am an Assistant Professor at the Department of Data Science, City University of Hong Kong. My research focuses on scalable and robust sequential and strategic decision-making, where decisions must generalize under evolving environments and constraints.</p>
    <p>Email: yangchen.pan AT cityu DOT edu DOT hk</p>
  </div>
</div>

## Research Interests

1. Computationally and sample-efficient reinforcement learning, especially through efficient planning with world models for physical systems with evolving dynamics.
2. Robustness under distribution shift across space and time, including continual learning.

## People

[Qizhen Ying](https://stephenying.github.io/) (2024–present, PhD, University of Oxford)

<style>
.intro-wrap {
  display: flex;
  align-items: flex-start;
  gap: 24px;
  margin-bottom: 16px;
}

.photo-placeholder {
  width: 180px;
  min-width: 180px;
  height: 220px;
  border: 2px dashed #bbb;
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #888;
  font-size: 0.95rem;
  text-align: center;
  padding: 8px;
  box-sizing: border-box;
}

.bio-content {
  flex: 1;
}

@media (max-width: 700px) {
  .intro-wrap {
    flex-direction: column;
  }

  .photo-placeholder {
    width: 100%;
    min-width: 0;
    height: 180px;
  }
}
</style>
