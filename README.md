# Graph Neural Networks
A model builder helper for creating graph neural networks/message passing neural networks akin to the ones described in https://arxiv.org/abs/1704.01212, https://arxiv.org/abs/1802.03685, https://ieeexplore.ieee.org/document/4700287 and later repurposed as the companion for the formalization in https://arxiv.org/abs/1901.07984

This model helper specifically uses Layer-norm LSTMs as the update functions and MLPs as the messaging funcions, while allowing for multiple kinds/types of nodes and messaging functions to be used. These architectural decisions were made to mirror Selsam et al's model.
