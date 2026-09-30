# Transition-Aware Credit Assignment in Agentic Learning for LLM Reasoning

Official repository for **Transition-Aware Credit Assignment (TACA)**, accepted at **NeurIPS 2026**.

> 🚧 **Coming soon!** The paper and code are currently being prepared for release.

## Overview

Multi-turn agentic reinforcement learning enables language models to reason with tools, but terminal correctness rewards can assign the same credit to useful and unhelpful tool interactions. This transition-blind credit assignment can suppress useful tool use and destabilize training, even when tool-call frequency remains nearly unchanged.

**TACA** makes credit assignment sensitive to tool-use transitions through three complementary mechanisms:

- **Subset-Lift:** offsets negative aggregate credit on tool-related token subsets while preserving beneficial tool-use credit.
- **Decision-Contrast:** localizes tool-versus-direct action credit at matched decision prefixes.
- **Support-Anchor:** keeps valid tool actions in support, stabilizing learning when tool use is sparse.

## Release Status

- [ ] Paper
- [ ] Code

Links and usage instructions will be added here as the release becomes available. Stay tuned, and star this repository to follow the project!

## Citation

If you find TACA useful in your research, please consider citing our work:

```bibtex
@inproceedings{lu2026taca,
  title     = {Transition-Aware Credit Assignment in Agentic Learning for {LLM} Reasoning},
  author    = {Xiangyu Lu and Zhanke Zhou and Jiazhe Ning and Chentao Cao and Jiangchao Yao and Bo Han},
  booktitle = {Advances in Neural Information Processing Systems},
  year      = {2026}
}
```
