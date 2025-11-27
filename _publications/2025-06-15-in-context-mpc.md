---
title: "LLM-Based Adaptive Distribution Voltage Regulation Under Frequent Topology Changes: An In-Context MPC Framework"
collection: publications
permalink: /publication/2025-06-15-in-context-mpc
excerpt: 'This paper introduces an LLM-based adaptive inverter control scheme for distribution voltage regulation under frequent topology changes. By using in-context learning to build a topology-adaptive power flow surrogate and integrating it with LSTM-based load forecasting and MPC, the method adapts to both known and unseen topologies with minimal fine-tuning. Its effectiveness is demonstrated on a modified IEEE 123-bus test system.'
date: 2025-06-15
venue: 'TSG'
paperurl: 'https://ieeexplore.ieee.org/document/11054276'
# citation: 'Coming Soon'
---
 This paper proposes a large language model (LLM) based adaptive inverter control for distribution voltage regulation under frequent topology changes. We leverage the ability of the LLM to perform in-context learning and create a topology-adaptive surrogate model for power flow calculation. The surrogate model is then integrated with a long short-term memory-based load forecaster and a model predictive control (MPC) scheme to achieve the optimal inverter control that adapts to frequent topology changes. Unlike many existing works that assume fixed-topology grids or require the knowledge of all possible topologies when training a model, the proposed in-context MPC method tackles the distribution voltage control problem under various topologies and adapts to unknown topologies with limited data requirement for fine-tuning. The effectiveness of our method is demonstrated on a modified IEEE 123-bus test system.

 
[Download paper here](https://ieeexplore.ieee.org/document/11054276)

