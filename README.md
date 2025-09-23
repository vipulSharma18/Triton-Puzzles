# Triton Puzzles
w/ [Tejas Ramesh](https://tejas3070.github.io/) and [Keren Zhou](https://www.jokeren.tech/) based on [Triton-Viz](https://github.com/Deep-Learning-Profiling-Tools/triton-viz)

## What I read/watched before attempting these puzzles:
[1] P. Tillet, H. T. Kung, and D. Cox, “Triton: an intermediate language and compiler for tiled neural network computations,” in Proceedings of the 3rd ACM SIGPLAN International Workshop on Machine Learning and Programming Languages, Phoenix AZ USA: ACM, June 2019, pp. 10–19. doi: 10.1145/3315508.3329973.        
[2] GPU MODE, Lecture 14: Practitioners Guide to Triton, (Apr. 16, 2024). Accessed: Sept. 16, 2025. [Online Video]. Available: https://www.youtube.com/watch?v=DdTsX6DQk24        
[3] K. Sharma, “GPU Mode - Triton Internals Talk,” Kapil Sharma. Accessed: Sept. 22, 2025. [Online]. Available: https://kapilsh.github.io/posts/gpu-mode-triton-internals-talk/        


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/github/srush/Triton-Puzzles/blob/main/Triton-Puzzles.ipynb](https://colab.research.google.com/drive/1PL7_yXjF2muR1WcU-ktdVoNOE884C1im?usp=sharing))

Programming for accelerators such as GPUs is critical for modern AI systems.
This often means programming directly in proprietary low-level languages such as CUDA. [Triton](https://github.com/openai/triton/) is an alternative open-source language that allows you to code at a higher-level and compile to accelerators like GPU.

Coding for Triton is very similar to Numpy and PyTorch in both syntax and semantics. However, as a lower-level language there are a lot of details that you need to keep track of. In particular, one area that learners have trouble with is memory loading and storage which is critical for speed on low-level devices.

This set is puzzles is meant to teach you how to use Triton from first principles in an interactive fashion. You will start with trivial examples and build your way up to real algorithms like Flash Attention and Quantized neural networks. These puzzles **do not** need to run on GPU since they use a Triton interpreter.

Discord: https://discord.gg/gpumode #triton-puzzles

![image](https://github.com/srush/Triton-Puzzles/assets/35882/3e18a47d-1311-43d0-a025-ed1f593f919e)



If you are into this kind of thing, this is 7th in a series of these puzzles.

* https://github.com/srush/gpu-puzzles
* https://github.com/srush/tensor-puzzles
* https://github.com/srush/autodiff-puzzles
* https://github.com/srush/transformer-puzzles
* https://github.com/srush/GPTworld
* https://github.com/srush/LLM-Training-Puzzles
