# DIALECTIC: LLM-Based Multi-Agent System for Startup Evaluation

[![Conference](https://img.shields.io/badge/EACL%202026-Industry%20Track-blue)](https://2026.eacl.org/)
[![Paper](https://img.shields.io/badge/Paper-PDF-red)](./paper.pdf)

## 📄 Paper

**Accepted at:** EACL 2026 Industry Track

[**Download Full Paper (PDF)**](./paper.pdf)

---

## 🎯 Overview

**DIALECTIC** is an LLM-based multi-agent system designed to help venture capital (VC) investors efficiently evaluate startup investment opportunities. The system addresses a critical challenge in the VC industry: investors face an overwhelming number of opportunities but can only invest in a small fraction, with even fewer ultimately succeeding.

### The Challenge

Early-stage screening of investment opportunities is constrained by:
- **Limited investor bandwidth** - VCs can only thoroughly evaluate so many deals
- **Quality vs. quantity tradeoff** - More diligence per deal means fewer opportunities assessed
- **High failure rates** - Most investments don't succeed, making initial screening crucial

### Our Solution

DIALECTIC eases this tradeoff through an automated, systematic evaluation approach that combines:

1. **Factual Knowledge Gathering** - Collects comprehensive information about startups
2. **Hierarchical Organization** - Structures facts into an organized question tree
3. **Argument Synthesis** - Generates natural-language arguments for and against investment
4. **Simulated Debate** - Iteratively critiques and refines arguments to surface the most convincing points
5. **Decision Scoring** - Produces numeric scores enabling efficient opportunity ranking and prioritization

---

## 🔬 Methodology

### System Architecture

The DIALECTIC system operates through four key stages:

```
1. Data Collection
   └─> Gather factual knowledge about the startup

2. Knowledge Organization
   └─> Structure information into hierarchical question tree

3. Argument Generation
   └─> Synthesize pro and con investment arguments

4. Iterative Refinement
   └─> Simulate debate to critique and improve arguments
   └─> Generate final decision scores
```

### Key Features

- **Multi-Agent Framework**: Leverages multiple LLM agents with specialized roles
- **Structured Reasoning**: Uses hierarchical question trees for systematic evaluation
- **Dialectical Process**: Simulated debate refines arguments through criticism
- **Quantitative Output**: Numeric scores enable ranking of opportunities
- **Efficient Screening**: Reduces time needed for initial deal evaluation

---

## 📊 Evaluation

### Backtesting Results

We evaluated DIALECTIC through backtesting on real investment opportunities from **five venture capital funds**.

**Key Finding**: DIALECTIC matches the precision of human investors in identifying promising opportunities, demonstrating its potential as a screening tool for early-stage investment decisions.

*Note: Full results and detailed analysis are available in the paper.*

---

## 🎓 Citation

If you use this work in your research, please cite:

```bibtex
@inproceedings{dialectic2026,
  title={DIALECTIC: An LLM-Based Multi-Agent System for Startup Evaluation},
  booktitle={Proceedings of the 2026 Conference of the European Chapter of the Association for Computational Linguistics: Industry Track},
  year={2026},
  publisher={Association for Computational Linguistics}
}
```

---

## 📚 Paper Access

The full paper is included in this repository as `paper.pdf` and contains:

- Detailed system architecture and implementation
- Complete methodology and algorithms
- Comprehensive evaluation results
- Comparative analysis with human investor decisions
- Discussion of limitations and future work
- Extensive related work review

---

## 🏢 Industry Applications

### Potential Use Cases

- **Deal Flow Screening**: Rapidly evaluate large volumes of investment opportunities
- **Due Diligence Support**: Structured framework for comprehensive startup analysis
- **Portfolio Management**: Consistent evaluation methodology across opportunities
- **Decision Documentation**: Natural-language arguments provide audit trail
- **Team Alignment**: Shared framework for discussing investment decisions

### Target Users

- Venture capital firms and angel investors
- Corporate venture capital (CVC) teams
- Accelerators and incubators
- Investment analysts and associates
- Startup evaluation platforms

---

## 🔑 Key Contributions

1. **Novel Architecture**: First multi-agent LLM system specifically designed for VC evaluation
2. **Dialectical Approach**: Innovative use of simulated debate for argument refinement
3. **Real-World Validation**: Backtesting on actual investment data from multiple VC funds
4. **Practical Tool**: Production-ready system that addresses real industry pain points
5. **Hybrid Output**: Combines interpretable arguments with quantitative rankings

---


## ⚠️ Limitations and Ethical Considerations

As discussed in the paper, users should be aware of:

- **Augmentation not Replacement**: Designed to assist, not replace, human judgment
- **Data Dependencies**: Quality depends on available information about startups
- **Model Limitations**: Subject to LLM capabilities and potential biases
- **Domain Specificity**: Trained and validated on VC investment context
- **Decision Accountability**: Final investment decisions remain human responsibility

---

## 📬 Contact

For questions about the paper, methodology, or potential collaborations, please refer to the contact information provided in the paper.

---

## 📖 License

Please refer to the paper for information about data usage and licensing.

---

## 🙏 Acknowledgments

We thank the five venture capital funds that provided anonymized historical data for backtesting and validation of our system.

---

**Note**: This research was presented at the EACL 2026 Industry Track, demonstrating practical applications of natural language processing and large language models in the venture capital domain.
