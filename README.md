# SAGE
The data and defense methods used in our ACL 2025 (Findings) paper "[Why Not Act on What You Know? Unleashing Safety Potential of LLMs via Self-Aware Guard Enhancement](https://arxiv.org/abs/2505.12060)".

![](SAGE.png)


## 📝 Abstract
Large Language Models (LLMs) have shown impressive capabilities across various tasks but remain vulnerable to meticulously crafted jailbreak attacks. In this paper, we identify a critical safety gap: while LLMs are adept at detecting jailbreak prompts, they often produce unsafe responses when directly processing these inputs. Inspired by this insight, we propose SAGE (Self-Aware Guard Enhancement), a training-free defense strategy designed to align LLMs' strong safety discrimination performance with their relatively weaker safety generation ability. SAGE consists of two core components: a Discriminative Analysis Module and a Discriminative Response Module, enhancing resilience against sophisticated jailbreak attempts through flexible safety discrimination instructions. Extensive experiments demonstrate SAGE's effectiveness and robustness across various open-source and closed-source LLMs of different sizes and architectures, achieving an average 99% defense success rate against numerous complex and covert jailbreak methods while maintaining helpfulness on general benchmarks. We further conduct mechanistic interpretability analysis through hidden states and attention distributions, revealing the underlying mechanisms of this detection-generation discrepancy. Our work thus contributes to developing future LLMs with coherent safety awareness and generation behavior.

## 📧 Contact

If you have any questions about our work, please feel free to contact us via the following email:

Peng Ding: dingpeng@smail.nju.edu.cn

Jun Kuang: jkuang@stu.ecnu.edu.cn

Shujian Huang: huangsj@nju.edu.cn

## 📚 Citation

If you find this work useful in your own research, please feel free to leave a star⭐️ and cite our paper:

```bibtex
@article{ding2025not,
  title={Why Not Act on What You Know? Unleashing Safety Potential of LLMs via Self-Aware Guard Enhancement},
  author={Ding, Peng and Kuang, Jun and Wang, Zongyu and Cao, Xuezhi and Cai, Xunliang and Chen, Jiajun and Huang, Shujian},
  journal={arXiv preprint arXiv:2505.12060},
  year={2025}
}
```
