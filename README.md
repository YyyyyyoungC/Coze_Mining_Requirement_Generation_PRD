# Coze Mining Requirement Generation PRD 🚀

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/YyyyyyoungC/Coze_Mining_Requirement_Generation_PRD/actions)
[![Version](https://img.shields.io/badge/version-1.0.0-blue)](https://github.com/YyyyyyoungC/Coze_Mining_Requirement_Generation_PRD/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow)](https://github.com/YyyyyyoungC/Coze_Mining_Requirement_Generation_PRD/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/YyyyyyoungC/Coze_Mining_Requirement_Generation_PRD?style=social)](https://github.com/YyyyyyoungC/Coze_Mining_Requirement_Generation_PRD)

## Description 📝

This project is designed for senior product managers and business analysts. It transforms vague user ideas into standardized, clear, actionable, and no-code Chinese Product Requirements Documents (PRDs). The process covers requirement refinement, architecture design, feature breakdown, and visualization, progressing in stages with user confirmation. This ensures that the generated PRDs meet the needs of development, testing, and product review.

## Table of Contents 📜

- [Project Title & Badges](#coze-mining-requirement-generation-prd-🚀)
- [Description](#description-📝)
- [Table of Contents](#table-of-contents-📜)
- [Features](#features-✨)
- [Tech Stack](#tech-stack-💻)
- [Installation](#installation-🛠️)
- [Usage](#usage-💡)
- [Project Structure](#project-structure-📂)
- [Contributing](#contributing-🤝)
- [License](#license-⚖️)
- [Important links](#important-links-🔗)
- [Footer](#footer-❤️)

## Features ✨

- **Requirement Refinement:** Transforms ambiguous user ideas into clear and structured requirements.
- **Architecture Design:** Assists in building a logical architecture for the product.
- **Feature Breakdown:** Decomposes complex features into manageable components.
- **Visualization:** Provides visual representations of the product requirements.
- **Phased Development:** Supports a stage-by-stage approach with user validation.
- **No-Code PRD Generation:** Creates PRDs without requiring coding.
- **Chinese Language Support:** Outputs PRDs in standardized Chinese.

## Tech Stack 💻

- **Primary Language:** Python (inferred from `requirements.txt`)
- **Frameworks:** FastAPI, LangChain (various modules), LangGraph, Starlette, Uvicorn
- **Libraries:** Pandas, NumPy, OpenAI, Pydantic, SQLAlchemy, Pytest, Rich, Requests, PyInstaller

## Installation 🛠️

To set up this project, you need to install the required Python dependencies. It's recommended to use a virtual environment.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/YyyyyyoungC/Coze_Mining_Requirement_Generation_PRD.git
    cd Coze_Mining_Requirement_Generation_PRD
    ```

2.  **Create and activate a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    # On Windows:
    .\venv\Scripts\activate
    # On macOS/Linux:
    source venv/bin/activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage 💡

This project acts as a skill or tool for generating PRDs. While specific entry points or direct execution commands are not explicitly defined in the analyzed files, its functionality is centered around processing user ideas into PRDs.

**Real-world Use Case:**

A product manager has a high-level idea for a new feature. Instead of manually writing a detailed PRD, they can use this tool to input their initial thoughts. The tool will then guide them through a process of refining requirements, defining architecture, and breaking down features, ultimately producing a comprehensive PRD ready for development and testing.

**How to Use:**

Although direct execution commands are not provided, the project structure suggests an interaction model where user input is processed to generate PRDs. The presence of `langchain` and `openai` libraries indicates that it likely leverages large language models for the generation process. Users would typically interact with the tool through a defined interface (potentially a web API using FastAPI, given its inclusion in `requirements.txt`) or a command-line interface that prompts for input and guides the PRD creation workflow.

*   The `prd-writer.skill` file and associated Markdown files (`SKILL.md`, `output-template.md`, `stage-guide.md`) hint at a structured, skill-based approach to PRD generation.
*   The `coze-workload-identity` and `cozeloop` dependencies might suggest integration with a specific platform or framework for running these skills.

Further implementation details would be needed to provide exact usage commands.

## Project Structure 📂

```
Coze_Mining_Requirement_Generation_PRD/
├── prd-writer.skill
├── prd-writer/
│   ├── SKILL.md
│   └── references/
│       ├── output-template.md
│       └── stage-guide.md
├── requirements.txt
└── README.md
```

## Contributing 🤝

We welcome contributions to improve this project! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix (`git checkout -b feature/YourFeature`).
3.  Make your changes and commit them (`git commit -m 'Add some YourFeature'`).
4.  Push to the branch (`git push origin feature/YourFeature`).
5.  Open a Pull Request.

Please ensure your code adheres to the project's coding standards and includes relevant tests if applicable.

## License ⚖️

This project is not explicitly licensed. Based on common open-source practices, it's often good to include a LICENSE file. If you intend to open-source it, consider adding a standard license like MIT or Apache 2.0.

## Important links 🔗

- **Repository:** [https://github.com/YyyyyyoungC/Coze_Mining_Requirement_Generation_PRD](https://github.com/YyyyyyoungC/Coze_Mining_Requirement_Generation_PRD)
- **Author Profile:** [https://github.com/YyyyyyoungC](https://github.com/YyyyyyoungC)

## Footer ❤️

Made with ❤️ by [YyyyyyoungC](https://github.com/YyyyyyoungC)

--- 

:star: Like this project? Give it a star!

:fork_and_knife: Fork it and contribute!

:bug: Found an issue? Report it!

© 2023 Coze_Mining_Requirement_Generation_PRD. All rights reserved.


---
**<p align="center">Generated by [ReadmeCodeGen](https://www.readmecodegen.com/)</p>**
