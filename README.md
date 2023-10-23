# Kyrie-Curiosities-Cabinet
## Kyrie's Cabinet of Curiosities 

1. Compiler for FL (computation+communication)

2. Is it possible to adopt imitation learning or other IRL approaches to mimic DNN compiler generated kernels,,, shortening long tuning process, boosting cross-device compiling?

3. NeRF, Q4ML, ML4Q, QCompiler... dazzled, [Closing the Gap between Quantum Algorithms and Machines with Hardware-Software Co-Design](https://people.cs.uchicago.edu/~ftchong/Chong-QC-UCLA19.pdf)

4. Sim2Real Runtime Engine, for e.g. [MinDOJO](https://github.com/MineDojo/MineDojo), autonomous driving?[X], nature of simulation: massive data, exploration cost, distributed traing <-> real. 

5. Carbon-aware DNN Compiler
- [EDEN: Enabling energy-efficient, high-performance deep neural network inference using approximate DRAM](https://dl.acm.org/doi/pdf/10.1145/3352460.3358280) by Koppula, Skanda, et al., MICRO 2019
- [Carbon Explorer: A Holistic Framework for Designing Carbon Aware Datacenters](https://www.seas.upenn.edu/~leebcc/documents/acun23-explorer.pdf) by Acun, Bilge, et al., ASPLOS 2023
- [octoml](https://www.linkedin.com/pulse/octoml-drives-down-production-ai-inference-costs-microsoft-octoml/?trackingId=Q2kohbkIR0qJ8TOzKcBc5Q%3D%3D)
- lamppost, energy = cost,  "However, AI inference at such a massive scale is very expensive."
- [Zeus](https://symbioticlab.org/publications/files/zeus:nsdi23/zeus-nsdi23.pdf)

The OctoML Platform has always provided automation for exploring multiple model acceleration techniques. Via our new TVM-ONNX Runtime integration, 

6. Duet类似的dual device inference的nn compiler+runtime，异构子图优化，根据不同设备的并行性能优化。

7. Diffusion model Survey [Diffusion models: A comprehensive survey of methods and applications](https://arxiv.org/pdf/2209.00796)

8. Crypto | Privacy | Security + Accelerator
- CryptGPU
- PolyMPCNet
- Crypten
- Cheetah

9. On-device AI
- [EfficientFormer: Vision Transformers at MobileNet Speed](https://arxiv.org/pdf/2206.01191)
- [FlexiBERT: Are Current Transformer Architectures too Homogeneous and Rigid?](https://arxiv.org/pdf/2205.11656)

10. [Summarizing CPU and GPU Design Trends with Product Data](https://chip-dataset.vercel.app/)
 
11. [prompt](https://github.com/ZrrSkywalker/CaFo)

12. webGPU (https://github.com/mlc-ai/web-stable-diffusion)

13. zeroth order optimization (blackboxML)

14. Unified abstarctions for IoT datastream.

15. mlir for heter-device ml-flow (dnn & non-dnn operators & flow)

16. tile ir => mixed-tile ir? cross-domain/modality ir? Pain point: multi-layer IR redundant code opt. iree support vulkan-spirv，for mobile gpu and cpu => compiler support for data flow in e2e auto vehicle

17. LLM running with CNN and DNN, co-running transformer and CNN.

18. 大模型更强的表征能力赋给在线小模型。

18. NPU running LLM, energy problem.

19. llm token的稀疏性和input token的动态性使distributed inference不是所有通信都是必要的。

20. machine unlearning ood

21. 样本端不愿意给label，都从云走的话太慢，以及云负载过大。

22. 未知任务识别放edge，未知任务识别在云上？

23. 有多少edge数据放在边缘侧可以finetune出比较好的垂直大模型？

24. Simulator for edge？

25. 大模型compiler for edge,迁移性

26. finetuning edge llm + compiler

27. rTile, rGraph, 重新定义基本单元，不要以op为单位，see as dataflow。load-compute-store。大模型on edge as dynamic nn。

28. Develop compiler strategies that can efficiently distribute model computations between edge and server GPUs, considering factors such as network latency, communication overhead, and load balancing.

29. To facilitate this mapping, WELDER provides an abstracted accelerator device with hierarchical memory layers.

30. Tensor 版本的imagebind, meta-transformer. Tuned records of same op/graphs (objects) on different hardwares (modality). Goal: unify hardware intrinsics, feature: cost model <-> svm对image到现在的encoder

31. Explore Data Placement Algorithm for Balanced Recovery Load Distribution

32. zpoline: a system call hook mechanism based on binary rewriting
