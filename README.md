# Paper: *A Methodology to Design Quantized Deep Neural Networks for Automatic Modulation Recognition*

This repository contains the information and algorithms presented in the paper *A Methodology to Design Quantized Deep Neural Networks for Automatic Modulation Recognition*.
![Automatic Modulation Recognition](https://github.com/DGoezSanchez/A-Methodology-to-Design-Quantized-Deep-Neural-Networks-for-Automatic-Modulation-Recognition/blob/main/Automatic%20Modulation%20Recognition/Figures/Plot_all_solutions.png)


The [Brevitas library](https://github.com/Xilinx/brevitas/tree/master) was utilized for efficient neural network quantization, playing a critical role in the implementation of this work.  
Moreover, the structure and methodology of this project were inspired by the [brevitas-radioml-challenge-21](https://github.com/Xilinx/brevitas-radioml-challenge-21) repository.

---

## Prerequisites

To set up the environment and run this project, follow the steps below:

1. **Install Docker Engine**  
   - Use the convenient installation script: [get.docker.com](https://get.docker.com)  
   - For detailed installation instructions, refer to: [docs.docker.com/engine/install/](https://docs.docker.com/engine/install/)  

2. **Enable Docker Without `sudo` (Optional)**  
   - To avoid using `sudo` with Docker commands, follow these [post-installation steps](https://docs.docker.com/engine/install/linux-postinstall/) to add your user to the `docker` group.

3. **Enable GPU-Accelerated Training (Recommended)**  
   - Install the latest NVIDIA driver.  
   - Set up the NVIDIA Container Toolkit by following the instructions here: [github.com/NVIDIA/nvidia-docker](https://github.com/NVIDIA/nvidia-docker).

---

## Citation

If you use this work, please cite the following paper:

Góez, D., Soto, P., Latré, S., Gaviria, N., & Camelo, M. (2022). *A methodology to design quantized deep neural networks for automatic modulation recognition*. Algorithms, 15(12), 441.  
[DOI Link (https://doi.org/10.3390/a15120441 )]
