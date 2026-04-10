# Graph-Based-Attack-Chain-Traceback-across-Multiple-In-Vehicle-Network-Domains
Rule-based IDS implementation: rules, predicates, definitions. Datasets: CAN, HOST, Ethernet traffic. For research reproducibility.
This repository contains the official implementation of the DAC 2026 paper:

Abla Smahi, Xiaohang Wang, Yu Xin, Chang Zhu, Amit Kumar Singh, Kaiwei Wu, Yingtao Jiang, and Kui Ren.

# In-Vehicle IDS Rules & Data

Rule-based IDS components for multi-domain attack traceback:
- `rules/`: HIDS, NIDS, CAN-IDS detection rules
- `predicates/`: kinematics predicates
- `definitions/`: System config & topology
- `data/`: CAN, HOST, Ethernet datasets

Supports attack chain TRACEBACK across vehicle domains.
