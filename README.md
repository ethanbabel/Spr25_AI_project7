# README: Project 6 - Solving MDPs with Value Iteration

## Background

A **Markov Decision Process (MDP)** is a foundational framework for modeling decision-making in situations where outcomes are partly random and partly under the control of a decision-maker.

Key components:
- **States**: All possible situations the agent can encounter
- **Actions**: Choices available to the agent
- **Transition probabilities**: How likely each action moves the agent between states
- **Rewards**: Immediate feedback for each transition
- **Discount factor**: Preference for sooner rewards over later rewards

Finding an **optimal policy** (a rule for choosing actions) is crucial for intelligent behavior under uncertainty.

---

## Why this is a good assignment

This project builds naturally on concepts from early projects and topics in the course, such as **classical search**, **adversarial search**, and **game theory**, but it also introduces key new ideas:

- Like **classical search** (e.g., A*), solving an MDP involves finding optimal sequences of actions. However, unlike classical search where the next state is fully deterministic, MDPs explicitly model **uncertainty** through transition probabilities.
- Compared to **adversarial search** (e.g., Minimax), which plans against an intelligent opponent, MDPs assume a **stochastic environment** rather than an adversarial one. The uncertainty arises from randomness, not competition.
- While **game theory** studies optimal strategies among multiple agents, solving a single-agent MDP is focused solely on the **best decisions for one agent** operating in a probabilistic world.

Thus, this project bridges deterministic planning and decision-making under uncertainty, which is critical for real-world AI systems.

- Introduces **dynamic programming** in a hands-on way.
- Discusses important ideas like **Bellman updates** and **policy extraction**.
- Small enough to complete within a few hours but rich enough for real understanding.
- Lays foundation for more advanced topics like **Reinforcement Learning**.

---

## Project Structure

Students will:
1. Set up a small **Gridworld MDP** environment.
2. Implement the **Value Iteration algorithm**.
3. **Extract the optimal policy**.
4. **Visualize** the policy.
5. (Optionally) **Plot** the value iteration convergence. 
6. (Optionally) **Plot** and **Compare** the value iteration convergence for varying discount factors γ

The project includes a step-by-step guide with clear **TODOs** and hints.

---

## 👨How Students Will Work on It

- Start by understanding how states, actions, and rewards are set up.
- Implement simple initialization (value table).
- Carefully apply Bellman updates iteratively.
- Debug and check for convergence of value function.
- Extract best actions to form the optimal policy.
- Print the final policy in a nice visual format.
- (Bonus) Plot value iteration convergence and compare the speed of convergence accross different discount factors γ

This flow allows gradual learning without overwhelming complexity, while teaching one of the most central techniques in AI decision-making.
