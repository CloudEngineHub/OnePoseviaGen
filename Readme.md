<div align="center">
<h1>One View, Many Worlds: Single-Image to 3D Object Meets Generative Domain Randomization for One-Shot 6D Pose Estimation</h1>

<a href="https://arxiv.org"><img src='https://img.shields.io/badge/arXiv-Paper-red?logo=arxiv&logoColor=white' alt='arXiv'></a>
<a href="https://gzwsama.github.io/OnePoseviaGen.github.io/"><img src="https://img.shields.io/badge/Project_Page-green" alt="Project Page"></a>
<a href='https://huggingface.co/spaces/ZhengGeng/OnePoseviaGen'><img src='https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Live_Demo-blue'></a>

<p class="text-lg">
   <a href="https://github.com/GZWSAMA" class="text-white hover:underline hover:text-gray-300 transition-colors duration-200">Zheng Geng</a>,
   <a href="https://bigcileng.github.io/" class="text-white hover:underline hover:text-gray-300 transition-colors duration-200">Nan Wang</a>,
   <a href="https://daniellli.github.io/" class="text-white hover:underline hover:text-gray-300 transition-colors duration-200">Shaocong Xu</a>,
   <a href="https://scholar.google.com/citations?user=V-YdQiAAAAAJ&hl=zh-CN" class="text-white hover:underline hover:text-gray-300 transition-colors duration-200">Bohan Li</a>,
   <a href="https://frozenburning.github.io/" class="text-white hover:underline hover:text-gray-300 transition-colors duration-200">Zhaoxi Chen</a>,
   <a href="https://hugoycj.github.io/" class="text-white hover:underline hover:text-gray-300 transition-colors duration-200">Chongjie Ye</a>,
   <a href="http://pengsida.net/" class="text-white hover:underline hover:text-gray-300 transition-colors duration-200">Sida Peng</a>,
   <a href="https://sites.google.com/view/fromandto" class="text-white hover:underline hover:text-gray-300 transition-colors duration-200">Hao Zhao</a>
</p>
</div>

---

![Manipulation](assets/manipulation.gif)

---

![Instruction](assets/instruction.gif)

---

## **TODO:**
- [ ] Release Polished Paper
- [ ] Release Evaluation Code
- [ ] Release Training Code
---

## ⚙️ Installation

### Quick Setup Using `setup.sh`

To streamline the setup process, we provide a `setup.sh` script that automates all installation steps. Follow these instructions to get started:

### Prerequisites

Before running the `setup.sh` script, ensure you have the following prerequisites installed on your system:

- Python 3.11+
- Conda (recommended)
- Basic build tools (`git`, `make`, `cmake`, etc.)

### Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/GZWSAMA/OnePoseviaGen.git
   cd OnePoseviaGen
   ```

2. **Make the `setup.sh` script executable:**

   ```bash
   chmod +x setup.sh
   ```

3. **Run the `setup.sh` script:**

   It is recommended to run this script within a fresh conda environment. Here's how you can create and activate a new environment before running the script:

   ```bash
   conda create -n OnePoseviaGen python=3.11 -y
   conda activate OnePoseviaGen
   ./setup.sh
   ```

   The script will handle:
   - Installing PyTorch with CUDA support.
   - Installing required dependencies.
   - Cloning and installing external extensions.
   - Building FoundationPose.
   - Installing local packages in editable mode.
   - Downloading pretrained weights.
   - Patching the transformers library.

4. **Verify the setup:**

   After running the script, verify that all dependencies are correctly installed and the necessary files are downloaded.

5. **Web demo:**

   ```bash
   python app.py
   ```
---

## Troubleshooting
[Indices should be on the same device](https://github.com/GZWSAMA/OnePoseviaGen/issues/6)

[Can't convert cuda:0 device type tensor to numpy](https://github.com/GZWSAMA/OnePoseviaGen/issues/7)

---
## 📚 Citation

If you find this work useful, please cite:

```bibtex
TODO
```

