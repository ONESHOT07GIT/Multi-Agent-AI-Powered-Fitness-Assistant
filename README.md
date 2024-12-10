# Multi-Agent-AI-Powered-Fitness-Assistant
Tools: Python, Streamlit, LangFlow, AstraDB, OpenAI API  Developed an AI-based fitness assistant 

## Overview
This project demonstrates the development of an **advanced multi-agent AI application**. The application integrates multiple large language models (LLMs) to perform diverse tasks, including real-time fitness recommendations and calculations, leveraging **retrieval-augmented generation (RAG)** techniques and dynamic user interaction via a custom-built UI.

## Key Features
- **Multi-Agent AI System**: Combines multiple LLMs to handle tasks such as fitness recommendations and complex mathematical calculations.
- **Retrieval-Augmented Generation (RAG)**: Uses **AstraDB** as a vector database to retrieve context-specific information efficiently.
- **Dynamic User Interaction**: Designed an intuitive frontend using **Streamlit**, allowing seamless user input and response visualization.
- **Tool Integration**: Enabled advanced operations like mathematical calculations by incorporating tools through LangFlow workflows.
- **Scalability**: Built a robust architecture for deploying the application locally or on cloud platforms.

---

## Tools and Technologies
- **Programming Language**: Python
- **Frontend**: Streamlit
- **AI Workflow Builder**: LangFlow
- **Database**: AstraDB (Vector Search)
- **LLMs**: OpenAI GPT API
- **Visualization**: Streamlit and LangFlow UI
- **Other Tools**: JSON, REST API

---

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.8 or higher
- Pip package manager
- API keys for OpenAI and AstraDB

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/ONESHOT07GIT/Multi-Agent-AI-Powered-Fitness-Assistant.git
   cd Multi-Agent-AI-Powered-Fitness-Assistant
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
3. **Set Environment Variables**:(Create a .env file in the root directory )
   ```bash
   OPENAI_API_KEY=your_openai_api_key
   ASTRA_DB_APPLICATION_TOKEN=your_astra_token
   ASTRA_DB_ENDPOINT=your_astra_db_endpoin
4. ***Run the Application**:
   ```bash
   streamlit run main.py


## Project Workflow

### Architecture

1. **Input Handling**:
- Users input personal fitness data (weight, height, activity level, goals) via the Streamlit frontend.

2. **AI Workflow**:
- Inputs are passed to LangFlow workflows to process and retrieve relevant responses.
- A **conditional router** directs queries to specialized LLMs or tools (e.g., calculators).

3. **Data Storage and Retrieval**:
- User notes and profile data are stored in **AstraDB** and retrieved dynamically to tailor AI responses.

4. **Output**:
- The application generates responses and recommendations, tailored to user inputs and stored notes.

---

## Usage

### Fitness Recommendation
- Input your personal details and goals via the provided form.
- The application provides specific fitness recommendations and nutrition plans.

### AI-Driven Calculations
- Ask the AI questions requiring calculations (e.g., calorie needs).
- The application routes queries to tools for accurate mathematical operations.

---

## Key Components

### LangFlow Workflow
- **Conditional Routing**: Routes inputs to appropriate tools or LLMs.
- **Prompt Engineering**: Custom prompts ensure relevant responses tailored to user inputs.

### AstraDB Integration
- Stores user profiles and notes as vectors for efficient retrieval.
- Powers the RAG system by returning contextually relevant data for queries.

### Streamlit Frontend
- Interactive forms and dropdown menus for user inputs.
- Dynamic display of AI responses and fitness recommendations.

---

## Results
- **Enhanced User Experience**: Real-time responses tailored to user inputs.
- **Accurate Recommendations**: Incorporates tools for precise calculations and contextual understanding.
- **Scalable Design**: Deployable on local machines or cloud platforms.

---

## Future Enhancements
- Add support for additional tools (e.g., weather APIs, advanced fitness trackers).
- Implement advanced user authentication for multi-user support.
- Expand the LangFlow workflow to include more task-specific LLMs.





