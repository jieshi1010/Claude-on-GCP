# Claude on GCP

This repository contains examples and tutorials for using Anthropic's Claude models on Google Cloud Platform (GCP) through Vertex AI.

## 🌟 Overview

The notebooks in this repository demonstrate how to interact with Claude models for various tasks, showcasing features like large context windows and tool use.

## 🚀 Getting Started

### Prerequisites

- A Google Cloud Platform project with the Vertex AI API enabled.
- Authentication configured for your environment. If you are using Google Colab, the notebooks will guide you through the authentication process.

### Installation

The necessary Python libraries can be installed by running the first code cell in each notebook. The primary dependency is `anthropic[vertex]`.

```bash
pip install --upgrade --user --quiet 'anthropic[vertex]'
```

##  notebooks

This repository contains the following notebooks:

### 1. `jieshi_claude_1M_context_window_with_Vertex_Claude.ipynb`

- **Purpose**: This notebook demonstrates how to use Claude with a 1 million token context window via Vertex AI.
- **Usage**:
    1. Open the notebook in a compatible environment (like Google Colab or Jupyter).
    2. Run the cells sequentially.
    3. The notebook will guide you through installation, authentication, and making a simple API call to the Claude model with the 1M context window enabled.

### 2. `jieshi_claude_interleaved_thinking_with_Vertex_Claude.ipynb`

- **Purpose**: This notebook showcases a more advanced use case involving a restaurant reservation chatbot. It demonstrates how to use Claude with tools and interleaved thinking to create a conversational agent.
- **Usage**:
    1. Open the notebook.
    2. Run the cells in order.
    3. The notebook defines a `Restaurant` class to simulate a reservation system and uses it with Claude to handle user requests.
    4. At the end of the notebook, you can interact with the chatbot in a command-line interface.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for improvements or new examples, please feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the terms of the [LICENSE](LICENSE) file.
