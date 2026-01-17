# LLMs-Space

<p align="center" width="300">Welcome to my LLMs project collection!  </p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" width="200"/>
</p>

This space documents my journey toward becoming a LLM Engineer by building real, production-ready systems.
Showcasing my projects in Large Language Models: Fine-Tuning, Optimization & Applied LLM Techniques

## **Featured Projects**

### **1. Fine-Tuning LLaMA 2–7B with QLoRA (1k Samples)**

 **Project Link** : 
[![View on GitHub](https://img.shields.io/badge/QLoRA-Fine--Tuning-green?logo=github)](https://github.com/Hedi-Bk/Fine_Tune_Llama2_7b)


Fine-tuning of the LLaMA 2–7B model using the **QLoRA** method:

- Base model quantized in **NF4**
- Full-precision **LoRA adapters**
- **Supervised Fine-Tuning (SFT)** on a 1k curated dataset
- We used **Hugging Face** for the Fine Tune

### Training Metrics Overview

| Metric            | Value           |
| ----------------- | --------------- |
| **Training Loss** | **1.36**        |
| **Global Steps**  | **250**         |
| **Runtime**       | **1634 s**      |
| **Samples / sec** | **0.612**       |
| **Steps / sec**   | **0.153**       |
| **Total FLOPs**   | **8.75 × 10¹⁵** |

---

### **2. Fine-Tuning Phi-3-Mini with QLoRA & Unsloth (500 Samples)**

**Project Link** : [![View on GitHub](https://img.shields.io/badge/QLoRA-Fine--Tuning-green?logo=github)](https://github.com/Hedi-Bk/Fine-Tuning-Phi-3-with-QLoRA-Unsloth)

Specialized fine-tuning of the **Microsoft Phi-3-Mini** model for structured data extraction:

- **Optimization**: Leveraged **Unsloth** for 2x faster training and 70% less VRAM usage.
- **Method**: **QLoRA** (4-bit quantization) with Rank-64 adapters.
- **Task**: Supervised Fine-Tuning (SFT) for **HTML-to-JSON** data extraction.
- **Efficiency**: Fully compatible with free-tier GPU (Tesla T4) via Google Colab.
- **Inference**: Merged model exported to 16-bit for seamless production deployment.

### Training Metrics Overview

| Metric | Value |
| --- | --- |
| **Model** | **Phi-3-Mini** |
| **Rank (r)** | **64** |
| **Alpha** | **128** |
| **Dataset Size** | **500 Samples** |
| **Quantization** | **4-bit (NF4)** |
| **Library** | **Unsloth** |

####  Feel free to explore the code, experiment with the notebooks, and adapt the ideas for your own projects!
<p align="center">
      <img src="https://github.com/user-attachments/assets/d7c0ef31-c3fc-44a3-adc6-539426cf9635" alt="icon" width="64" height="64">
</p>  

