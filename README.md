## Learning Enhanced Game Theoretic Decision-Making for Interaction-Aware Autonomous Driving in Urban Traffic Scenarios
## Abstract
Autonomous vehicles (AVs) are expected to significantly improve road safety and traffic efficiency. However, ensuring safe decision-making in complex urban traffic scenarios remains a critical challenge due to complex interactions between AVs and surrounding traffic participants (TPs). In this context, the behaviors of nearby TPs influence the AV’s actions, and vice versa, forming highly coupled bidirectional interactions. Improper handling of such interactions may lead to unsafe decisions or even traffic accidents. To this end, a game theoretic decision-making framework for interaction-aware autonomous driving is proposed in this paper, where the inter-TP interactions are transformed to a pairwise leader-follower Stackelberg game. Specifically, a driving context-aware strategy proposal network is first developed to generate adaptive strategy spaces for surrounding TPs by incorporating historical trajectories, road structures, and interaction features. Subsequently, a convex hull–based scanning technique is introduced to identify the most influential TPs based on future spatiotemporal occupancy. Furthermore, a learning enhanced game-theoretic decision-making is formulated that incorporates predicted trajectories of TPs into the payoff function with safety-related metrics. Finally, the effectiveness of the proposed method is validated through both qualitative and quantitative experiments in multiple highly interactive urban traffic scenarios using the CARLA simulator. Experimental results demonstrate that the proposed method could improve interaction safety while maintaining travel efficiency compared with baselines. 

# Supplementary Videos of Qualitative Performance Evaluation
### Crossroad Scenarios
Case 1 | Case 2
:-------------------------:|:-------------------------:
https://github.com/user-attachments/assets/088338a0-39a5-400e-8176-27eabfecb2ce | https://github.com/user-attachments/assets/ffccb299-2d00-4701-b4f2-64250c7b8f97

### Roundabout scenario
Case 1 | Case 2
:-------------------------:|:-------------------------:
https://github.com/user-attachments/assets/381b944f-c593-4c6d-b720-5f1bf66b013d | https://github.com/user-attachments/assets/a1579023-b972-4498-97d9-77457736d344

### Mixed scenario
Case 1 | Case 2
:-------------------------:|:-------------------------:
https://github.com/user-attachments/assets/08db2592-ae21-452e-a8f8-a9fe6177498f | https://github.com/user-attachments/assets/cd1045ba-bf22-48c6-a79b-7dc800389dae
