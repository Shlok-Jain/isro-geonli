<div align="center">
<img src="https://i.ibb.co/n8kcfR4T/Screenshot-2025-12-05-085957.png" alt="Screenshot-2025-12-05-085957" border="0">

---

**TRINETRA**

TRINETRA is an AI-powered conversational platform designed for Geospatial Natural Language Interpretation (GeoNLI) across remote sensing imagery of multiple modalities, including optical, False Color Composite (FCC), and Synthetic Aperture Radar (SAR). It supports three core tasks captioning, grounding, and visual question answering to deliver clear, context-aware insights directly tied to geospatial data. Alongside these core capabilities, TRINETRA offers AgriChat for agriculture specific queries and GEO Compare for temporal comparison, allowing users to analyze and interpret changes between two images of the same location over time.

</div>

---

## Repository Structure

```txt
├── TRINETRA
├── backend
├── deployment_script.sh
└── README.md
```
---

## Pre-requisite
1. Ensure the system has Node.js v22.18.0 installed.
2. Ensure the system has Python v3.12.4 installed.
   
## Quick Start
**Steps**

1. The repo has 2 folders, 'TRINETRA' and 'backend'.
2. Both have their individual README.md with instructions well explained.
3. Follow the instructions for both to get your app ready.

**Steps to run deployment script**
Run the command:
```bash
./deployment_script.sh
```
---

## License & Acknowledgments

This project integrates multiple open-source models and libraries. Each component retains its original license:

- **Qwen3** -  Licensed under Apache 2.0, allowing for free commercial use, modification, and distribution.
- **LLaMA 3.1** - Governed by the LLaMA 3.1 Community License, which permits commercial use and redistribution subject to user cap restrictions and attribution.
- **YOLO v11** - Released under the AGPL-3.0 license, requiring any derivative open-source software to use the same license; enterprise use requires a separate commercial license.
- **SAM 2.1** - Both code and model weights are released under the permissive Apache 2.0 license.
- **SAM 3** - Distributed under a custom Meta license that grants a non-exclusive, royalty-free license for use and redistribution, subject to specific attribution and compliance terms.
- **RemoteCLIP** - Licensed under Apache 2.0, allowing for free commercial use, modification, and distribution.

Please refer to individual documentation files for specific citations and acknowledgments.

---
