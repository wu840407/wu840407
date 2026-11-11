## Hi, I'm Roger (ChengRung Wu) 👋

**AI infrastructure engineer — I make large language models run fast on hardware that shouldn't be able to run them.**

10 years building and deploying mission-critical systems. Currently focused on LLM inference: quantization, tensor parallelism, and serving 27B–30B-class models fully offline on constrained GPUs, with every performance number checked against a first-principles ceiling.

---

### 🚀 Featured Projects

| Project | What it is |
|---------|------------|
| **[llm-inference-benchmark](https://github.com/wu840407/llm-inference-benchmark)** | Reproducible vLLM vs TensorRT-LLM benchmark on one RTX 3090, checked against a first-principles roofline. Includes the post-mortem of a 20× measurement error I caught in my own harness. |
| **[enterprise-airgapped-llm](https://github.com/wu840407/enterprise-airgapped-llm)** | Reference architecture for a self-hosted LLM platform in air-gapped environments — 4-bit quantized 27B–30B models across dual Turing GPUs via tensor parallelism, AD/LDAPS login, zero cloud dependency. |
| **[YaYan-AI](https://github.com/wu840407/YaYan-AI)** | Offline multi-dialect speech recognition that routes each segment to a dialect-specialised engine — 22.3% CER versus 37.6% for Whisper alone on a public benchmark; speaker diarization and character-level timestamps. |
| **[yolov5-parallel](https://github.com/wu840407/yolov5-parallel)** | Multi-GPU parallelized YOLOv5 training and inference pipeline. |
| **[MultiBodyCuboids](https://github.com/wu840407/MultiBodyCuboids)** | M.S. thesis — multi-body motion segmentation for arbitrary numbers of disordered 3D point sets. |
| **[openclaw-agents](https://github.com/wu840407/openclaw-agents)** | Autonomous LLM agents — OODA decision support, scheduled briefings, human-in-the-loop safety gates. |

---

### 🛠 Tech Stack

**LLM Inference** `vLLM` · `llama.cpp` · `quantization (AWQ / 4-bit)` · `tensor parallelism` · `KV-cache sizing` · `FlashInfer` · `TensorRT-LLM`

**ML & Languages** `PyTorch` · `HuggingFace` · `CUDA` · `Python` · `C++`

**Infrastructure** `Docker` · `Linux` · `Kafka` · `Elasticsearch` · `PostgreSQL` · `AWS`

### 🎓 Background
M.S. CS @ NYCU · AWS Solutions Architect – Associate · CEH · CompTIA Security+ / Network+ · HITCON participant

### 📫 Contact
wu840407@gmail.com — open to **AI infrastructure / LLM inference / ML systems** roles
