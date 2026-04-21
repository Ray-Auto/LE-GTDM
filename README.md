## Learning Enhanced Game Theoretic Decision-Making for Interaction-Aware Autonomous Driving in Urban Traffic Scenarios
## Abstract
Autonomous vehicles (AVs) are expected to significantly improve road safety and traffic efficiency. However, ensuring safe decision-making in complex urban traffic scenarios remains a critical challenge due to complex interactions between AVs and surrounding traffic participants (TPs). In this context, the behaviors of nearby TPs influence the AV’s actions, and vice versa, forming highly coupled bidirectional interactions. Improper handling of such interactions may lead to unsafe decisions or even traffic accidents. To this end, a game theoretic decision-making framework for interaction-aware autonomous driving is proposed in this paper, where the inter-TP interactions are transformed to a pairwise leader-follower Stackelberg game. Specifically, a driving context-aware strategy proposal network is first developed to generate adaptive strategy spaces for surrounding TPs by incorporating historical trajectories, road structures, and interaction features. Subsequently, a convex hull–based scanning technique is introduced to identify the most influential TPs based on future spatiotemporal occupancy. Furthermore, a learning enhanced game-theoretic decision-making is formulated that incorporates predicted trajectories of TPs into the payoff function with safety-related metrics. Finally, the effectiveness of the proposed method is validated through both qualitative and quantitative experiments in multiple highly interactive urban traffic scenarios using the CARLA simulator. Experimental results demonstrate that the proposed method could improve interaction safety while maintaining travel efficiency compared with baselines. 

# Supplementary Videos of Qualitative Performance Evaluation
### Crossroad Scenarios
Case 1 | Case 2
:-------------------------:|:-------------------------:
https://github.com/user-attachments/assets/2486e794-155e-4635-b172-3b68f14cd47d | https://github.com/user-attachments/assets/df1297e6-f009-4b35-b3c9-bd8332923e2d

### Roundabout scenario
Case 1 | Case 2
:-------------------------:|:-------------------------:
https://github.com/user-attachments/assets/41d15271-37af-4199-978e-c6ba7c297c03 | https://github.com/user-attachments/assets/d42472bb-ac31-4b37-a4f7-d550dd79d02e

### Mixed scenario
Case 1 | Case 2
:-------------------------:|:-------------------------:
https://github.com/user-attachments/assets/1ff8b99f-1ba7-4778-95f9-e3c4bc957888 | https://github.com/user-attachments/assets/dbc31cbb-9ef5-4fe1-931d-a05f1f1f357b






