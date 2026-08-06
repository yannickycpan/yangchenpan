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
    <p>
Yangchen Pan is an Assistant Professor in the Department of Data Science at City University of Hong Kong. Prior to joining CityU, he was a Lecturer (Teaching and Research) in Machine Learning in the Department of Engineering Science at the University of Oxford, where he was affiliated with the Torr Vision Group. While at Oxford, he was awarded the UK Engineering and Physical Sciences Research Council (EPSRC) New Investigator Award as the sole Principal Investigator (PI) and secured significant computational resources through UK Research and Innovation (UKRI). His research has been published in leading machine learning and artificial intelligence venues, including JMLR, JAIR, TMLR, ICML, NeurIPS, and ICLR. He actively serves the research community as an Area Chair or (Senior) Program Committee member for those top conferences and journals. He was recognized as a top reviewer at NeurIPS and AISTATS. Before Oxford, he received his PhD in Computer Science from the University of Alberta, conducting research under the supervision of Prof. Martha White (co-supervisor: Prof. Amir Massoud Farahmand) within the Reinforcement Learning and Artificial Intelligence (RLAI) lab. His doctoral research focused on developing sample-efficient reinforcement learning algorithms. He also gained industry experience in Canada and the United States. 
    </p>
    <p>Email: yangchen.pan AT cityu DOT edu DOT hk</p>
  </div>
</div>

## Research Interests

His research interests broadly span machine learning. Some of the research directions he is currently exploring include the following.

1. World models and model-based RL. He is interested in developing physically-plausible models that capture dynamics of real-world environments, with the goal of improving both the sample and computational efficiency of RL agents. 

2. Fundamental problems in RL. While not necessarily theoretical in nature, these problems often require rigorous empirical design and evaluation. 

3. The connections between RL and other areas of AI. This includes using the RL perspective to better understand supervised and unsupervised learning (e.g. generative models), as well as investigating how RL can contribute to LLMs.

4. More broadly: problems involving generalization under distribution shift, non-i.i.d. data, and changing environments. These challenges arise across a wide range of applications, and his work seeks to develop methods that remain robust under such conditions. 

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

.profile-photo {
  width: 100%;
  height: auto;
  display: block;
}

.bio-content {
  flex: 1;
}

@media (max-width: 700px) {
  .intro-wrap {
    flex-direction: column;
  }

  .photo-placeholder {
    width: min(100%, 280px);
    min-width: 0;
    margin: 0 auto;
  }
}
</style>
