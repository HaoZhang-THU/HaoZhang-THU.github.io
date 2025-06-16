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

I am the Associate Director of the [ETAIC (Embodied Technology for Autonomy, Intelligence, and Control) Research Lab](https://etaic.github.io/) at the University of Texas at Arlington, working with [Prof. Eric Tseng](https://www.nae.edu/248787/Dr-Hongtei-E-Tseng), a member of the [National Academy of Engineering](https://www.nae.edu/). I am currently conducting postdoctoral research in the [Safe AI Lab](https://safeai-lab.github.io/) at Carnegie Mellon University, working with [Prof. Ding Zhao](https://www.meche.engineering.cmu.edu/directory/bios/zhao-ding.html). I received my Ph.D. from School of Vehicle and Mobility at Tsinghua University, co-advised by [Prof. Zhi Wang](https://www.svm.tsinghua.edu.cn/essay/74/1854.html) and [Prof. Shengbo Eben Li](https://www.svm.tsinghua.edu.cn/essay/80/1812.html).

I was the recipient of the Outstanding Ph.D. Graduate, the Outstanding Doctoral Dissertation Award, and the “Shuimu Scholar” talent program at [Tsinghua University](https://www.tsinghua.edu.cn/en/) in 2024. My doctoral research directly contributed to the successful industry deployment of reinforcement learning methods in developing advanced driver-assistance systems and energy management systems, significantly enhancing the operational efficiency of connected and automated vehicles. Notably, the control systems I developed have been implemented in leading automotive companies such as [BYD Auto](https://www.byd.com/us), [Dongfeng Motor](https://www.dongfeng-global.com/), [SAIC Motor](https://www.saicmotor.com/english/index.shtml), and start-up automotive companies such as [Hybot](http://www.hybot.com.cn/). 

I have authored over 30 peer-reviewed journal and conference papers and am a co-inventor on more than 20 patents. My current research focuses on multi-agent reinforcement learning theory, the integration of large language models with closed-loop control, and human–robot collaboration using game theory. I aim to advance AI agents for real-world deployment in autonomous systems (including robotics and vehicles) and distributed energy systems.


# 💻 Research Interests
- Embidied AI theory: Multi-agent reinforcement learning, LLM with closed-loop capability, and game theory
- Micro-mobility Device: Trustworthy AI methods for motion control of assistive and mobile robots
- Automotive/Energy: Generalized AI foundation model for ADAS, EMS, and V2G

# 🔥 News
- *2025.06*: Our paper [Bi-Level Transfer Learning for Lifelong-Intelligent Energy Management of Electric Vehicles](https://www.techrxiv.org/users/692350/articles/1233556-bi-level-transfer-learning-for-lifelong-intelligent-energy-management-of-electric-vehicles) was published in IEEE Transactions on Intelligent Transportation Systems.
- *2025.06*:&nbsp;🎉 I joined the Safe AI Lab as a Postdoctoral Researcher at CMU in the U.S.
- *2025.01*: Our paper [Theory-Constrained Neural Network with Modular Interpretability for Fuel Cell Vehicle Modelling](https://ieeexplore.ieee.org/document/10852019) was published in IEEE Transactions on Vehicular Technology.
- *2025.01*: Our paper [Ecological Electric Vehicle Platooning: An Adaptive Tube-Based Distributed Model Predictive Control Approach](https://ieeexplore.ieee.org/document/10530162) was published in IEEE Transactions on Transportation Electrification.
- *2024.11*: Our paper [Modeling and control system optimization for electrified vehicles: A data-driven approach](https://www.sciencedirect.com/science/article/pii/S0360544224029712?via%3Dihub) was published in Energy.
- *2024.11*:&nbsp;🎉 I am an incoming Research Associate in ETAIC Lab led by Prof. Eric Tseng (NAE Member) at UTA in the U.S.
- *2024.08*: I delivered a plenary talk at 2024 China SAE Annual Conference on Advanced Powertrains (APC), titled “Data-Driven Modeling of Electric Powertrains and Reinforcement Learning-Based Optimal Control”, held in Zhenjiang, China.
- *2024.06*:&nbsp;🎉 I was selected for the “Shuimu Scholar” talent program at Tsinghua University.
- *2024.06*:&nbsp;🎉 I received the Outstanding Ph.D. Graduate and the Excellent Doctoral Dissertation Award from Tsinghua University.
- *2024.06*: Our paper [Integrated Thermal and Energy Management of Connected Hybrid Electric Vehicles Using Deep Reinforcement Learning](https://ieeexplore.ieee.org/document/10233107) was published in IEEE Transactions on Transportation Electrification.


# 📝 Featured Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS</div><img src='images/IEEE_TITS_2025_multi.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multi-Scale Reinforcement Learning of Dynamic Energy Controller for Connected Electrified Vehicles](https://www.techrxiv.org/users/692350/articles/1184096-multi-scale-reinforcement-learning-of-dynamic-energy-controller-for-connected-electrified-vehicles?commit=cd309bc80017f735b83292e39179ef3815d2cbe2)

**Hao Zhang**, Nuo Lei, Shengbo Eben Li, Junzhi Zhang, Zhi Wang

- This study proposes a multi-horizon reinforcement learning (MHRL) featuring a novel state representation and coordinated training of sub-networks across multiple time scales, which greatly improves fuel economy in real-world driving.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TITS</div><img src='images/IEEE_TITS_2025_500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Bi-Level Transfer Learning for Lifelong-Intelligent Energy Management of Electric Vehicles](https://ieeexplore.ieee.org/document/11034670)

**Hao Zhang**, Nuo Lei, Wang Peng, Bingbing Li, Shujun Lv, Boli Chen, Zhi Wang

[**Industrial Collaborator: BYD Auto**](https://www.byd.com/us) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper proposes a bi-level transfer approach with MAML to realize cross-platform transferable and online-adaptive EMS for REEVs. It contributed to the successful industry deployment of RL methods, implemented in leading automotive company - BYD Auto, significantly enhancing the REEV efficiency. 
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TVT</div><img src='images/IEEE_TVT_TCNN_500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Theory-Constrained Neural Network with Modular Interpretability for Fuel Cell Vehicle Modelling](https://ieeexplore.ieee.org/document/10852019)

Nuo Lei, **Hao Zhang*** (Corresponding Author), Hong Wang, Zunyan Hu, Hu Chen, Jingjing Hu, Zhi Wang

[**Industrial Collaborator: Hybot**](http://www.hybot.com.cn/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper proposes a theory-constrained neural network (TCNN) that integrates physical principles without sacrificing accuracy. A theory-guided filter ensures sub-module interpretability, and sub-networks are individually trained under theoretical constraints with a CNN-BiLSTM-MHSA architecture enhances overall accuracy. Results demonstrate significant improvements in fitting accuragy for fuel cell modeling.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Energy</div><img src='images/EGY_RL_ECMS_500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Modeling and control system optimization for electrified vehicles: A data-driven approach](https://www.sciencedirect.com/science/article/pii/S0360544224029712?via%3Dihub)

**Hao Zhang**, Nuo Lei, Boli Chen, Bingbing Li, Rulong Li, Zhi Wang

[**Industrial Collaborator: Dongfeng Motor**](https://www.dongfeng-global.com/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This paper develops a high-fidelity PHEV model integrating physical and data-driven approaches, and proposes a real-vehicle control framework that combines horizon-extended reinforcement learning with ECMS to improve practical energy management.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Aplied Energy</div><img src='images/APEN_CPO_500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Coupled velocity and energy management optimization of connected hybrid electric vehicles for maximum collective efficiency](https://www.sciencedirect.com/science/article/pii/S0306261924001752?via%3Dihub)

**Hao Zhang**, Boli Chen, Nuo Lei, Bingbing Li, Chaoyi Chen, Zhi Wang

- This paper proposes an efficient nested parallel optimization (NPO) strategy based on the ‘1+n’ mixed platoon concept, integrating Pontryagin’s minimum principle into a constrained control framework to jointly optimize speed planning and energy control of heterogeneous CAVs. The method reduces the control state-action dimensions while balancing traffic efficiency and fuel economy across intersections.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TTE</div><img src='images/IEEE_TTE_ITEM_500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Integrated Thermal and Energy Management of Connected Hybrid Electric Vehicles Using Deep Reinforcement Learning](https://ieeexplore.ieee.org/document/10233107)

**Hao Zhang**, Boli Chen, Nuo Lei, Bingbing Li, Rulong Li, Zhi Wang

[**Industrial Collaborator: Dongfeng Motor**](https://www.dongfeng-global.com/) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This research proposes a model-free multistate deep reinforcement learning (DRL) algorithm for integrated thermal and energy management (ITEM) of multimode connected PHEVs, leveraging AI control and traffic preview to enhance EMS performance under cold climate conditions.
</div>
</div>



# Preprints
- **Zhang H**, Lei N, Li E S, et al. Multi-scale reinforcement learning of dynamic energy controller for connected electrified vehicles. IEEE Transactions on Intelligent Transportation Systems, 2025, to be published.

# Selected Papers
- **Zhang H**, Lei N, Chen B, et al. Bi-level transfer learning for lifelong intelligent energy management of electric vehicles. IEEE Transactions on Intelligent Transportation Systems, 2025, Early Access.
- Lei N, **Zhang H**, Hu J, et al. Sim-to-real design and development of reinforcement learning-based energy management strategies for fuel cell electric vehicles. Applied Energy, 2025,393:126030.
- Lei N, **Zhang H*** (Corresponding Author), Wang H, et al. Theory-Constrained Neural Network with Modular Interpretability for Fuel Cell Vehicle Modelling. IEEE Trans. on Vehicular Technology, 2025, Early Access.
- **Zhang H**, Lei N, Chen B, et al. Modeling and control system optimization for electrified vehicles: A data-driven approach. Energy, 2024,311:133196.
- **Zhang H**, Chen B, Lei N, et al. Coupled velocity and energy management optimization of connected hybrid electric vehicles for maximum collective efficiency. Applied Energy, 2024,360:122792.
- Li B, Zhuang W, **Zhang H**, et al. Traffic-aware ecological cruising control for connected electric vehicle. IEEE Trans. on Transportation Electrification. 2024,10:5225-5240.
- **Zhang H**, Chen B, Lei N, et al. Integrated thermal and energy management of connected hybrid electric vehicles using deep reinforcement learning. IEEE Trans. on Transportation Electrification, 2024,10:4594-4603.
- Lei N, **Zhang H**, and Wang Z. A comprehensive study of various carbon-free vehicle propulsion systems utilizing ammonia-hydrogen synergy fuel. eTransportation, 2024,20:100332.
- **Zhang H**, Lei N, Wang Z. Ammonia-hydrogen propulsion system for carbon-free heavy-duty vehicles. Applied Energy, 2024,369:123505.
- Sun H, Li B, **Zhang H**, et al. Ecological electric vehicle platooning: an adaptive tube-based distributed model predictive control approach. IEEE Trans. on Transportation Electrification, 2024,11:1048-1060.
- Lei N, **Zhang H**, Li R, et al. Physics-informed data-driven modeling approach for commuting-oriented hybrid powertrain optimization. Energy Conversion and Management, 2024;299:117814.
- **Zhang H**, Lei N, Chen B, et al. Data-driven predictive energy consumption minimization strategy for connected plug-in hybrid electric vehicles. Energy, 2023,283:128514.
- Li B, Zhuang W, **Zhang H**, et al. A comparative study of energy-oriented driving strategy for connected electric vehicles on freeways with varying slopes. Energy, 2023,289:129916.
- Lei N, **Zhang H**, Wang H, et al. An improved co-optimization of component sizing and energy management for hybrid powertrains with high-fidelity model. IEEE Trans. on Vehicular Technology, 2023,72:15585-15596.
- **Zhang H**, Liu S, Lei N, et al. Learning-based supervisory control of dual mode engine-based hybrid electric vehicle with reliance on multivariate trip information. Energy Conversion and Management, 2022,257:115450.
- More publications can be found on my [Google Scholar homepage](https://scholar.google.com/citations?user=SCHOLAR_ID&user=qC9ScSkAAAAJ).


# 🎖 Honors and Awards
- *2024* Plenary Talk at 2024 China SAE Annual Conference on Advanced Powertrains
- *2024* “Shuimu Tsinghua Scholar” Talents Program, Tsinghua University
- *2024* Outstanding Doctoral Dissertation Award, Tsinghua University
- *2024* Outstanding Ph.D. Graduate (top 4%), Tsinghua University
- *2023* Comprehensive Excellence Scholarship, Tsinghua University
- *2022* Best Paper Award in the 2022 CSICE Conference on TEIP in Shanghai, China
- *2022* Comprehensive Excellence Scholarship, Tsinghua University
- *2021* Excellent Student Leader, Tsinghua University
- *2021* Comprehensive Excellence Scholarship, Tsinghua University
- *2020* Comprehensive Excellence Scholarship, Tsinghua University
- *2018* National Scholarship, Ministry of Education of China
- *2018* Best Paper Award in the 2018 IEEE ACES Conference in Denver, U.S.
- *2017* National Scholarship, Ministry of Education of China
- *2016* National Scholarship, Ministry of Education of China


# 💻 Work Experience
- *2025 - now*, Associate Director, ETAIC Research Lab, University of Texas at Arlington, U.S.
- *2025 - now*, Postdoc Researcher, Department of Mechanical Engineering, Carnegie Mellon University, U.S.
- *2025 - now*, Research Associate, Department of Electrical Engineering, University of Texas at Arlington, U.S.
- *2024 - 2024*, Postdoc Researcher, School of Vehicle and Mobility, Tsinghua University, China


# 📖 Education
- Ph.D. in Automotive Engineering, Tsinghua University, China (2024)
- Visiting student in Prof. Boli Chen's lab, University College London, U.K. (2023)
- B.Eng. in Electrical Engineering and Automation, China University of Mining and Technology, China (2019)
- Visiting student in Prof. A. A. Arkadan (IEEE Fellow)'s lab, Colorado School of Mines, U.S. (2017)


# 💬 Invited Talks
- *2024.08*, Plenary Talk, APC 2024: Joint Annual Conference on Advanced Powertrains - China SAE, "Data-Driven Modeling of Electric Powertrains and Reinforcement Learning-Based Optimal Control," China SAE, Zhenjiang, China


# 📚 Service
# Reviewer
- Reviewer, Journal, IEEE Transactions on Intelligent Transportation Systems
- Reviewer, Journal, IEEE Transactions on Intelligent Vehicles
- Reviewer, Journal, IEEE Transactions on Transportation Electrification
- Reviewer, Journal, IEEE Transactions on Vehicular Technology
- Reviewer, Journal, Renewable and Sustainable Energy Reviews
- Reviewer, Journal, Applied Energy
- Reviewer, Journal, Energy
- Reviewer, Journal, Energy Conversion and Management
- Reviewer, Journal, Engineering Applications of Artificial Intelligence
- Reviewer, Conference, IEEE Intelligent Transportation Systems Conference (ITSC)

# Teaching Assistant
- Guest Lecturer, Fundamentals of Automotive Powertrains，Tsinghua University, Fall 2023
- Teaching Assistant, Frontiers in Dynamic Systems and Control，Tsinghua University, Fall 2021
