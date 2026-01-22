# Nate Willis

### Systems & Performance Engineer | High-Performance Computing (HPC)
I focus on the hardware-software boundary, specifically focusing on optimizing and managing hardware constraints.

---

## Featured Project: [Lighter++](https://github.com/21NWillis/Lighterpp)
A zero-dependency C++/CUDA inference engine for Large Language Models (Llama 2 and 3).

* **From-Scratch Architecture:** Built without PyTorch or TensorFlow to ensure total control over tensor operations and memory management.
* **Performance Optimization:** Saturates hardware bandwidth using **Warp-level reductions**, **Vectorized memory access**, **A Fused Sampling Kernel**, **HFMA2 Instrinsics**, and **Dynamic shared memory**. Achieved 23x speedup over basic CPU implementation and 2.3x speedup over basic Llama3 inference (RTX 3070).
* **Status:** Currently implementing **Int4 Quantization**.

---

## Technical Stack
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)

---

## Currently Exploring
* **Fused Kernels:** Fusing multiple kernels into a single kernel launch to reduce launch overhead and keep data in GPU registers rather than global VRAM.
* **Quantization:** Sub-8-bit weight packing and kernel fusion.

---

## Connect with Me
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nathaniel-willis-317052279/)
[![Twitter/X](https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/NwillisML)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:nlwillis@gmail.com)

![Nate's Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=21NWillis&theme=dracula&hide_border=true)
