# PTSPM
Final year B-tech Project
Team 29
Manyam Avinash 187233		Vamshi Krishna 187243		Nirav Patel 187242


TITLE:
Joint task scheduling and Energy Management for Heterogeneous Mobile Edge Computing with Hybrid Energy Supply


IMPORTANCE:
Edge computing is important because it creates new and improved ways for industrial and enterprise-level businesses to maximize operational efficiency, improve performance and safety, automate all core business processes, and ensure “always-on” availability. It is a leading method to achieve the digital transformation of how you do business.Increasing computing power at the edge is the foundation needed to establish autonomous systems, enabling companies to increase efficiency and productivity while enabling personnel to focus on higher-value activities within the operation.Edge computing works hand in hand with the cloud to provide a flexible solution based on the data collection and analysis needs of each organization. For real-time collection and analysis, the edge is ideal for certain workloads. At the same time, the cloud can provide a centralized location for large-scale analytics.  Together they provide real-time and longer-term insights into performance and power initiatives like machine learning and asset performance management.
Mobile edge computing (MEC) has recently become a promising paradigm to meet computer growth. The need for mobile devices, as well as the mixed power supply has been considered an effective way to save the use of electricity in the MEC system and make it environmentally friendly. In particular, scheduling energy-related work the management system plays an important role in reaping the benefits of the MEC through a mixed power supply.


LITERATURE SURVEY:
A solution to energy management and task scheduling in the substations using TSEM algorithm that uses Lyapunov function, By transforming the long-term stochastic optimization problem to a deterministic problem under each time slot aiming at maximizing the average system utility while keeping the queue stable and meeting the energy budget.



Research papers we have gone through are:-

L. P. Qian, Y. Wu, B. Ji, and X. Shen, “Optimal admm-based spectrum and power allocation for heterogeneous small-cell networks with hybrid energy supplies,” IEEE Transactions on Mobile Computing, pp. 1–1, 2019. 
L. Chen, S. Zhou, and J. Xu, “Computation peer offloading for energy-constrained mobile edge computing in small-cell networks,” IEEE/ACM Transactions on Networking, vol. 26, no. 4, pp. 1619–1632, Aug 2018 
C. You, K. Huang, H. Chae, and B. H. Kim, “Energy-efficient resource allocation for mobile-edge computation offloading,” IEEE Transactions on Wireless Communications, vol. 16, no. 3, pp.1397–1411, March 2017.
M. J. Neely, Stochastic Network Optimization With Application to Communication and Queueing Systems. Morgan & Claypool,2010.
H. Lu, C. Gu, F. Luo, W. Ding, and X. Liu, “Optimization of lightweight task offloading strategy for mobile edge computing based on deep reinforcement learning,” Future GenerationComputer Systems, vol. 102, pp. 847 – 861, 2020


UNDERSTANDING EXISTING ALGORITHMS AND THEIR DRAWBACKS:
The given TSEM algorithm is understood and has been learnt that it is a linear programming problem and when compared to other similar algorithms it has been proved that this gives maximum system utilization while keeping queue length stable.
We have found certain drawbacks regarding this algorithm that is it has taken a lot of assumptions like energy required to send computation tasks from mobile devices is 0 and also they constrained the energy budget as 3500 J which should vary based on our requirements and also for the algorithm to be efficient we should select a tradeoff parameters which increases overall system utility and currently is not very scalable as it has computational power is limited.we have addressed these problems in our proposed method


PROPOSED METHOD:
After understanding and analyzing various research papers we have found that priority based scheduling ensures high system utility and the cost saved per sec by SBS is higher than the TSEM algorithm proposed.Thus we can analyze how system utility and queue length behaves with the change in tasks size and their priorities.




ALGORITHM:
As mentioned above, first we input the dynamic dataset (taking random values and varying the number of devices) and then we fix admission cost(V), MEC computing capacity and by this we can implement TSEM.
The given TSEM minimization problem can be solved individually by dividing it into 4 sub-problems
Auxiliary Variable Selection (AUS)
Admission Control Decision (ACD)
Task Scheduling and Energy Management in SBS
Task Allocation in MBS (TAM)

By this algorithm, we can achieve a high system utility while keeping the queue length stable. We can also vary parameters like energy budget and energy consumption rate to get optimal values and vary accordingly.


IMPROVED ALGORITHM:
As a replacement for organizing tasks inside SBS and MBS in a primary manner we have introduced a priority based scheduling algorithm.
Brought in a priority based approach on arrival time and size of the task which avoids starvation and fairness among SBS.
Introduced a parameter called delay which tells about average execution delay of the task.


OBSERVATIONS:
By our improved algorithm we can observe a crucial increase in utility and average cost saved per second by SBS. In the long run we can observe that a significant amount is saved. By noticing there is an increase in utility so that tasks admission and servicing rate improves thus resulting in end users satisfaction.



CONCLUSION: 
So far we have implemented the research paper and upgraded it.we are in process of further identification of other optimization techniques. We also plan to analyze important parameters in fuzzy logic optimization problem and how they affect the whole system.


    

     
           
   




