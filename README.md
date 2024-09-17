# 🎯 AI-Driven Media Investment Plan Across Channels for E-commerce
## 🚀 BUDGET MASTER APPLICATION - https://www.popai.pro/share.html?shareKey=51436dd50214b0bb877c20f5b09c519a025e6cd19e568d00fda8ce24ce954155&utm_source=presentationsharepage

### Overview
This project focuses on **optimizing a analysis and marketing budget** across various paid media channels using AI, machine learning, and **RAG-powered LLM chatbot**. The chatbot interacts with users, answering queries about customer journeys, ad performance, and budget reallocation. It employs **LangChain** and **Chainlit** for enhanced document retrieval and language generation.


## ✨ Features

- AI-Powered Media Optimization: Allocate and optimize marketing budgets across paid media channels using an AI-driven model.
- Data Upload & Analysis: Users can upload customer journey data, ad spend data in CSV or other formats, and receive detailed analysis and insights.
- RAG-Powered Chatbot: The chatbot interacts with users, answering queries about ad performance, customer journey insights, and budget recommendations.
- Python & Azure-Powered: Built using Python, LangChain, Azure, and other modern tools for seamless AI operations.
- Customizable Welcome Screen: Modify the Chainlit-powered welcome screen or remove it as needed.

---

## 📂 Project Structure

- `.dockerignore`: Specifies which files to ignore during Docker builds.
- `.gitignore`: Lists files and directories that Git should ignore.
- `Dockerfile`: Defines the Docker image build process using Python 3.12 and Poetry.
- `LICENSE`: MIT License, ensuring the project is free and open for any use.
- `chainlit.md`: Contains the welcome message for users interacting with the Chainlit-based chatbot.
- `chat_app.py`: The main application that runs the chatbot, integrating LangChain, Azure, and custom tools for document search and Python execution.
- `common.py`: Manages Azure's vector store and search index with embeddings to enhance search functionality.
- `entrypoint.sh`: A shell script to start the chatbot or indexer job based on the argument provided.
- `indexer_job.py`: Handles document loading and indexing of user-uploaded files (e.g., PDFs) into the vector store.
- `poetry.lock`: Ensures dependency version consistency.
- `prompt.py`: The prompt template guiding the chatbot's logic for budget optimization.
- `pyproject.toml`: Project configuration and dependency management via Poetry.

---

## 🛠️ Installation and Setup

1. Clone the Repository

    ```bash
    git clone https://github.com/your-username/budget-master.git
    cd budget-master
    ```

2. Install Dependencies with Poetry

    Make sure you have [Poetry](https://python-poetry.org/) installed.

    ```bash
    poetry install
    ```

3. Set up Environment Variables

    Create a `.env` file in the root directory with your Azure and OpenAI credentials:

    ```bash
    AZURE_OPENAI_ENDPOINT="your-azure-openai-endpoint"
    AZURE_SEARCH_ENDPOINT="your-azure-search-endpoint"
    POOL_MANAGEMENT_ENDPOINT="your-pool-management-endpoint"
    ```

4. Run the Application

    Use the provided `entrypoint.sh` to run the chatbot or indexer job:

    ```bash
    ./entrypoint.sh chat_app
    ```

    Or run the indexer:

    ```bash
    ./entrypoint.sh indexer_job
    ```

---

## 🧠 How It Works

- Step 1: The user uploads their data (e.g., CSV files) to the application.
- Step 2: The application processes and indexes the data using Azure Search and LangChain embeddings.
- Step 3: The chatbot interacts with the user, answering questions about customer journeys, ad performance, and providing optimized budget plans.
- Step 4: The AI model uses machine learning techniques to suggest optimal media budgets across various channels based on the uploaded data.

---

## 🔧 Key Technologies

- Python 3.12: Core programming language for AI and data processing.
- LangChain: Used for creating the RAG (Retrieval-Augmented Generation) chatbot.
- Azure Search: For storing and retrieving document vectors for fast and efficient search.
- Chainlit: Powers the chatbot interface and user interactions.
- Poetry: Dependency and project management.

---

## 🧪 Example Use Case

Here’s a brief example of how the chatbot works:

1. Upload Data: Users upload their CSV or PDF data containing customer journey and ad spend information.
2. Ask Questions: The user asks the chatbot: "Which channel is driving the most conversions?"
3. Receive AI-Powered Insights: The chatbot analyzes the data and responds with insights such as: "Based on the data, paid search ads have the highest conversion rates for the allocated budget."
4. Budget Reallocation: The chatbot suggests reallocating budget to optimize conversions: "It is recommended to allocate 20% more budget to paid search ads to increase conversions by 15%."

---

## 📊 Media Investment Strategy

The AI analyzes and reassigns the budget based on customer journey and ad spend data:

- Data-Driven Budget Allocation: Based on uploaded data, the AI suggests how to reallocate a $200,000 total budget across various channels like:
  - 📈 Paid Search
  - 📱 Social Media
  - 🛍️ Display Ads
  - 📰 Native Ads

- Advanced Machine Learning: The model predicts the potential conversion uplift by reallocating the budget.
- Visualization: Results can be plotted using `pandas`, `plotly`, or `matplotlib`.

---

## 🤝 Contributing

We welcome contributions from the community! Please follow these steps:

1. Fork the repository.
2. Create a new branch with a descriptive name (e.g., `feature-new-analysis-tool`).
3. Make your changes and commit them.
4. Open a pull request, and describe the changes in detail.

---

## 🛡️ License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for more details.

---

## 👥 Community and Support

For any questions or support, feel free to reach out:

- Join the discussion on our [Discord Community](https://discord.gg/k73SQ3FyUh) 💬
- Check out the full [Chainlit Documentation](https://docs.chainlit.io) 📚

---

Thank you for using BUDGET MASTER APPLICATION! We can’t wait to see how you optimize your ad spending and boost your conversions with AI! 🚀💰
