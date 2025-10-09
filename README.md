**graph-based-kv-cache-compression**

This repository presents a graph-based Key–Value (KV) cache compression framework designed to enable efficient deployment of Large Language Models (LLMs) in edge and resource-constrained environments.

LLMs typically suffer from high memory and compute overhead during autoregressive inference due to large KV cache requirements. To address this, the proposed method models KV cache entries as nodes in a dynamic similarity graph, performing centroid-based merging guided by a tunable distance threshold. This adaptive mechanism allows compression to scale with context similarity while maintaining model fidelity.

**Repository Structure**

1) Model & Framework Implementation:
Python implementation of the graph-based KV cache compression algorithm, including graph construction, similarity computation, and centroid-based cache merging.

2) Evaluation Scripts:
Scripts for benchmarking the framework on GPT-2 and TinyLlama models, measuring memory reduction, latency, throughput, and perplexity metrics.

3) Visualization & Analysis:
Tools for visualizing similarity graphs, cache clustering behavior, and compression-performance trade-offs.

4) Edge Deployment Support:
Example configurations and runtime integration for deploying compressed LLMs on edge-AI devices.

**NOTE:**

1) Each experiment folder contains the corresponding configuration, dataset, and evaluation scripts.

2) Results include comparative plots showing performance vs. compression ratio.

3) Compatible with PyTorch ≥ 2.1, tested on both CPU and GPU environments.

**For any queries, contact:**
yadav.49@iitj.ac.in, m23eev006@iitj.ac.in.
