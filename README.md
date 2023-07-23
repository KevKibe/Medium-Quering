## Medium Article Chatbot: Interacting with Articles from Medium Using Conversational AI
This is an application that allows users to interact with one or many articles from Medium using conversational AI techniques.
The chatbot utilizes the OpenAI GPT-3.5 model and provides answers to user queries based on the content of the Medium articles.

## Features
- Fetches one or many articles from Medium based on provided URLs
- Preprocesses the article content for better compatibility with the chatbot model
- Builds a conversation chain using the preprocessed article texts
- Allows users to ask questions and receive answers from the chatbot
- Provides a chat history for tracking previous interactions

## Limitations
- The chatbot's usage is limited to articles that are freely accessible on Medium. 
- Articles behind a paywall or requiring a subscription may not be accessible for fetching and processing.
- The accuracy and relevance of the chatbot's answers depend on the quality and comprehensiveness of the article content.
## Installation
- Clone the repository: `git clone https://github.com/KevKibe/Medium-Article-Chatbot.git`
- Install dependencies: `pip install -r requirements.txt`
- Set up environment variables: Create a `.env` file in the root directory of the project and add your OpenAI API key as follows:
  `OPENAI_API_KEY=your_api_key_here`

## Usage
- Enter one or many medium article URLS in the variable `url=[ ]` in the `main.py` file
- Run the application: `python main.py`
- Enter your queries in the console prompt and press Enter.
- The chatbot will process your query and provide an answer based on the content of the Medium articles.
- Continue the conversation by entering additional queries.
- Exit the conversatio by entering command `q`

## Contributions
Contributions to the Medium Article Chatbot are welcome!
If you find any issues or have suggestions for improvements, please feel free to open an issue and submit a pull request on the GitHub repository.
