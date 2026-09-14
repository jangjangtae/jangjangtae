# Tae-Hyeon Jang

**Reinforcement Learning & Game AI Researcher**  
M.S. Candidate in Computer Engineering, Dong-A University · Expected Feb. 2027

I research reinforcement learning agents for game environments, focusing on **exploration, reward design, policy adaptation, world models, and agent evaluation**. My work covers environment/benchmark construction, learning-pipeline implementation, reward and exploration design, and reproducible multi-seed evaluation.

## Selected Research

### Coverage-Aware Guidance for Novelty-Driven Exploration (RND+CAE)
**Minecraft / Project Malmo · DQN · RND · Coverage-Guided Exploration**  
IEEE Access, 2026 · First Author

- Combined RND novelty with coverage-guided adaptive exploration for sparse-reward 3D game testing.
- Built Maze/Arena environments, seeded-fault logging, DQN/RND training pipelines, and multi-seed/ablation evaluation.
- Arena results: **5.70 ± 1.06 final unique bugs** and **4.66 ± 0.67 bug-discovery AUC** among the compared methods.

[Repository](https://github.com/jangjangtae/coverageguidedexploration)

### World-Model-Based Policy Adaptation for Game Testing
**Craftax · DreamerV3 · World Models · Policy Adaptation**  
First Author · Under Review

- Studies policy adaptation for broader fault exposure while preserving task competence.
- Explores world-model-based auxiliary signals for adapting agent behavior during game testing.
- Evaluated under multiple fault conditions with matched multi-seed experiments.
- **Implementation details and code are kept private while the manuscript is under review.**

### Overcoming Exploration Stagnation in Reinforcement Learning-Based Automated Game Testing (BEAGT)
**DQN · ε-greedy · Softmax Exploration · Automated Game Testing**  
Journal of Digital Contents Society, 2025 · First Author

- Detects exploration stagnation from recent reward changes and temporarily increases exploration.
- Evaluated on CartPole and MsPacman with location-based fault scenarios.

[Repository](https://github.com/jangjangtae/BEAGT)

## Game & Engine Experience

- **Unity–ML-Agents reproduction study** — reconstructed an RL-based game-testing setup, connected Unity with the ML-Agents trainer, validated agent training, and investigated observation/action and error-logging behavior.
- **VR Zombie Shooter Prototype** — implemented player movement/interactions, weapon and combat logic, enemy integration, game-flow handling, and environment integration with Unity, XR Interaction Toolkit, and Blender.

[VR Prototype](https://github.com/jangjangtae/VRGame)

## Research & Engineering Stack

`Python` · `JAX` · `Stable-Baselines3` · `DreamerV3` · `DQN` · `RND` · `Unity ML-Agents` · `Project Malmo` · `Craftax` · `TensorBoard`

## Publications

- **Tae-Hyeon Jang**, Hyeon-Uk Lee, Hyunseok Kim, *Coverage-Aware Guidance for Novelty-Driven Exploration in Automated Game Testing under Sparse-Reward 3D Environments*, IEEE Access, 2026.
- **Tae-Hyeon Jang**, Yeajin Lee, Hyunseok Kim, *Overcoming Exploration Stagnation in Reinforcement Learning-Based Automated Game Testing*, Journal of Digital Contents Society, 2025.
- First-author manuscript under review on **world-model-based policy adaptation for automated game testing**. Implementation and exact manuscript details are not publicly disclosed.

## Links

- Research Website: https://sites.google.com/view/taehyeon-jang
- Email: jth000210@gmail.com
