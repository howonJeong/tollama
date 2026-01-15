# Project: TinyLLaMA Reconstruction

**"From Tensors to TinyLLaMA"** 파이토치 기초부터 LLM 아키텍처까지, 단계별로 직접 구현하며 모델의 내부 메커니즘을 마스터하는 교육용 레포지토리입니다.

---

### 🚀 Learning Roadmap

1.  **PyTorch Foundation** - 텐서 연산 마스터
2.  **NanoGPT (by Andrej Karpathy)** - Transformer 아키텍처 및 Self-Attention의 기본 구현
3.  **llm.c (by Andrej Karpathy)** - C/CUDA 관점에서의 저수준 최적화 및 GPT-2 구조 학습
4.  **TinyLLaMA Implementation** - Llama-2 기반 1.1B 파라미터 모델 아키텍처 최종 구현 (RoPE, RMSNorm, SwiGLU)

---

### 🛠 Tech Stack
- **Framework:** PyTorch, NumPy
- **Models:** NanoGPT, llm.c, TinyLLaMA
- **Environment:** MacBook Pro (MPS) & Kaggle (GPU)

---

### 🔄 Workflow
```bash
# Pull from Kaggle
kaggle kernels pull howonmjeong/pratices -m

# Push to Kaggle
kaggle kernels push -p .
