# Tae-Hyeon Jang

**Reinforcement Learning & Game AI Researcher**  
M.S. Candidate in Computer Engineering, Dong-A University · Expected Feb. 2027

I research reinforcement learning agents for game environments, focusing on **exploration, reward design, policy adaptation, world models, and agent evaluation**. My work covers environment/benchmark construction, learning-pipeline implementation, reward and exploration design, and reproducible multi-seed evaluation.

## Awards & Honors

- **Outstanding Paper Presentation Award** — Korea Game Society Spring Conference, 2026
- **Outstanding Paper Award** — Korea Digital Contents Society Summer Conference, 2026
- **Academic Research Award** — Korea Multimedia Society, Feb. 2025
- **Best Paper Award** — Korea Multimedia Society Fall Conference, 2024

## Research Grants & Scholarships

- **NRF M.S. Research Fellowship** — Sep. 2025 – Aug. 2026  
  National Research Foundation of Korea (NRF)  
  *Research Topic: Reinforcement Learning-Based Automated Framework for Game Quality Assurance*  
  Individual research support for reinforcement-learning-based game QA automation; research outputs include first-author work on automated game testing and fault discovery.
- **KOSAF Outstanding Science & Engineering Scholarship for M.S. Students** — Jun. 2026 – Present
- **KOSAF Professional Technical Talent Scholarship** — Mar. 2022 – Sep. 2022

## Selected Research

### Coverage-Aware Guidance for Novelty-Driven Exploration (RND+CAE)
**Minecraft / Project Malmo · DQN · RND · Coverage-Guided Exploration**  
IEEE Access, 2026 · First Author

- Combined RND novelty with coverage-guided adaptive exploration for sparse-reward 3D game testing.
- Built Maze/Arena environments, seeded-fault logging, DQN/RND training pipelines, and multi-seed/ablation evaluation.
- Arena results: **5.70 ± 1.06 final unique bugs** and **4.66 ± 0.67 bug-discovery AUC** among the compared methods.

[Repository](https://github.com/jangjangtae/coverageguidedexploration)

### World-Model-Based Policy Reuse and Adaptation for Automated Game Testing (FATE)
**Craftax · DreamerV3 · World Models · Reinforcement Learning**  
Ongoing Research

- Investigates how pretrained gameplay policies and world models can be reused for automated game testing.
- Develops a test-oriented policy adaptation method using auxiliary rewards derived from temporal changes in frozen reference world-model surprise.
- Evaluates how additional adaptation, reward design, and reference selection affect gameplay performance and fault exposure.
- Examines the effectiveness and limitations of policy adaptation through controlled experiments.
- **Implementation and experimental code are currently private.**

### Overcoming Exploration Stagnation in Reinforcement Learning-Based Automated Game Testing (BEAGT)
**DQN · ε-greedy · Softmax Exploration · Automated Game Testing**  
Journal of Digital Contents Society, 2025 · First Author

- Detects exploration stagnation from recent reward changes and temporarily increases exploration.
- Evaluated on CartPole and MsPacman with location-based fault scenarios.

[Repository](https://github.com/jangjangtae/BEAGT)

## Game & Engine Experience

- **Unity–ML-Agents reproduction study** — reconstructed an RL-based game-testing setup, connected Unity with the ML-Agents trainer, validated agent training, and investigated observation/action and error-logging behavior.
- **VR Zombie Shooter Prototype** — implemented player movement/interactions, weapon and combat logic, enemy integration, game-flow handling, and environment integration with Unity and XR Interaction Toolkit.

[VR Prototype](https://github.com/jangjangtae/VRGame)

## Research & Engineering Stack

`Python` · `JAX` · `Stable-Baselines3` · `DreamerV3` · `DQN` · `RND` · `Unity ML-Agents` · `Project Malmo` · `Craftax` · `TensorBoard`

## Publications

### Journal Articles

- **Tae-Hyeon Jang**, Hyeon-Uk Lee, Hyunseok Kim, *Coverage-Aware Guidance for Novelty-Driven Exploration in Automated Game Testing under Sparse-Reward 3D Environments*, **IEEE Access**, 2026. **(First Author)** · [DOI](https://doi.org/10.1109/ACCESS.2026.3730445)
- Hyeon-Uk Lee, **Tae-Hyeon Jang**, Minkook Son, Jae Hoon Jang, Hyunseok Kim, *DeLTL: Decoupled Architecture for Learning Efficiency and Generalization in Linear Temporal Logic Tasks*, **IEEE Access**, 2026. **(Co-author)** · [DOI](https://doi.org/10.1109/ACCESS.2026.3708960)
- **Tae-Hyeon Jang**, Yeajin Lee, Hyunseok Kim, *Overcoming Exploration Stagnation in Reinforcement Learning-Based Automated Game Testing*, **Journal of Digital Contents Society**, 2025. **(First Author)** · [DOI](https://doi.org/10.9728/dcs.2025.26.7.1801)
- Yejin Lee, Hoyoung Song, Seong Hwan Kim, **Tae-Hyeon Jang**, Younglim Choi, Hyunseok Kim, *PerAct-L: Linear Self-Attention Mechanism for Computational Optimization of Robotic Transformer*, **Journal of Korea Multimedia Society**, 2025. **(Co-author)**

### Selected Conference Papers

- **장태현**, 옥수열, 이석환, 김현석, *복합재난 대응 시뮬레이션 확장을 위한 월드 모델 기반 게임 결함 탐지 가능성 분석*, **한국게임학회 춘계 학술발표대회**, 2026. **(First Author · 우수논문 발표상)**

### Ongoing Manuscript

- First-author research manuscript on **world-model-based policy reuse and test-oriented adaptation for automated game testing**. Additional experiments and manuscript revisions are in progress; implementation details and code are not publicly disclosed.

## Links

- [Google Scholar](https://scholar.google.com/citations?user=7PW_SEcAAAAJ&hl=ko)
- Research Website: https://sites.google.com/view/taehyeon-jang
- Email: jth000210@gmail.com
