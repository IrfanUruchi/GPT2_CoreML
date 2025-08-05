# GPT-2 Core ML Model

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=for-the-badge&logo=github)](https://github.com/IrfanUruchi/GPT2_CoreML)
[![Model Weights](https://img.shields.io/badge/🤗-Model_Weights-FFD21F?style=for-the-badge)](https://huggingface.co/Irfanuruchi/GPT2-CoreML)
[![License](https://img.shields.io/badge/License-OpenAI_Model_License-blue.svg?style=for-the-badge)](https://github.com/openai/gpt-2/blob/master/LICENSE)

---

This repository contains a version of OpenAI’s GPT-2 language model converted to Core ML format for efficient on-device inference on iOS and macOS.

## Model Details

- **Base model:** [OpenAI GPT-2](https://github.com/openai/gpt-2)
- **Conversion tool:** [coremltools](https://github.com/apple/coremltools)
- **Format:** Core ML (`.mlmodel`)
- **Usage:** Runs entirely offline on Apple devices, no data leaves the device.

---

## License

The original GPT-2 model is licensed under the [OpenAI Model License]([LICENSE]((https://github.com/openai/gpt-2/blob/master/LICENSE)).  
**Do not use this model for illegal, harmful, or deceptive purposes, as outlined in the license.**

---

## Attribution

- Convertion tools by Apple [coremltools](https://github.com/apple/coremltools)
- GPT-2 by OpenAI ([GitHub](https://github.com/openai/gpt-2))
- Core ML conversion by Irfan

---

## Limitations and considerations

- The model may generate biased or inappropriate content reflecting its training data.
- Performance and output may differ slightly from the original GPT-2 due to conversion and optimization.
- Intended for research, experimentation, and on-device applications on Apple platforms.
- Not suitable for high-stakes or sensitive use cases without additional safeguards.

---

## Contribution and feedback

Contributions, issues, and feature requests are welcome! Feel free to open a GitHub issue or pull request.
