# Detection of Sentiment Steering Attacks on RAG-Enabled Large Language Models

## Overview

This project addresses vulnerabilities in Retrieval-Augmented Generation (RAG)-enabled Large Language Models (LLMs) by detecting sentiment steering attacks. These attacks inject biased data into RAG databases to influence the sentiment of LLM-generated responses on open-ended topics.

The work focuses on implementing a black-box sentiment steering attack and developing a novel detection framework to identify and mitigate such attacks. The detection framework achieves a recall of 97.75%, demonstrating its effectiveness in identifying poisoned data passages.

---

## Features

- **Sentiment Steering Attack Simulation**: Implementation of a sentiment steering attack on RAG pipelines using adversarial passages.
- **Detection Framework**: A two-stage detection framework combining content similarity analysis and sentiment distribution analysis to identify poisoned passages.
- **Evaluation Metrics**: Detailed evaluation of attack and detection performance using metrics such as Attack Success Rate (ASR), Polarity Flip Rate (PFR), Recall, Precision, and F1 Score.
- **Dataset**: [WikiASP-OfficeHolder](https://github.com/neulab/wikiasp) dataset for evaluating attacks and detection. ([Download](http://phontron.com/download/wikiasp/OfficeHolder.tar.bz2))

---

## Visualizations

### Attack Framework
![Attack Framework](images/RAG_poison_attack_model.svg)

### Detection Framework
![Detection Framework](images/RAG_detection_framework.svg)
---

## Results

### Attack Performance
- **Attack Success Rate (ASR)**: 81.26%
- **Polarity Flip Rate (PFR)**: 65.21%
- **Mean Sentiment Shift**: 6.08

### Detection Model Performance
- **Recall**: 97.75%
- **Precision**: 80.77%
- **F1 Score**: 88.45%
- **Accuracy**: 83.47%

---
## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
---
## Acknowledgments

This project was completed as part of the **CS F491 Special Project** at **BITS Pilani, Dubai Campus** under the supervision of **Dr. Pranav M. Pawar**. Special thanks to the Computer Science Department for providing guidance and resources.

