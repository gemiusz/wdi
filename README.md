# GenAI on Your Own Terms – Running Open LLMs with Ollama on Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ontaptom/wdi/blob/main/gemma3_colab.ipynb)

## About this repo 

Originally I have created this repository for a specific talk, but currently I'm re-using the same repo to add some additional Colab notebooks related to Open LLMs ;) Cheers!


## Overview

This repository contains the companion Google Colab notebook (`gemma3_colab.ipynb`) for the talk **"GenAI on Your Own Terms – Open Large Language Models in Action"** presented at Warszawskie Dni Informatyki 2025.

The notebook provides a practical, hands-on demonstration of how to:
*   Set up **Ollama** within a Google Colab environment.
*   Leverage Google Colab's **free T4 GPU** resources.
*   Download and run **open Large Language Models (LLMs)**, specifically **Gemma 3 4B** by default.
*   Interact with the LLM for tasks like text generation and **image analysis**.
*   Do all of this **for free**, without needing your own dedicated hardware (within Colab's usage limits).

This project aims to empower users to experiment with powerful open LLMs, maintaining control over their data flow and avoiding unpredictable costs associated with proprietary models.

## About the Talk

**GenAI on Your Own Terms – Open Large Language Models in Action**
*(Warszawskie Dni Informatyki 2025)*

**Abstract:** Generative AI opens up new ways for humans to interact with machines. Its ability to grasp context and deliver relevant responses means users increasingly rely on it for complex tasks, often sharing sensitive or confidential information. Unfortunately, proprietary LLMs introduce unpredictable costs, as each token generated comes with its own price tag. In this session, I'll show you how to practically deploy and leverage open language models within your own infrastructure, maintaining complete control over data flow. Using concrete examples, I'll walk you through the installation, configuration, and integration with your existing systems. Rather than theoretical discussions, we’ll focus on live demonstrations of various real-world scenarios. This session is ideal for anyone looking to deploy and experiment with this technology hands-on.

## Getting Started with the Notebook

1.  **Prerequisites:** You need a Google Account to use Google Colab.
2.  **Open in Colab:** Click the "Open In Colab" badge at the top of this README, or navigate to the `gemma3_colab.ipynb` file in this repository and click the Colab link there.
3.  **Select GPU Runtime:**
    *   Once the notebook is open, go to the menu: `Runtime` -> `Change runtime type`.
    *   In the pop-up window, select `T4 GPU` from the "Hardware accelerator" dropdown.
    *   Click `Save`.
4.  **Run the Cells:** Execute the notebook cells sequentially by clicking the play button next to each cell or using `Shift+Enter`.
5.  **Experiment:** Feel free to modify the prompts, try different models (see below), and explore the capabilities!

**Important Note:** Google Colab provides free resources with usage limits. If you run into quota issues, you may need to wait until the next day or consider Colab Pro.

## Model Information

*   **Default Model:** The notebook uses `gemma3:4b` by default. This is a powerful and efficient model from Google capable of both text and image understanding.
*   **Terms of Use:** Please review the Gemma 3 terms of use: [https://ai.google.dev/gemma/terms](https://ai.google.dev/gemma/terms)
*   **Other Models:** You can easily change the `MODEL_ID` variable in the notebook to try other models available in the Ollama library: [https://ollama.com/library](https://ollama.com/library)
    *   *Note:* If you switch to a model that does not support image input (multimodal capabilities), the image analysis cells will not work.

## What's Next?

The notebook concludes with links to further resources for exploring open LLMs, including cookbooks from Google, Microsoft, Meta, and Mistral, as well as Polish language model projects and Hugging Face learning resources.

## Get in touch

If you want to get in touch, you can find me on linkedin: [https://www.linkedin.com/in/tomaszporozynski/](https://www.linkedin.com/in/tomaszporozynski/)

## License

This project and the accompanying notebook are licensed under the Apache License, Version 2.0. See the license header in the notebook file for details.

---

Enjoy experimenting with open LLMs!
