---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Research Associate in the [Safe AI Lab](https://safeai-lab.github.io/#team) at Carnegie Mellon University, working with [Prof. Ding Zhao](https://www.meche.engineering.cmu.edu/directory/bios/zhao-ding.html). I serve as the Associate Director of the [ETAIC (Embodied Technology for Autonomy, Intelligence, and Control)](https://etaic.github.io/) Lab at the University of Texas at Arlington, working with [Prof. Eric Tseng](https://www.nae.edu/248787/Dr-Hongtei-E-Tseng), a member of the [National Academy of Engineering](https://www.nae.edu/). Prior to this, I worked as a Research Fellow at Tsinghua University and a Visiting Researcher at University College of London. I received my Ph.D. from School of Vehicle and Mobility at Tsinghua University, co-advised by [Prof. Zhi Wang](https://www.svm.tsinghua.edu.cn/essay/74/1854.html) and [Prof. Shengbo Eben Li](https://www.svm.tsinghua.edu.cn/essay/80/2123.html).

I was the recipient of the Outstanding Doctoral Dissertation Award, the Outstanding Ph.D. Graduate, and the “Shuimu Scholar” Fellowship at [Tsinghua University](https://www.tsinghua.edu.cn/en/). My doctoral research on ADAS and EMS contributed to the industry deployment of reinforcement learning since 2019, significantly improving safety, energy efficiency, and driving comfort of connected and automated vehicles. Notably, the control systems I developed have been implemented in leading automotive companies such as [BYD Auto](https://www.byd.com/us), [Dongfeng Motor](https://www.dongfeng-global.com/), [SAIC Motor](https://www.saicmotor.com/english/index.shtml), and start-up automotive companies such as [Hybot](http://www.hybot.com.cn/). 

I have authored over 50 peer-reviewed SCI journal and conference papers. I serve as Guest Editor for several journals and as Associate Editor on the International Program Committee of several conferences including IEEE ITSC, IEEE IV, etc. My current research focuses on multi-agent reinforcement learning theory, the integration of vison-language-models with closed-loop control, and human–robot collaboration using game theory. I aim to advance human-centric trustworthy AI agents for real-world deployment in autonomous systems.

Open to casual collaborations if interests align, and open to bringing in RA/Volunteers to work with me at Safe AI Lab and ETAIC Lab.


# 💻 Research Interests

- Embodied AI theory: Reinforcement learning, Optimal control, VLM with closed-loop control, and game theory
- Robotics: Safety-critical decision-making and control of assistive and mobile robots
- Intelligent vehicles: Human-centric AI for ADAS and EMS to improve safety, efficiency, and comfort

<!-- <div style="width: 100%; margin-bottom: 30px; margin-top: 20px;">
  <div style="display: flex; justify-content: space-between; gap: 2%;">
    
    <div style="width: 23.5%; display: flex; flex-direction: column; align-items: center;">
      <img src="images/demo1.GIF" alt="Demo 1" style="width: 100%; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
      <div style="text-align: center; color: #666; font-size: 0.85em; margin-top: 8px; line-height: 1.2;">
        Multi-Agent Safe Decision Making
      </div>
    </div>

    <div style="width: 23.5%; display: flex; flex-direction: column; align-items: center;">
      <img src="images/demo3.GIF" alt="Demo 3" style="width: 100%; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
      <div style="text-align: center; color: #666; font-size: 0.85em; margin-top: 8px; line-height: 1.2;">
        Contact-Rich Loco-Manipulation
      </div>
    </div>

    <div style="width: 23.5%; display: flex; flex-direction: column; align-items: center;">
      <img src="images/demo2.GIF" alt="Demo 2" style="width: 100%; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
      <div style="text-align: center; color: #666; font-size: 0.85em; margin-top: 8px; line-height: 1.2;">
        Trustworthy AI Partner
      </div>
    </div>

    <div style="width: 23.5%; display: flex; flex-direction: column; align-items: center;">
      <img src="images/demo4.GIF" alt="Demo 4" style="width: 100%; object-fit: cover; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);">
      <div style="text-align: center; color: #666; font-size: 0.85em; margin-top: 8px; line-height: 1.2;">
        Intelligent Vehicle and Digital Twin
      </div>
    </div>

  </div>
</div> -->


<div style="width: 100%; margin: 20px 0 30px;">
  <div style="
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      column-gap: 32px;
      row-gap: 30px;
  ">

    <!-- Demo 1 -->
    <div style="width: 30.5%; display: flex; flex-direction: column; align-items: center;">
      <img src="images/demo1.GIF" alt="Demo 1"
           style="width:95%; object-fit:cover; border-radius:8px;
                  box-shadow:0 4px 6px rgba(0,0,0,0.1);">
      <div style="text-align:center; color:#666; font-size:0.85em; margin-top:10px; line-height:1.3;">
        Multi-Agent Safe Decision Making
      </div>
    </div>

    <!-- Demo 3 -->
    <div style="width: 30.5%; display: flex; flex-direction: column; align-items: center;">
      <img src="images/demo3.GIF" alt="Demo 3"
           style="width:95%; object-fit:cover; border-radius:8px;
                  box-shadow:0 4px 6px rgba(0,0,0,0.1);">
      <div style="text-align:center; color:#666; font-size:0.85em; margin-top:10px; line-height:1.3;">
        Contact-Rich Loco-Manipulation
      </div>
    </div>

    <!-- Demo 2 -->
    <div style="width: 30.5%; display: flex; flex-direction: column; align-items: center;">
      <img src="images/demo2.GIF" alt="Demo 2"
           style="width:95%; object-fit:cover; border-radius:8px;
                  box-shadow:0 4px 6px rgba(0,0,0,0.1);">
      <div style="text-align:center; color:#666; font-size:0.85em; margin-top:10px; line-height:1.3;">
        Trustworthy AI Partner
      </div>
    </div>

    <!-- Demo 4 -->
    <div style="width: 30.5%; display: flex; flex-direction: column; align-items: center;">
      <img src="images/demo4.GIF" alt="Demo 4"
           style="width:95%; object-fit:cover; border-radius:8px;
                  box-shadow:0 4px 6px rgba(0,0,0,0.1);">
      <div style="text-align:center; color:#666; font-size:0.85em; margin-top:10px; line-height:1.3;">
        Intelligent Vehicles and Digital Twins
      </div>
    </div>

    <!-- Demo 6 -->
    <div style="width: 30.5%; display: flex; flex-direction: column; align-items: center;">
      <img src="images/demo6.GIF" alt="Demo 6"
           style="width:95%; object-fit:cover; border-radius:8px;
                  box-shadow:0 4px 6px rgba(0,0,0,0.1);">
      <div style="text-align:center; color:#666; font-size:0.85em; margin-top:10px; line-height:1.3;">
        Agile Sports Robotics
      </div>
    </div>

    <!-- Demo 5 -->
    <div style="width: 30.5%; display: flex; flex-direction: column; align-items: center;">
      <img src="images/demo5.GIF" alt="Demo 5"
           style="width:95%; object-fit:cover; border-radius:8px;
                  box-shadow:0 4px 6px rgba(0,0,0,0.1);">
      <div style="text-align:center; color:#666; font-size:0.85em; margin-top:10px; line-height:1.3;">
        Game-Theoretic Decision Making
      </div>
    </div>

  </div>
</div>

# 🔥 News
- *2026.06*: Our paper [IO-WBC: Interaction-Orientated Whole-Body Control for Compliant Object Transport](http://arxiv.org/abs/2603.03751) was accepted at IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2026.
- *2026.06*: Our paper [Learning Versatile Humanoid Manipulation with Touch Dreaming](https://arxiv.org/abs/2604.13015) was accepted at IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2026.
- *2026.04*:&nbsp;🎉 Our paper [Learning Human-Robot Collaboration via Heterogeneous-Agent Lyapunov Policy Optimization](http://arxiv.org/abs/2603.03741) was accepted and selected for an **Oral Presentation (top 0.7%)** at International Conference on Machine Learning (ICML) 2026.
- *2026.01*: I serve as an Associate Editor for the upcoming IEEE International Conference on Intelligent Transportation Systems (ITSC 2026). I warmly welcome you to submit your papers to this exciting venue.
- *2025.10*: Our paper [Multi-Scale Reinforcement Learning of Dynamic Energy Controller for Connected Electrified Vehicles](https://ieeexplore.ieee.org/document/11215998) was published in IEEE Transactions on Intelligent Transportation Systems.
- *2025.10*: I serve as an Associate Editor for the upcoming IEEE Intelligent Vehicles Symposium (IV 2026). I warmly welcome you to submit your papers to this exciting venue.
- *2025.06*: Our paper [Bi-Level Transfer Learning for Lifelong-Intelligent Energy Management of Electric Vehicles](https://ieeexplore.ieee.org/document/11034670) was published in IEEE Transactions on Intelligent Transportation Systems.
- *2025.06*:&nbsp;🎉 I joined the Safe AI Lab as a **Research Associate** at CMU in the U.S.
- *2025.01*: Our paper [Theory-Constrained Neural Network with Modular Interpretability for Fuel Cell Vehicle Modelling](https://ieeexplore.ieee.org/document/10852019) was published in IEEE Transactions on Vehicular Technology.
- *2024.11*:&nbsp;🎉 I am an incoming **Associate Director** of ETAIC Lab led by Prof. Eric Tseng (NAE Member) at UTA in the U.S.
- *2024.08*: I delivered a plenary talk at 2024 China SAE Annual Conference on Advanced Powertrains (APC), titled “Data-Driven Modeling of Electric Powertrains and Reinforcement Learning-Based Optimal Control”, held in Zhenjiang, China.
- *2024.06*:&nbsp;🎉 I received Outstanding Doctoral Dissertation Award, the Outstanding Ph.D. Graduate, and the “Shuimu Scholar” Fellowship from Tsinghua University.
- *2024.06*: Our paper [Integrated Thermal and Energy Management of Connected Hybrid Electric Vehicles Using Deep Reinforcement Learning](https://ieeexplore.ieee.org/document/10233107) was published in IEEE Transactions on Transportation Electrification.

# 💬 Media

<style>
.media-talk-card {
  display: flex;
  align-items: stretch;
  gap: 27px;
  box-sizing: border-box;
  width: 98%;
  margin: 17px 0 24px;
  padding: 0;
  overflow: hidden;
  border: 1px solid rgba(127, 127, 127, 0.20);
  border-radius: 9px;
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.08);
}

.media-talk-visual {
  flex: 0 0 62%;
  display: flex;
  align-items: center;
  overflow: hidden;
}

.media-talk-visual img {
  display: block;
  width: 100%;
  height: 100%;
  margin: 0;
  object-fit: cover;
}

.media-talk-content {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: center;
  min-width: 0;
  padding: 23px 30px 23px 0;
}

.media-talk-label {
  display: block;
  margin-bottom: 8px;
  font-size: 0.72em;
  font-weight: 700;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  opacity: 0.58;
}

.media-talk-content h3 {
  margin: 0 0 12px;
  font-size: 1.25em;
  line-height: 1.28;
}

.media-talk-content p {
  margin: 0 0 18px;
  font-size: 0.92em;
  line-height: 1.52;
}

.media-talk-link {
  display: inline-block;
  align-self: flex-start;
  font-weight: 700;
  text-decoration: none;
}

.media-talk-link:hover {
  text-decoration: underline;
}

@media (max-width: 700px) {
  .media-talk-card {
    width: 100%;
    margin: 18px 0 24px;
    flex-direction: column;
    gap: 0;
  }

  .media-talk-visual {
    flex-basis: auto;
    width: 100%;
  }

  .media-talk-visual img {
    height: auto;
  }

  .media-talk-content {
    padding: 22px 24px 25px;
  }

  .media-talk-content h3 {
    font-size: 1.25em;
  }

  .media-talk-content p {
    font-size: 0.96em;
  }
}
</style>

<div class="media-talk-card">
  <div class="media-talk-visual">
    <img
      src="images/ICML_talk.gif"
      alt="Hao Zhang delivering an academic talk"
    >
  </div>

  <div class="media-talk-content">
    <span class="media-talk-label">Trustworthy Embodied Intelligence</span>

    <h3>Academic Talk</h3>

    <p>
      Research at the intersection of learning, control, and robotics
      for safe and capable intelligent systems in the physical world.
    </p>

    <a
      class="media-talk-link"
      href="https://icml.cc/virtual/2026/session/68647"
      target="_blank"
      rel="noopener noreferrer"
    >
      Watch Video&nbsp;→
    </a>
  </div>
</div>

# Recent Talks

- *2026.07*, Oral Presentation, International Conference on Machine Learning (ICML) 2026, "HALO: Learning Human-Robot Collaboration via Heterogeneous-Agent Lyapunov Policy Optimization", Seoul, South Korea
- *2024.08*, Plenary Talk, APC 2024: Joint Annual Conference on Advanced Powertrains - China SAE, "Data-Driven Modeling of Electric Powertrains and Reinforcement Learning-Based Optimal Control", China SAE, Zhenjiang, China



# 📝 Featured Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML (Oral)</div><img src='images/HALYPO.gif' alt="sym" width="92%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning Human-Robot Collaboration via Heterogeneous-Agent Lyapunov Policy Optimization](http://arxiv.org/abs/2603.03741)


**Hao Zhang**, Yaru Niu, Yikai Wang, Ding Zhao, H. Eric Tseng
<br>*ICML 2026 <span style="color:red;"><strong>Oral Presentation (top 0.7%)</strong></span>*

[**Project Webpage**](https://haozhang-thu.github.io/HALO/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We propose heterogeneous-agent Lyapunov policy optimization (HALO), which establishes formal stability directly in the policy-parameter space by enforcing a per-step Lyapunov decrease condition on a parameter-space disagreement metric.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Preprint</div><img src='images/IROSHARL.gif' alt="sym" width="92%"></div></div>
<div class='paper-box-text' markdown="1">

[C2C: A Cognition-to-Control Hierarchy for Human-Robot Collaboration via Multi-Agent Learning](http://arxiv.org/abs/2603.03768)

**Hao Zhang**, Ding Zhao, H. Eric Tseng
<br>*Under review*

[**Project Webpage**](https://haozhang-thu.github.io/HALyPO/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In multi-agent human-robot collaboration, where long-horizon coordination decisions and physical execution must co-evolve under contact, feasibility, and safety constraints. We address this limitation with cognition-to-control (C2C), a three-layer hierarchy that makes the deliberation-to-control pathway explicit.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE/RSJ IROS</div><img src='images/IROSHTD.gif' alt="sym" width="92%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning Versatile Humanoid Manipulation with Touch Dreaming](https://arxiv.org/abs/2604.13015)

Yaru Niu, Zhenlong Fang, Binghong Chen, Shuai Zhou, Revanth Senthilkumaran, **Hao Zhang**, Bingqing Chen, Chen Qiu, Eric H. Tseng, Jonathan Francis, Ding Zhao 
<br>*IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2026*

[**Project Webpage**](https://haozhang-thu.github.io/HALyPO/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We develop a VR-based whole-body data collection system and propose Humanoid Transformer with Touch Dreaming (HTD), a multimodal Transformer that jointly models vision, proprioception, and touch, achieving a 90.9% relative improvement in average success rate across five real-world tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE/RSJ IROS</div><img src='images/IROSWBC.gif' alt="sym" width="92%"></div></div>
<div class='paper-box-text' markdown="1">

[IO-WBC: Interaction-Orientated Whole-Body Control for Compliant Object Transport](http://arxiv.org/abs/2603.03751)

**Hao Zhang**, Yves Tseng, Ding Zhao, H. Eric Tseng
<br>*IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2026*

[**Project Webpage**](https://haozhang-thu.github.io/HALyPO/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We proposed a bio-inspired, interaction-oriented whole-body control (IO-WBC) that functions as an artificial cerebellum - an adaptive motor agent that translates upstream (skill-level) commands into stable, physically consistent whole-body behavior under contact.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS</div><img src='images/IEEE_TITS_2025_multi.gif' alt="sym" width="92%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-Scale Reinforcement Learning of Dynamic Energy Controller for Connected Electrified Vehicles](https://www.techrxiv.org/users/692350/articles/1184096-multi-scale-reinforcement-learning-of-dynamic-energy-controller-for-connected-electrified-vehicles?commit=cd309bc80017f735b83292e39179ef3815d2cbe2)

**Hao Zhang**, Nuo Lei, Shengbo Eben Li, Junzhi Zhang, Zhi Wang
<br>*In IEEE Transactions on Intelligent Transportation Systems*

- We proposed a multi-horizon reinforcement learning (MHRL) featuring a novel state representation and coordinated training of sub-networks across multiple time scales, which greatly improves fuel economy in real-world driving.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS</div><img src='images/IEEE_TITS_2025_500x300.gif' alt="sym" width="92%"></div></div>
<div class='paper-box-text' markdown="1">

[Bi-Level Transfer Learning for Lifelong-Intelligent Energy Management of Electric Vehicles](https://ieeexplore.ieee.org/document/11034670)

**Hao Zhang**, Nuo Lei, Wang Peng, Bingbing Li, Shujun Lv, Boli Chen, Zhi Wang
<br>*In IEEE Transactions on Intelligent Transportation Systems*

[**Industrial Collaborator: BYD Auto**](https://www.byd.com/us) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We proposed a bi-level transfer approach with MAML to realize cross-platform transferable and online-adaptive EMS for REEVs. It contributed to the successful industry deployment of RL methods, implemented in leading automotive company - BYD Auto, significantly enhancing the REEV efficiency. 
</div>
</div>



<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Energy</div><img src='images/EGY_RL_ECMS_500x300.gif' alt="sym" width="92%"></div></div>
<div class='paper-box-text' markdown="1">

[Modeling and control system optimization for electrified vehicles: A data-driven approach](https://www.sciencedirect.com/science/article/pii/S0360544224029712?via%3Dihub)

**Hao Zhang**, Nuo Lei, Boli Chen, Bingbing Li, Rulong Li, Zhi Wang
<br>*In Energy*

[**Industrial Collaborator: Dongfeng Motor**](https://www.dongfeng-global.com/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper develops a high-fidelity PHEV model integrating physical and data-driven approaches, and proposes a real-vehicle control framework that combines horizon-extended reinforcement learning with ECMS to improve practical energy management.
</div>
</div> -->



<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TVT</div><img src='images/IEEE_TVT_TCNN_500x300.gif' alt="sym" width="92%"></div></div>
<div class='paper-box-text' markdown="1">

[Theory-Constrained Neural Network with Modular Interpretability for Fuel Cell Vehicle Modelling](https://ieeexplore.ieee.org/document/10852019)

Nuo Lei, **Hao Zhang*** (Corresponding Author), Hong Wang, Zunyan Hu, Hu Chen, Jingjing Hu, Zhi Wang
<br>*In IEEE Transactions on Vehicular Technology*

[**Industrial Collaborator: Hybot**](http://www.hybot.com.cn/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We proposed a theory-constrained neural network (TCNN) that integrates physical principles without sacrificing accuracy. A theory-guided filter ensures sub-module interpretability, and sub-networks are individually trained under theoretical constraints with a CNN-BiLSTM-MHSA architecture enhances overall accuracy. Results demonstrate significant improvements in fitting accuragy for fuel cell modeling.
</div>
</div> -->





# Preprints
- **Zhang H**, Ding Zhao, H. Eric Tseng. C2C: A Cognition-to-Control Hierarchy for Human-Robot Collaboration via Multi-Agent Learning. arXiv, 2026, under review.
- **Zhang H**, H. Eric Tseng. Intention-Aware Adversarial MARL for AV Stress Testing. arXiv, 2025, under review.
- Xinyi Zhao, Nuo Lei, et al., **Zhang H*** (Corresponding Author). Adversarial experience replay in embodied multi-agent learning for efficient coordination of wheel-legged mobile robots. Engineering Applications of Artificial Intelligence, 2025, under review.

# Selected Papers
- **Zhang H**, Yves Tseng, Ding Zhao, H. Eric Tseng. IO-WBC: Interaction-Orientated Whole-Body Control for Compliant Object Transport. IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2026.
- **Zhang H**, Yaru Niu, Yikai Wang, Ding Zhao, H. Eric Tseng. Learning Human-Robot Collaboration via Heterogeneous-Agent Lyapunov Policy Optimization. International Conference on Machine Learning (ICML) 2026. (**Oral**, top 0.7%)
- **Zhang H**, Lei N, Li E S, et al. Multi-scale reinforcement learning of dynamic energy controller for connected electrified vehicles. IEEE Transactions on Intelligent Transportation Systems, 2025,26:22607-22619. (IF: 9.1)
- Niu Y, Fang Z, Chen B, Zhou S, Senthilkumaran R, **Zhang H**, Chen B, Qiu C, Tseng E H, Francis J, Zhao D. Learning Versatile Humanoid Manipulation with Touch Dreaming. IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2026.
- **Zhang H**, Lei N, Chen B, et al. Bi-level transfer learning for lifelong intelligent energy management of electric vehicles. IEEE Transactions on Intelligent Transportation Systems, 2025,26:16174-16187. (IF: 9.1)
- Yang G, **Zhang H**, Qiu L. Graph-based multi-agent reinforcement learning with an enriched environment for joint ride-sharing and charging optimization. Applied Energy, 2025,405:127220. (IF: 12.2)
- **Zhang H**, Dong J, Lei N, et al. Optimal vehicle dynamics and powertrain control of carbon-free autonomous vehicles: Large Language Model Assisted Heterogeneous-Agent Learning. Energy, 2025,338:138786. (IF: 10.1)
- **Zhang H**, Yang G, Lei N, et al. Scenario-aware electric vehicle energy control with enhanced vehicle-to-grid capability: A multi-task reinforcement learning approach. Energy, 2025,138189. (IF: 10.1)
- **Zhang H**, Xu J, Lei N, et al. Surrogate-enhanced multi-objective optimization of on-board hydrogen production device for carbon-free heavy-duty vehicles. Energy, 2025,333:137369. (IF: 10.1)
- Lei N, **Zhang H**, Hu J, et al. Sim-to-real design and development of reinforcement learning-based energy management strategies for fuel cell electric vehicles. Applied Energy, 2025,393:126030. (**ESI highly cited paper**) (IF: 12.2)
- Lei N, **Zhang H*** (Corresponding Author), Wang H, et al. Theory-Constrained Neural Network with Modular Interpretability for Fuel Cell Vehicle Modelling. IEEE Trans. on Vehicular Technology, 2025, Early Access. (IF: 7.5)
- **Zhang H**, Lei N, Chen B, et al. Modeling and control system optimization for electrified vehicles: A data-driven approach. Energy, 2024,311:133196. (IF: 10.1)
- **Zhang H**, Chen B, Lei N, et al. Coupled velocity and energy management optimization of connected hybrid electric vehicles for maximum collective efficiency. Applied Energy, 2024,360:122792. (IF: 12.2)
- Li B, Zhuang W, **Zhang H**, et al. Traffic-aware ecological cruising control for connected electric vehicle. IEEE Trans. on Transportation Electrification. 2024,10:5225-5240. (IF: 8.5)
- **Zhang H**, Chen B, Lei N, et al. Integrated thermal and energy management of connected hybrid electric vehicles using deep reinforcement learning. IEEE Trans. on Transportation Electrification, 2024,10:4594-4603. (IF: 8.5)
- Lei N, **Zhang H**, and Wang Z. A comprehensive study of various carbon-free vehicle propulsion systems utilizing ammonia-hydrogen synergy fuel. eTransportation, 2024,20:100332. (IF: 18.7)
- **Zhang H**, Lei N, Wang Z. Ammonia-hydrogen propulsion system for carbon-free heavy-duty vehicles. Applied Energy, 2024,369:123505. (IF: 12.2)
- Sun H, Li B, **Zhang H**, et al. Ecological electric vehicle platooning: an adaptive tube-based distributed model predictive control approach. IEEE Trans. on Transportation Electrification, 2024,11:1048-1060. (IF: 8.5)
- Lei N, **Zhang H**, Li R, et al. Physics-informed data-driven modeling approach for commuting-oriented hybrid powertrain optimization. Energy Conversion and Management, 2024;299:117814. (IF: 11.8)
- **Zhang H**, Lei N, Chen B, et al. Data-driven predictive energy consumption minimization strategy for connected plug-in hybrid electric vehicles. Energy, 2023,283:128514. (IF: 10.1)
- Lei N, **Zhang H**, Wang H, et al. An improved co-optimization of component sizing and energy management for hybrid powertrains with high-fidelity model. IEEE Trans. on Vehicular Technology, 2023,72:15585-15596. (IF: 7.5)
- More publications can be found on my [Google Scholar homepage](https://scholar.google.com/citations?user=SCHOLAR_ID&user=qC9ScSkAAAAJ).

# Book Chapters
- Bin Shuai, **Hao Zhang** (Co-first Author), Min Hua, et al. Physics-Aware Machine Learning for Integrated Energy Systems Management. ELSEVIER.


# 🎖 Honors and Awards
- *2026* Oral Presentation at International Conference on Machine Learning
- *2026* Gold Reviewer for International Conference on Machine Learning
- *2024* Plenary Talk at 2024 China SAE Annual Conference on Advanced Powertrains
- *2024* “Shuimu Tsinghua Scholar” Talents Program, Tsinghua University
- *2024* Outstanding Doctoral Dissertation Award, Tsinghua University
- *2024* Outstanding Ph.D. Graduate (top 4%), Tsinghua University
- *2023* Comprehensive Excellence Scholarship, Tsinghua University
- *2022* Comprehensive Excellence Scholarship, Tsinghua University
- *2021* Excellent Student Leader, Tsinghua University
- *2021* Comprehensive Excellence Scholarship, Tsinghua University
- *2020* Comprehensive Excellence Scholarship, Tsinghua University
- *2018* National Scholarship, Ministry of Education of China
- *2018* Best Paper Award in the 2018 IEEE ACES Conference in Denver, U.S.
- *2017* National Scholarship, Ministry of Education of China
- *2016* National Scholarship, Ministry of Education of China




# 📚 Service
# Reviewer
- **Associate Editor**: IEEE Intelligent Vehicles Symposium (IEEE IV), sponsored by The IEEE Intelligent Transportation Systems Society (ITSS), Ann Arbor, USA
- **Associate Editor**: The IEEE International Conference on Intelligent Transportation Systems (ITSC), sponsored by The IEEE Intelligent Transportation Systems Society (ITSS), Naples, Italy
- **Guest Editor**: Electronics, Special Issue: Eco-Safe Intelligent Mobility Development and Application
- **Journal Reviewer**: 1. IEEE Transactions on Intelligent Transportation Systems (IF: 9.1); 2. IEEE Transactions on Intelligent Vehicles (IF: 14.3); 3. IEEE Transactions on Transportation Electrification (IF: 8.5); 4. IEEE Transactions on Visualization and Computer Graphics (IF: 6.8); 5. IEEE Open Journal of Vehicular Technology (IF: 6.6); 6. Renewable and Sustainable Energy Reviews (IF: 18.0); 7. Applied Energy (IF: 12.2); 8. Energy (IF: 10.1); 9. Energy Conversion and Management (IF: 11.8); 10. Sustainable Energy, Grids and Networks (IF: 5.7); 11. Journal of Cleaner Production (IF: 10.7); 12. Journal of Energy Storage (IF: 10.7); 13. Engineering Applications of Artificial Intelligence (IF: 9.0); 14. Green Energy and Intelligent Transportation (IF: 21.5)
- **Conference Reviewer**: 1. International Conference on Machine Learning (ICML); 2. Annual Conference on Neural Information Processing Systems (NeurIPS); 3. AAAI Conference on Artificial Intelligence (AAAI); 4. IEEE Intelligent Vehicles Symposium (IV); 5. IEEE Intelligent Transportation Systems Conference (ITSC)


# Teaching
- Guest Lecturer (Designed and delivered 6 lectures), EE5329, Topics in Systems Engineering (Reinforcement Learning and Control), UT Arlington, Spring 2026
- Guest Lecturer (Project-based instruction), 80150183, Fundamentals of Automotive Powertrains, Tsinghua University, Fall 2023
- Teaching Assistant, 40150420, Student Research Training (SRT), Tsinghua University, Fall 2022
- Teaching Assistant, 80150042, Frontiers in Vehicle System Dynamics and Control, Tsinghua University, Fall 2021


# Mentorship
- Since 2024 (during Postdoc), have **independently provided mentorship** to postgraduate and undergraduate students (research assistants) from Tsinghua University, UC Berkeley, UPenn, UCL, NYU, Brown, HKU, Fudan University, and Zhejiang University. More than half of the mentees have published papers in top-tier conferences and journals, with me serving as the corresponding/last author on multiple projects. I am actively recruiting research assistants and students interested in embodied AI.
- Since 2020, assisted in the supervision of 5 Ph.D. students, 13 master's students; mentored over a dozen undergraduate students, their work received multiple honors including Tsinghua University and Beijing Outstanding Undergraduate Thesis Awards.
