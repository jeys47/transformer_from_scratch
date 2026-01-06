# A Transformer From Scratch

This project implements a Transformer model from first principles, without using high-level deep learning framework like PyTorch or Tensorflow.

## Objectives
- Understanding how Transformers work internally
- Implement forward and backward passes manually
- Experiment with small sequences and toy data
- Create a clear, well-commented, structured codebase

## Structure
Each notebook covers a specific component :
- 00_overview.ipynb : Project overview and roadmap
- 01_embeddings.ipynb : Token embeddings
- 02_positional_encoding.ipynb : Positional encodings
- 03_attention.ipynb : Scaled dot-product attention
- 04_multihead_attention.ipynb : Multi-head attention
- 05_feed_forward.ipynb : Feed-forward network
- 06_transform_block.ipynb : Encoder/Decoder block
- 07_transform_model.ipynb : Full Transform model
- 08_training_loop.ipynb : Training loop on toy data
- experiments/ : Experiments and tests

## Note
This project is educational and research-oriented.
The focus is **understanding** rather than performance.