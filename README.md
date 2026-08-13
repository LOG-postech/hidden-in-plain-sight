# Hidden in Plain Sight: The Overlooked Significance of Canonical Elements for Extreme LLM Sparsity

Code for our EMNLP 2026 paper.

> **Status: code release in progress — star or watch this repo to be notified.**

We are cleaning up the training and evaluation code and will push it here shortly.
The release will include:

- The progressive sparsification pipeline (second-order saliency, global thresholding, cubic sparsity schedule, warmup + decay training)
- One-shot pruning baselines (Magnitude, Wanda, SparseGPT) and their retrained variants
- Perplexity and zero-shot evaluation scripts
- Configurations reproducing the reported LLaMA-2 and Qwen-3 results

## Paper

*Hidden in Plain Sight: The Overlooked Significance of Canonical Elements for Extreme LLM Sparsity*
Hyeondo Jang, Kwanhee Lee, Dongyeop Lee, Namhoon Lee (POSTECH)

We show that pretrained LLMs retain strong performance far beyond the sparsity levels
usually treated as a practical ceiling — up to 99% unstructured sparsity — once a few
elementary components of the pruning process are applied properly.

## Contact

Questions are welcome via GitHub issues, or by email to
`{hyeondo.jang, kwanhee.lee, dongyeop.lee2, namhoon.lee}@postech.ac.kr`.
