---
layout: page
title: Introduction
permalink: /
---

<div class="intro-wrap">
  <div class="photo-placeholder">
    <img src="{{ '/bio.png' | relative_url }}" alt="Yangchen Pan" class="profile-photo">
    </div>
  <div class="bio-content">
    <h2>Bio</h2>
    <p>
Yangchen Pan is an Assistant Professor in the Department of Data Science at City University of Hong Kong. Prior to joining CityU, he was a Lecturer (Teaching and Research) in Machine Learning in the Department of Engineering Science at the University of Oxford, where he was affiliated with the Torr Vision Group. While at Oxford, he was awarded the UK Engineering and Physical Sciences Research Council (EPSRC) New Investigator Award as a sole PI. His research has been published in leading machine learning and artificial intelligence venues, including JMLR, JAIR, TMLR, ICML, NeurIPS, and ICLR. He actively serves the research community as an Area Chair or (Senior) Program Committee member for those top conferences and journals. He received his PhD in Computer Science from the University of Alberta, conducting research under the supervision of Prof. Martha White (co-supervisor: Prof. Amir Massoud Farahmand) within the RLAI lab, which is led by Prof. Richard S. Sutton. His doctoral research focused on developing sample-efficient reinforcement learning algorithms. He also gained industry experience through positions in Canada and the United States. 
    </p>
    <p>Email: yangchen.pan AT cityu DOT edu DOT hk</p>
  </div>
</div>

## Research Interests

His research interests broadly span machine learning, reinforcement learning, representation learning, and deep learning, with a particular focus on developing data-efficient, computationally efficient, and generalizable learning algorithms. Some of the research directions he is currently exploring include the following.

World models and model-based RL. He is interested in developing predictive models that more accurately capture the structure and dynamics of real-world environments, including physical constraints, with the goal of improving both the sample efficiency and computational efficiency of RL systems.

Fundamental problems in RL. While not necessarily theoretical in nature, these problems require a good understanding of RL principles and rigorous empirical methodologies for the design and evaluation of new algorithms. 

The connections between RL and other areas of AI. This includes using the RL perspective to better understand supervised and unsupervised learning, such as supervised learning and generative modeling, as well as investigating how RL can contribute to LLMs.

More broadly: problems involving generalization under distribution shift, non-i.i.d. data, and changing environments. These challenges arise across a wide range of applications, and his work seeks to develop methods that remain robust, efficient, and adaptable under such conditions. 

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
