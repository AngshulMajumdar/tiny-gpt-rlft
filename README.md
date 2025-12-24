# Tiny GPT from Scratch + RL Fine-Tuning (Colab)

End-to-end implementation of a decoder-only GPT trained **from scratch**
on TinyStories + WikiText, with Byte-Level BPE tokenization, resume-safe
training, and KL-regularized REINFORCE fine-tuning.

## Highlights
- No pretrained models
- BBPE tokenizer
- RoPE + RMSNorm + SwiGLU
- Drive-based checkpointing
- RL fine-tuning (policy + frozen reference)

Built and run on Google Colab (T4).
