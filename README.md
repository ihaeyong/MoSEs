# Mixtures of SubExperts (MoSEs)
## Mixtures of SubExperts (MoSEs): A Breakthrough in Continual Learning for LLMs

Adapting Large Language Models (LLMs) to a continuous stream of tasks is challenging - especially due to catastrophic forgetting. Current PEFT (Parameter-Efficient Fine-Tuning) methods face a clear trade-off:
- Reusing a single parameter set → High forgetting
- Assigning separate parameters per task → No forgetting but linear model growth and limited knowledge transfer

## ✨ Our Solution: Mixtures of SubExperts (MoSEs)

 MoSEs is a novel continual learning framework designed to achieve minimal forgetting, efficient scalability, and effective knowledge reuse.
 
🔹 **Sparse SubExpert Architecture**:
 A sparse Mixture of SubExperts is integrated into transformer layers, guided by a task-specific routing mechanism.
 
🔹 **Minimal Forgetting**: 
 Dedicated SubExperts preserve and isolate knowledge from previous tasks, reducing interference.

🔹 **Efficient Knowledge Transfer**:
 The router dynamically selects and combines previously learned sparse parameters to accelerate learning on new tasks.

🔹 **Scalable Model Growth**:
 Model capacity increases sublinearly, enabling substantial savings in memory and computation.

## 🏆 State-of-the-Art Results on the TRACE Benchmark

Our experiments demonstrate that MoSEs significantly outperforms existing continual learning techniques in:

 1️⃣ Knowledge Retention (minimal forgetting)
 
 2️⃣ Scalability across a large number of tasks
 
 3️⃣ Overall efficiency in parameters and computation
 
MoSEs delivers SOTA performance with dramatically improved efficiency - redefining what’s possible in continual LLM adaptation.

Linked Paper: Mixtures of SubExperts for Large Language Continual Learning (https://lnkd.in/gyTTCTQZ)

```
@misc{kang2025MoSEs,
      title={Mixtures of SubExperts for Large Language Continual Learning}, 
      author={Haeyong Kang},
      year={2025},
      eprint={2511.06237},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2511.06237}, 
}
```
