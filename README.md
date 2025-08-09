# Agentic AI: From Beginner to Expert

Welcome to the ultimate course on building Agentic AI systems! This course is designed to take you from the foundational concepts of AI to designing and implementing complex, multi-agent systems using the latest and most relevant frameworks.

## 📊 Course Analysis & Structure

### The Landscape of Agentic AI Education

The field of Agentic AI is evolving at an unprecedented pace. While there are many resources available, they often fall into two categories:
1.  **Too theoretical:** Focusing on high-level concepts without practical, hands-on coding experience.
2.  **Too framework-specific:** Diving deep into one tool without providing a broader understanding of the ecosystem and how different frameworks can be integrated.

This course aims to bridge that gap.

### Our Proposed Learning Path

We offer a structured, modular learning path that builds on your existing Python and OOP knowledge. The course is designed to be progressive, with each chapter building on the last, ensuring a solid understanding of both theory and practice.

1.  **Foundations:** We start with the "why" behind Agentic AI and map familiar OOP concepts to agentic design principles.
2.  **Core Frameworks:** We introduce you to the most influential frameworks one by one, focusing on their core strengths.
3.  **Advanced Concepts:** We delve into multi-agent collaboration, graph-based workflows, and seamless integration with powerful APIs like Gemini and Hugging Face.
4.  **Cutting-Edge Protocols:** We explore the future of agent communication with the Model Context Protocol (MCP).
5.  **Capstone Project:** You'll apply everything you've learned to build a modular, multi-framework agentic system.

## 🧰 Framework Selection

The frameworks chosen for this course are selected based on their relevance, community support, modularity, and ease of integration.

| Framework | Justification |
|-----------|---------------|
| **LangChain** | The most popular and comprehensive framework for building LLM-powered applications. It's an excellent starting point for understanding chains, tools, and agents. |
| **CrewAI** | A role-based agent framework that simplifies multi-agent collaboration. Its intuitive design is perfect for beginners in the multi-agent space. |
| **LangGraph** | An extension of LangChain that allows for creating cyclical and stateful agent workflows. It's essential for building more complex and robust agents. |
| **AutoGen** | A powerful framework from Microsoft Research for building conversational agents that can solve complex tasks. |
| **OpenAgents** | An open-source platform for hosting and deploying agents, which will be explored for real-world deployment scenarios. |

## 🔑 API Key Setup Instructions

To complete this course, you will need API keys for Google's Gemini and Hugging Face.

### 1. Get Your Gemini API Key
- Go to the [Google AI for Developers](https://ai.google.dev/) website.
- Click on "Get API key in Google AI Studio".
- Create a new project and an API key.
- **Important:** Keep this key safe and do not share it publicly.

### 2. Get Your Hugging Face API Key
- Create an account on [Hugging Face](https://huggingface.co/).
- Go to your profile settings and then to the "Access Tokens" section.
- Create a new token with "read" permissions.
- **Important:** Keep this key safe.

### 3. Configure Your Environment
This project uses a `.env` file to manage API keys securely.

1.  **Rename the example file:**
    ```bash
    cp .env.example .env
    ```
2.  **Add your keys:**
    Open the `.env` file and replace the placeholder text with your actual API keys:
    ```
    GEMINI_API_KEY="YOUR_GEMINI_API_KEY"
    HUGGINGFACE_API_KEY="YOUR_HUGGINGFACE_API_KEY"
    ```

## 🚀 How to Run the Notebooks

### Running in Google Colab (Recommended)
Each notebook has a "Open in Colab" badge at the top. Click on it to open the notebook in a new Colab session. You will be prompted to upload your `.env` file or enter your API keys.

### Running Locally
1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Start Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
4.  Navigate to the `notebooks` directory and open the chapter you want to work on.

## 🔧 Troubleshooting
- **`ModuleNotFoundError`:** Make sure you have installed all the packages from `requirements.txt`.
- **API Key Errors:** Double-check that your `.env` file is correctly named and that the variable names match those in the notebooks (`GEMINI_API_KEY`, `HUGGINGFACE_API_KEY`).

## 📜 Licensing and Contribution
This course is licensed under the MIT License. We encourage contributions! Please open an issue or submit a pull request if you have suggestions for improvement.
