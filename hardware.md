# Hardware Audit

**Audit date:** 2026-11-16  
**Environment:** Ubuntu 24.04.3 LTS on WSL2

## CPU
- Model: 11th Gen Intel Core i5-11300H @ 3.10GHz
- Architecture: x86_64
- Physical cores: 4
- Logical processors: 8
- Sockets: 1

## Memory
- RAM: 7.6 GiB
- Available at audit time: 6.9 GiB
- Swap: 2.0 GiB

## Storage
- WSL filesystem: 1007 GiB
- Used at audit time: 14 GiB
- Available at audit time: 942 GiB

## GPU
- NVIDIA GPU: Not available
- CUDA: Not available
- PyTorch configuration: CPU-only

## Research Constraints and Decisions
- Use CPU-based development and testing by default.
- Keep experiments small enough to fit available memory.
- Use reduced datasets, smaller models, and smaller batch sizes when necessary.
- Do not purchase hardware or rent cloud GPUs until a specific experiment requires them.
- Reassess compute requirements when beginning larger training experiments.
