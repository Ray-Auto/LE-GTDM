## Learning Enhanced Game Theoretic Decision-Making for Interaction-Aware Autonomous Driving in Urban Traffic Scenarios
## Abstract
Autonomous vehicles (AVs) are expected to significantly improve road safety and traffic efficiency. However, ensuring safe decision-making in complex urban traffic scenarios remains a critical challenge due to complex interactions between AVs and surrounding traffic participants (TPs). In this context, the behaviors of nearby TPs influence the AV’s actions, and vice versa, forming highly coupled bidirectional interactions. Improper handling of such interactions may lead to unsafe decisions or even traffic accidents. To this end, a game theoretic decision-making framework for interaction-aware autonomous driving is proposed in this paper, where the inter-TP interactions are transformed to a pairwise leader-follower Stackelberg game. Specifically, a driving context-aware strategy proposal network is first developed to generate adaptive strategy spaces for surrounding TPs by incorporating historical trajectories, road structures, and interaction features. Subsequently, a convex hull–based scanning technique is introduced to identify the most influential TPs based on future spatiotemporal occupancy. Furthermore, a learning enhanced game-theoretic decision-making is formulated that incorporates predicted trajectories of TPs into the payoff function with safety-related metrics. Finally, the effectiveness of the proposed method is validated through both qualitative and quantitative experiments in multiple highly interactive urban traffic scenarios using the CARLA simulator. Experimental results demonstrate that the proposed method could improve interaction safety while maintaining travel efficiency compared with baselines. 

# Supplementary Videos of Qualitative Performance Evaluation
### Crossroad Scenarios
Case 1 | Case 2
:-------------------------:|:-------------------------:
https://github.com/user-attachments/assets/91768ac0-e4c1-4028-8a40-0ea7718865fe | https://github.com/user-attachments/assets/3da54eae-5448-40b4-92d8-2c11c2885278

### Roundabout scenario
Case 1 | Case 2
:-------------------------:|:-------------------------:
https://github.com/user-attachments/assets/3cc06934-ca2e-4211-ab4f-396e5152a56b | https://github.com/user-attachments/assets/24f7c626-46d7-4593-972d-423cd79c839d

### Mixed scenario
Case 1 | Case 2
:-------------------------:|:-------------------------:
https://github.com/user-attachments/assets/51ad622d-ca4c-4747-a538-347df4b299e6 | https://github.com/user-attachments/assets/f102d87f-47d9-4008-b265-ad2352b20cee

