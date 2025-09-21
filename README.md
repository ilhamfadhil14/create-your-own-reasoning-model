# Bandung.py Community Meetup September 2025 - Build Your Own Reasoning Model

<img src="images/deepseek-r1-training-pipeline.png" alt="deepseek-training-pipeline" width="500"/>

## Deskripsi

Repository ini berisi tentang diskusi di forum Bandung.py tentang bagaimana membangun model reasoning dari base model LLM. Referensi utama dari diskusi ini berasal dari paper dengan judul [DeepSeek DeepSeek-R1 incentivizes reasoning in LLMs through reinforcement learning](https://www.nature.com/articles/s41586-025-09422-z). Di dalam repository ini berisi:

- Slide materi
- Notebook contoh implementasi menggunakan Google Colab

## Notes

Waktu training jika menggunakan GPU T4 bisa cukup lama, bisa di adjust parameter `max_step` menjadi lebih kecil.

## Notebook

- GPU T4 <a target="_blank" href="https://colab.research.google.com/drive/1pvvOaKw-EtE3n-Wy7-68K44hLhkwOkTd?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>
- GPU A100 <a target="_blank" href="https://colab.research.google.com/drive/1ps_94n7HP7joqrPQotLLmIA6G3fwQ1qR?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Referensi

- [Hugging Face - Build Reasoning Models](https://huggingface.co/learn/llm-course/en/chapter12/1?fw=pt)
- [Unsloth - Reinforcement Learning (RL) Guide](https://docs.unsloth.ai/basics/reinforcement-learning-rl-guide)
- [Unsloth - Train Your Own Reasoning Model with Unsloth (GRPO)](https://unsloth.ai/blog/r1-reasoning)
- [Prompting Engineering Guide - Chain-of-Thought Prompting](https://www.promptingguide.ai/techniques/cot)
- [Guo, D., Yang, D., Zhang, H. et al. DeepSeek-R1 incentivizes reasoning in LLMs through reinforcement learning. Nature 645, 633–638 (2025)](https://www.nature.com/articles/s41586-025-09422-z)
- [Guo, D., Yang, D., Zhang, H., Song, J., Zhang, R., Xu, R., ... & He, Y. (2025). Deepseek-r1: Incentivizing reasoning capability in llms via reinforcement learning. arXiv preprint arXiv:2501.12948.](https://arxiv.org/abs/2501.12948)
