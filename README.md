# 🎯 AI-Driven Media Investment Plan Across Channels for E-commerce
## 🚀 BUDGET MASTER APPLICATION - https://www.popai.pro/share.html?shareKey=51436dd50214b0bb877c20f5b09c519a025e6cd19e568d00fda8ce24ce954155&utm_source=presentationsharepage

### Overview
This project focuses on **optimizing a analysis and marketing budget** across various paid media channels using AI, machine learning, and **RAG-powered LLM chatbot**. The chatbot interacts with users, answering queries about customer journeys, ad performance, and budget reallocation. It employs **LangChain** and **Chainlit** for enhanced document retrieval and language generation.

### Features
- **🔍 Analyze Customer Journey Data**: Review customer interactions across different marketing channels.
- **💡 Machine Learning Insights**: Utilize AI models to detect trends and optimize channel performance.
- **💬 RAG LLM Chatbot**: A conversational assistant that retrieves relevant data from documents and provides AI-generated answers.
- **📊 Budget Reallocation**: Smartly reallocate marketing budget based on performance forecasts.

### RAG LLM Chatbot Integration 🤖💬
The application features a **Retrieval-Augmented Generation (RAG) LLM chatbot**, which combines language models and document retrieval for enhanced answers. Here’s how it works:

1. **Document Search with LangChain**: The chatbot uses LangChain to retrieve relevant excerpts from documents.
2. **AzureChatOpenAI Integration**: The chatbot generates contextual, AI-driven answers using the GPT-35-turbo model.
3. **Chainlit Framework**: Provides real-time, interactive chatbot functionality in the user interface.

### How It Works ⚙️
1. **Data Retrieval**: The chatbot uses **LangChain** to fetch the most relevant document excerpts in response to user queries.
2. **LLM Response**: **AzureChatOpenAI** generates responses by combining the retrieved data and AI language models.
3. **User Interaction**: Through **Chainlit**, the chatbot interacts in real-time, providing valuable insights on customer journey data, ad spend, and budget decisions.

### Tools & Libraries 🛠️
- **AzureChatOpenAI**: GPT-35-turbo model used for generating AI-driven responses.
- **SessionsPythonREPLTool**: Executes Python code and supports machine learning analysis and visualization.
- **Vector Store Retriever**: Retrieves customer journey data from documents to aid analysis.
- **LangChain**: Retrieves relevant data chunks from documents to support RAG-based responses.
- **Chainlit**: Enables real-time interaction with users through an intuitive chatbot interface.

### Installation & Setup 🛠️

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-repo/budget-master-application.git
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set Environment Variables**:
    Set up your `.env` file to include necessary keys for Azure, LangChain, and vector store.
    ```
    AZURE_OPENAI_ENDPOINT=your_endpoint
    OPENAI_API_KEY=your_openai_key
    POOL_MANAGEMENT_ENDPOINT=your_pool_management_endpoint
    PDF_DIR=your_pdf_directory
    ```

4. **Run the Application**:
    Execute the application, which will launch the RAG-powered chatbot and allow users to query documents and optimize media investments.
    ```bash
    python app.py
    ```

### RAG LLM Chatbot in Action 💬✨
The chatbot can answer queries like:
- **“What channels are driving the most conversions?”**
- **“How should I reallocate my $200,000 budget for optimal conversions?”**
- **“Show me the customer journey data for Facebook Ads.”**

With the RAG approach, the chatbot retrieves relevant document sections, then the LLM generates detailed, insightful responses.

### Example Workflow 📈
1. **User Interaction**: A user asks the chatbot about ad performance or budget allocation.
2. **Document Retrieval**: LangChain retrieves the most relevant sections from the document store.
3. **Response Generation**: AzureChatOpenAI generates a response by combining retrieved data with its LLM capabilities.
4. **Insights Delivered**: The chatbot returns a concise, data-driven recommendation for improving the media plan.

### Usage 📊

- **Upload Data**: Upload PDF files containing customer journey or ad spend data to the system.
- **Ask Questions**: Use the RAG-powered chatbot to interact with the application and query data.
- **Analyze and Visualize**: Run Python code to process data, generate insights, and visualize trends.
- **Optimize Budget**: Based on AI-driven insights, reallocate your marketing budget to maximize conversions.

### Media Investment Plan 📑
At the end of the analysis, you will receive:
- A detailed media investment plan with optimized budget allocations.
- Predictions for conversion rates for each paid channel over the next 30 days.

### Contributions 🤝
Feel free to fork the project and create pull requests for any enhancements or bug fixes! Together, we can make marketing smarter with AI. 💼🤖

### License 📜
This project is licensed under the MIT License.

---

Start optimizing your marketing budget today with the **BUDGET MASTER APPLICATION**! 🎉
