
# VietCheckMed: Explainable Regulatory Compliance Checking for Medical Advertisements

Official implementation of the paper: **"VietCheckMed: Explainable Regulatory Compliance Checking for Medical Advertisements on Vietnamese Social Media"**, accepted at the **AAAI 2026 Main Track** (Singapore).

## 📢 Latest News

* **October 2025**: 🎉 VietCheckMed has been accepted to AAAI 2026 Main Track!

* **September 2025**: Release of the `VietAestheticAds` benchmark, the first expert-validated dataset for Vietnamese medical regulatory checking.

## 🚀 Project Overview

VietCheckMed introduces a paradigm shift from traditional fact-checking to **Authorization-based Regulatory Compliance Checking**. It leverages an **Agentic RAG pipeline** to verify if medical advertisements on social media possess valid legal authorization according to Ministry of Health (MOH) and State Bank of Vietnam (SBV) regulations.

### Key Scientific Contributions:

1. **Authorization-based Task Definition**: A novel NLP task focusing on legal authorization rather than just factual veracity.

2. **VietAestheticAds Benchmark**: A comprehensive dataset of Vietnamese medical advertisements with multi-level expert annotations.

3. **Explainable Agentic Pipeline**: An architecture built on **LangGraph** that provides step-by-step reasoning grounded in regulatory evidence.

## 🏗️ System Architecture

VietCheckMed utilizes a state-of-the-art multi-agent system to simulate the workflow of a legal compliance expert.

* **Retrieval Engine**: Optimized dense retrieval for Vietnamese legal corpora.

* **Reasoning Agents**: Chain-of-Thought (CoT) agents that evaluate ads against specific articles of law.

* **XAI Module**: Generates human-readable verdicts with explicit citations to legal documents.

## 🛠️ Installation & Setup

### Prerequisites

* Python 3.9 or higher

* CUDA-enabled GPU (recommended for local inference)

* Google Gemini API Key or local LLM setup

### Standard Installation

```bash
# Clone the repository
git clone [https://github.com/your-org/VietCheckMed.git](https://github.com/your-org/VietCheckMed.git)
cd VietCheckMed

# Create a clean environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install core dependencies
pip install --upgrade pip
pip install -r requirements.txt

```

## 🖋️ Citation

If you utilize this framework or the dataset in your research, please cite our AAAI 2026 paper:

```bibtex
@inproceedings{vietcheckmed2026,
  title={VietCheckMed: Explainable Regulatory Compliance Checking for Medical Advertisements on Vietnamese Social Media},
  author={Nguyen Thanh Tam, Khanh Quoc Tran, Dat Thanh Pham, Truong Phu Le, Nguyen Hoang Gia Han, Binh T. Nguyen},
  booktitle={Proceedings of the 40th AAAI Conference on Artificial Intelligence (AAAI-26)},
  year={2026},
  publisher={AAAI Press},
  address={Singapore}
}

```

## 🤝 Contributing

We welcome contributions from the community. Please read our CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.

## 🛡️ Ethics & Disclaimer

VietCheckMed is a research tool designed to assist in regulatory oversight. It is **not** a replacement for legal counsel or official government decisions. Users should verify AI-generated verdicts with primary legal sources.

## 📄 License

This project is licensed under the **MIT License** - see the LICENSE file for details.

© 2026 VietCheckMed Research Team. Supported by AAAI
