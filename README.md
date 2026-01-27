# portfolio_rebalancing

Accelerating Practical Portfolio Rebalancing via Integer Programming and Machine Learning

Qian Hu,(a) Ke Li,(a) Xingyu Lu,(a,b) Caihua Chen,(a,*) Zhixing Luo,(a) Zhibo Zhu(b)
(a) School of Management and Engineering, Nanjing University, Nanjing 210093, China; (b) Ant Group, Hangzhou
310000, China

This paper investigates a practical portfolio rebalancing problem faced by a leading fintech company serving more than one billion users on its mobile application. The problem poses a computation challenge as recommended rebalancing solutions must be computed and returned to users in near real-time. We overcome this challenge by reformulation and algorithm design leveraging integer programming and machine learning. We introduce an improved formulation through integer programming techniques, transforming the original mixed-integer nonlinear program into a more tractable mixed-integer quadratic program and further strengthening it via a novel fund transfer flow representation. The continuous relaxation of our improved formulation dominates the baseline model. We propose a predict-then-optimize framework that leverages neural network to identify promising assets for weight increase, enabling rapid computation of restricted models with significantly reduced binary variables. Computational experiments demonstrate that our improved formulation solves most test instances to optimality within a minute, while our predict-then-optimize methods find optimal and near-optimal solutions with average computation times under 500 milliseconds, representing significant speedups over the baseline model. Our approaches are suitable for practical portfolio rebalancing applications where both solution quality and response time are critical.
