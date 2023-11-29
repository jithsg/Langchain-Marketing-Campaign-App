
# Streamlit Marketing Tool

## Introduction
This Streamlit application is designed to generate marketing content using OpenAI's GPT model. It's tailored for different age groups and can create various types of content such as sales copies, tweets, and product descriptions. The application uses the LangChain library to interact with OpenAI's API, providing a user-friendly interface for content generation.

## Features
- Generate marketing content based on user input.
- Tailored responses for different age groups (Kids, Adults, Senior Citizens).
- Options to create sales copies, tweets, and product descriptions.
- User-friendly interface with Streamlit.

## Installation

Before running the application, ensure you have Python installed on your system. Then, follow these steps:

1. **Clone the Repository**
```
   git clone [repository URL]
   cd [repository directory]
```
2. **Set up a Virtual Environment (Optional but recommended)**
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install Dependencies**
   ```
   pip install streamlit openai langchain python-dotenv
   ```
4. **Environment Variables**
   - Create a .env file in the root directory.
   - Add your OpenAI API key
     ```
     OPENAI_API_KEY='your_api_key_here'
     ```
5. **Usage**

    - To run the application:

    - Start the Streamlit App

      ```
      streamlit run app.py
      ```

6. **Using the Application**

    - Open your web browser and go to ```http://localhost:8501.```
    - Enter the text you want to base your marketing content on.
    - Select the content type and target age group.
    - Adjust the word limit as needed.
    - Click "Generate" to receive your marketing content.


