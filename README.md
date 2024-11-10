# GPT-2 from Scratch

This repository contains an implementation of the **GPT-2** architecture, built from the ground up with inspiration from **Andrej Karpathy's work**. Although the code is my own, it closely follows the architecture details outlined and implemented by Andrej Karpathy for the original GPT-2 model. 

## About This Project

This project implements the GPT-2 model architecture from scratch. It does load pre-trained weights from Huggingface, making it easy to experiment with various GPT-2 configurations. Replication of the structure and design of GPT-2 while allowing for customizable configurations was the goal.

### Key Features
- **GPT-2 Architecture**: Recreated in detail based on the OpenAI GPT-2 model specifications and the research paper **Attention is all you need**.
- **Pre-trained Weight Loading**: Supports loading model weights from Hugging Face. By adjusting the `GPTConfig` values, you can load weights for different versions of GPT-2

### Prerequisites
- Python (version >= 3.6)
- PyTorch
- Transformers

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/R2D2-08/GPT2.git
   cd GPT2
### References
- Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., Kaiser, Ł., & Polosukhin, I. (2017). [Attention Is All You Need](https://arxiv.org/abs/1706.03762). *Advances in Neural Information Processing Systems*, 30, 5998-6008.
- Andrej Karpathy's guide on the implementation [Let's Build GPT-2 from scratch](https://www.youtube.com/watch?v=l8pRSuU81PU)
