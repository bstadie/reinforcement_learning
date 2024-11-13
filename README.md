# Stat 436 -- Reinforcement Learning Fall 2024

# Course Materials
[Sutton and Barto: Reinforcement Learning, an Introduction](http://incompleteideas.net/book/RLbook2020.pdf)

[Open AI: Spinning up](https://spinningup.openai.com/en/latest/spinningup/keypapers.html)

[Reinforcement Learning: Theory and Algorithms, Agarwal et al. (theory reference)](https://rltheorybook.github.io/rltheorybook_AJKS.pdf)

[Tour of RL](https://arxiv.org/pdf/1806.09460)

# TA Office Hours
Youngmin Ko, youngminko2027@u.northwestern.edu

Friday, Sept 27 10:30-11:30am

Wednesdays from 1:30-2:30pm

Zoom link: https://northwestern.zoom.us/j/2592304024

# Homeworks and Due Dates


| Project title                  | Date released | Due date                
|--------------------------------|---------------|-------------------------|
|   Intro to PyTorch, Imitation Learning       | Sept 24   | Oct 2  |
|   Q-Learning      |  Oct 2   | Oct 11  |
|   Policy Gradients     |  Oct 11   | Oct 21  |
|   Midterm (online)    |  Oct 22   | Oct 22  |
|   Offline RL     | Oct 24  | Nov 11  |
|   RLHF & LLMs     |  Nov 11   | Nov 27  |
| Final presentation topic proposals |       |  Nov 29   | 
|  Final presentations        |       | Week of Dec 9th |


# Course Lectures 

Lecture notes can be found on the course Canvas website. 

S&B = Sutton and Barto, the course textbook. Available [here](http://incompleteideas.net/book/RLbook2020.pdf)


| Lecture              | Date        | Material                                      | Readings |
|----------------------|-------------|----------------------------------------------|----------|
| Week 1, Tuesday       | September 24   | RL is not very useful. Why?                  | S & B Ch 1 <br> S & B Ch 3 <br> [Supervised Learning Recap](https://see.stanford.edu/materials/aimlcs229/cs229-notes1.pdf), [PyTorch recap](https://github.com/yunjey/pytorch-tutorial/blob/master/tutorials/02-intermediate/convolutional_neural_network/main.py) <br> [Just use PID](https://archives.argmin.net/2018/04/19/pid/) |
| Week 1, Thursday       | September 26   | MDPs, Tabular RL                             |    S & B 4.1-4.4 <br> S & B 5.1 - 5.4      |
| Week 2, Tuesday     | October 1  | Q-learning                                   |      S & B 6.1 - 6.5 <br> [Playing Atari with Deep Q Learning](https://arxiv.org/abs/1312.5602), [Spinning Up](https://spinningup.openai.com/en/latest/spinningup/rl_intro.html#the-optimal-q-function-and-the-optimal-action)    |
| Week 2, Thursday     | October 3  | Advanced Q-learning                          |      [Rainbow](https://arxiv.org/abs/1710.02298), [Prioritized Experience Replay](https://arxiv.org/abs/1511.05952), [Double Q Learning](https://arxiv.org/pdf/1509.06461), [Distributional Q Learning](https://arxiv.org/pdf/1710.10044)    |
| Week 3, Tuesday      | October 8  | Policy Gradients                             |     S & B 13.1 - 13.6 <br> [The Policy of Truth](https://archives.argmin.net/2018/02/20/reinforce/), [Issues with PGs](https://archives.argmin.net/2018/03/13/pg-saga/), [Spinning Up](https://spinningup.openai.com/en/latest/spinningup/rl_intro3.html#deriving-the-simplest-policy-gradient)     |
| Week 3, Thurdsay    | October 10  | Advanced Policy Gradients                    |     [TRPO](https://spinningup.openai.com/en/latest/algorithms/trpo.html), [PPO](https://spinningup.openai.com/en/latest/algorithms/ppo.html), [DDPG](https://spinningup.openai.com/en/latest/algorithms/ddpg.html), [SAC](https://spinningup.openai.com/en/latest/algorithms/sac.html)     |
| Week 4, Tuesday    | October 15  | Exploration                                  |    [ICM](https://pathak22.github.io/noreward-rl/), [Incentivising Exploration](https://arxiv.org/abs/1507.00814), [Go-Explore](https://arxiv.org/abs/1901.10995), [VIME](https://arxiv.org/abs/1605.09674), [Optimal Exploration](https://zicokolter.com/publications/kolter2009nearbayesian.pdf)      |
| Week 4, Thursday    | October 17  | Inverse RL                                   |     [GAIL](https://arxiv.org/abs/1606.03476), [Inverse RL](https://ai.stanford.edu/~ang/papers/icml04-apprentice.pdf), [Third Person Imitation](https://arxiv.org/abs/1703.01703)     |
| Week 5, Tuesday    | October 22  | Online Midterm Exam (no class)                                  |          |
| Week 5, Thursday  | October 24  | Advanced Imitation (diffusion)               |       [Diffuser](https://arxiv.org/pdf/2205.09991), [Cold Diffusion on the Replay Buffer](https://arxiv.org/pdf/2310.13914)   |
| Week 6, Tuesday      | October 29  | Offline-RL & Model-Based RL                                  |     [CQL](https://sites.google.com/view/cql-offline-rl), [TDMPC](https://www.tdmpc2.com/), [Dreamer](https://research.google/blog/introducing-dreamer-scalable-reinforcement-learning-using-world-models/#:~:text=Dreamer%20consists%20of%20three%20processes,environment%20to%20collect%20new%20experience.), [IQL](https://arxiv.org/abs/2110.06169)     |
| Week 6, Thursday | October 31 | RLHF, RLAIF                                  |    [Instruct GPT](https://arxiv.org/abs/2203.02155), [DPO](https://arxiv.org/abs/2305.18290), [BCO](https://arxiv.org/html/2404.04656v1), [RLHF overview](https://realcwl.github.io/posts/rlhf_to_ipo/), [Code](https://github.com/huggingface/trl), [RLAIF](https://arxiv.org/abs/2309.00267)      |
| Week 7, Tuesday | November 5 | No class (Election Day)                               |          |
| Week 7, Thursday      | November 7 | Alpha-Zero                                   |     [Simple ALpha Zero](https://suragnair.github.io/posts/alphazero.html), [Another blog](https://nikcheerla.github.io/deeplearningschool/2018/01/01/AlphaZero-Explained/), [Alpha Zero](https://arxiv.org/abs/1712.01815), [MuZero](https://arxiv.org/abs/1911.08265), [Official implementation](https://github.com/google-deepmind/mctx), [Efficient-Zero](https://arxiv.org/abs/2111.00210)     |
| Week 8, Tuesday    | November 12 | Multi-Goal RL                                |    [HER](https://arxiv.org/abs/1707.01495), [MEGA](https://arxiv.org/pdf/2007.02832), [Skew-Fit](https://arxiv.org/abs/1903.03698)      |
| Week 8, Thursday | November 14 | Hierarchical RL & Graph-based RL             |     [HIRO](https://arxiv.org/abs/1805.08296), [L3P](https://arxiv.org/abs/2011.12491)     |
| Week 9, Tuesday      | November 19 | Few Shot Learning (Wonderful Team)           |      [MAML](https://arxiv.org/abs/1703.03400), [Wonderful Team](https://wonderful-team-robotics.github.io/)    |
| Week 9, Thursday     | November 21 | AI Safety                                    |     [AI Saftey Gridworlds](https://deepmind.google/discover/blog/specifying-ai-safety-problems-in-simple-environments/), [Blog post](https://deepmindsafetyresearch.medium.com/designing-agent-incentives-to-avoid-side-effects-e1ac80ea6107), [Concrete AI saftey](https://arxiv.org/pdf/1606.06565), [Off switch game](https://arxiv.org/abs/1611.08219), [Inverse reward design](https://proceedings.neurips.cc/paper/2017/hash/32fdab6559cdfa4f167f8c31b9199643-Abstract.html),  [Red Teaming](https://arxiv.org/abs/2202.03286), [Unsolved ML saftey](https://arxiv.org/abs/2109.13916), [Models vs Data](https://dl.acm.org/doi/abs/10.1145/3411764.3445518?casa_token=h4EZACtq7D4AAAAA:KC3FtAQHC0Dv4qSistc-QUbNgQQ2sFgg-Vy8LdtM_dIxYtqJLLn3Uwomnsv87ApSNWVwtl5bPbjqQBk)    |
| Week 10, Tuesday     | November 26    | No class                       |          |
| Week 11, Tuesday     | December 3   | Science Fiction and RL                      |          |






