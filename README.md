# SFADNet
In recent years, traffic flow prediction has played a crucial role in the management of intelligent
transportation systems. However, traditional forecasting methods are often limited by static spatial
modeling and fail to accurately capture the dynamic and complex relationships between time
and space, thereby affecting accuracy. This paper proposes an innovative traffic flow prediction
network, SFADNet, which segments traffic flow into different traffic modes streams based on node
spatial features and time embedding features. For each mode, we constructed independent adaptive
spatiotemporal fusion graphs (SFG) based on cross-attention mechanism. These graphs integrate Time
Information Graphs (TG) and Space Information Graphs (SG), and employ residual graph convolution
modules to better capture dynamic spatio-temporal relationships under different fine-grained traffic
modes. Comprehensive experimental results demonstrate that SFADNet outperforms current stateof-the-art baselines in performance across four large-scale datasets.
