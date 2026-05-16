# NVIDIA NEMOTRON Workshop Notes

HydPy is hosting an NVIDIA Nemotron 3 Super Workshop - India

📅 Saturday, May 16

⌚ 9:00 AM - 3:30 PM GMT+5:30

📍 IIIT Hyderabad, Telangana

## Terms to Know

### Models and architecture
- MoE in Models
- NVIDIA Nemotron
  - A family of efficient, open, multimodal models, datasets, and technologies for long-running, specialized agentic AI systems
  - Built for reasoning, coding, visual understanding, safety, speech, and information retrieval
  - Supports deployment across NVIDIA RTX PRO™ and NVIDIA DGX Spark™
- Nemotron-3 Super
- Magpie TTS Multilingual 357m
- Personaplex 7B
- Best Models, Largest Models, SLM, Fastest Models in Open Source
- GNN
- SSM
- LBM
- VLM
- VLA
- CPT

### Hardware and infrastructure
- GB200 NVL72
- Vera Rubin NVL72
- TPU vs Rubin
- TPS per MW
- Memory Bound / Compute Bound
- Infiniband / rack-scale systems
- Block-based scaling in NVIDIA
- Helm chart
- GPU Direct Storage (GDS) - NVIDIA

### Inference and runtime
- Inference Endpoints
- LLM inference phases
  - Prefill phase
  - Decoding phase
  - Attention Mechanism
- KV-Cache (Key-Value Cache optimization)
- Tool call flow in LLMs
- Guardrail speech-to-speech under low latency

### Speech, voice, and real-time systems
- Nemotron Speech / Streaming ASR
- Nemotron Voice Agent
- WebRTC transport
- Magpie TTS Zeroshot (instant voice cloning)
- Speech/voice guardrails

### Glossary and optimization terms
- LLM glossary: HBM, I/OSL, MHA, FFN, MoE, FTL, TTFT, TPOT, FLOPS
- LatentMoE

### Useful links
- https://github.com/karpathy
- https://docs.aws.amazon.com/nova/latest/userguide/nova-cpt.html
- https://huggingface.co/docs/peft/package_reference/cpt
- https://afmck.in/posts/2023-02-26-parallelism/
- https://huggingface.co/docs/transformers/en/perf_train_gpu_many
- https://developer.nvidia.com/blog/how-the-nvidia-vera-rubin-platform-is-solving-agentic-ais-scale-up-problem/
- https://www.microsoft.com/en-us/research/project/rack-scale-computing/
- https://developer.nvidia.com/blog
- https://blog.google/innovation-and-ai/technology/ai/
- https://www.nvidia.com/en-in/ai-data-science/foundation-models/nemotron/
- https://huggingface.co/nvidia/personaplex-7b-v1
- https://developer.nvidia.com/dynamo
- https://www.systalyze.com/
- https://nvtop.org/
- https://github.com/systalyze/utilyze
- https://developer.nvidia.com/blog/scaling-large-moe-models-with-wide-expert-parallelism-on-nvl72-rack-scale-systems/
- https://github.com/Wan-Video/Wan2.2
- https://huggingface.co/nvidia/magpie_tts_multilingual_357m
- https://huggingface.co/nvidia
- https://webrtc.org/
- https://github.com/livekit/client-sdk-js
- https://build.nvidia.com/nvidia/nemotron-voice-agent
- https://build.nvidia.com/nvidia/pdf-to-podcast
- https://research.nvidia.com/labs/nemotron/LatentMoE/
- https://research.nvidia.com/labs/nemotron/Nemotron-3-Super/
- https://research.nvidia.com/labs/nemotron/
- https://docs.nvidia.com/nemotron/nightly/nemotron/super3/README.html
- https://research.nvidia.com/labs/nemotron/files/NVIDIA-Nemotron-3-Super-Technical-Report.pdf
- https://developer.nvidia.com/blog/introducing-nemotron-3-super-an-open-hybrid-mamba-transformer-moe-for-agentic-reasoning/
- https://developer.nvidia.com/
- https://github.com/ai-dynamo/dynamo
- https://github.com/scitix/InstantTensor


## Questions to Find Answers
- What exactly is NVIDIA Nemotron and how is it positioned versus other foundation model families?
- How does NVIDIA Vera Rubin NVL72 compare to TPU in performance, cost, and efficiency?
- What is TPS per MW and how is it measured for large models?
- What are the practical differences between pre-training and post-training?
- How do tool calls happen in LLMs? What is the flow, scalability, and main limitations?
- How does KV-Cache work across the prefill and decoding phases?
- What role does Infiniband / NVL72 rack-scale architecture play in wide expert parallelism for MoE?
- How do inference endpoints differ from standard serving methods?
- What does block-based scaling mean in NVIDIA, and how does the scaling factor work?
- How are guardrails implemented for speech-to-speech with low latency?
- What are the best open-source and NVIDIA resources for Nemotron, Magpie TTS, and voice agents?

----
# NVIDIA Developer Program

NVIDIA Developer Program
- DGX Spark
- Enforce Eager (Never to do in Production)
- Constraint Decoding
- GDDR | MDNS | LPDDR | HBM

