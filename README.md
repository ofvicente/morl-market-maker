# Optimizing Market Making Strategies: A Multi-Objective Reinforcement Learning Approach with Pareto Fronts

Here you can find all the data from the paper "Optimizing Market Making Strategies: A Multi-Objective Reinforcement Learning Approach with Pareto Fronts".

### Abstract

Financial markets are complex ecosystems with market makers playing a crucial role in providing liquidity. These market makers encounter the task of striking a balance between maximizing profitability and minimizing inventory levels. Traditionally, this problem has been approached with reinforcement learning (RL) as a single-objective framework by combining both goals into a parameterized function. In this paper, we propose $M^3ORL$ (Market-Maker based on Multi-Objective RL), a pure multi-objective market maker agent based on deep RL to simultaneously optimize both objectives independently. The utilization of Pareto fronts allows for visualizing and analyzing the trade-offs between objectives without the need for reward engineering, providing multiple optimal policies. Furthermore, this approach offers advantages over traditional reward engineering-based methods, which are discussed in detail. We compare our approach to classic alternatives based on reward engineering and demonstrate its effectiveness in achieving a balance between profitability and inventory control. We evaluate our method using well-known multi-objective metrics such as hypervolume, the sparsity of solutions, and the number of undominated solutions, showcasing its superior performance. Moreover, we believe that our approach is promising in addressing diverse financial challenges beyond market-making. The ability to simultaneously optimize multiple objectives using RL and Pareto fronts opens up new possibilities for tackling complex problems in the financial domain.


### Authors

Corresponding author: 
- Óscar Fernández Vicente. (oscar.f.vicente@alumnos.uc3m.es)

Contributing authors: 
- Javier García Polo (franciscojavier.garcia.polo@usc.es)
- Fernando Fernández Rebollo (ffernand@inf.uc3m.es)

*Note

The train and test data regarding RE-AIIF agent can be found at:
- https://github.com/ofvicente/automated_mm_paper/

