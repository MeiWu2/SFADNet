# SFADNet
This paper proposes an innovative traffic flow prediction
network, SFADNet, which segments traffic flow into different traffic modes streams based on node
spatial features and time embedding features. \\

For each mode, we constructed independent adaptive
spatiotemporal fusion graphs (SFG) based on cross-attention mechanism. These graphs integrate Time
Information Graphs (TG) and Space Information Graphs (SG), and employ residual graph convolution
modules to better capture dynamic spatio-temporal relationships under different fine-grained traffic
modes.
![model](https://github.com/MeiWu2/SFADNet/assets/101339621/746dad2d-f802-417d-a2fa-b12a9fdd5170)
The input traffic signal $\mathcal{X}_{t-T_h:t}$
undergo temporal embedding. The cyclic temporal features
generated at time step 𝑡 are processed by the Dynamic Graph
Generation (DGG) Module to generate an adaptive dynamic
graph, serving as the input graph for the Residual Graph
Convolution (RGC) Module, which operates on multiple
traffic mode flows decoupled by the output of the Decouple
Module. The decoupled traffic mode flows are concatenated and fed into the Temporal Sequence (TS) Module for
extracting temporal information. Convolutional operations,
activation functions, and linear layers introduce nonlinear
factors, facilitating the final prediction.
![image](https://github.com/MeiWu2/SFADNet/assets/101339621/bac0c7ce-b4c6-4794-91ed-8041125f43ab)

