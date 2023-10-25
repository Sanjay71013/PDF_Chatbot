# Chat with PDFs

Chat with PDFs is a web application that leverages the power of the OpenAI GPT-3.5 language model to enable users to have interactive conversations with uploaded PDF documents. With this application, users can upload multiple PDFs, process them, and then ask questions about the content of the documents. The application utilizes OpenAI's embeddings to understand and respond to user queries effectively.

![Chat with PDFs](/images/1.png)

## Table of Contents
- [Getting Started](#getting-started)
- [Features](#features)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Before you start using the Chat with PDFs application, make sure you have the following prerequisites:

- [Streamlit](https://streamlit.io/) installed on your system.
- An OpenAI API key. You can obtain this from [OpenAI](https://openai.com/).

### Installation

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/Sanjay71013/PDF_Chatbot.git
   ```

2. Navigate to the project directory:

   ```
   cd PDF_Chatbot
   ```

3. Create a `.env` file in the root directory of the project and add your OpenAI API key:

   ```
   OPENAI_API_KEY=your-api-key-goes-here
   ```

4. Start the development server:

   ```
   streamlit run app.py
   ```

This will start the application locally. You can access it in your web browser at `http://localhost:8501/`.

## Features

- **PDF Upload:** Users can upload multiple PDF documents for processing.
- **Chat Interface:** The application provides a chat interface where users can type questions and interact with the documents.
- **OpenAI Integration:** The application utilizes OpenAI's GPT-3.5 for document understanding and generation of responses.

## How to Use

1. **Upload PDFs**

   - Click on the "Upload PDFs" button.
   - Select one or more PDF documents you want to process.

   ![Upload PDFs](/images/2.png)

2. **Processing PDFs**

   - After selecting the PDFs, click on the "Process" button.
   - The application will process the uploaded PDFs to make them searchable.

   ![Processing PDFs](/images/3.png)

3. **Ask Questions**

   - Once the PDFs are processed, you can start asking questions.
   - Type your question in the chat input box and press Enter.
   - The application will use OpenAI's GPT-3.5 to generate responses based on the content of the uploaded PDFs.

   ![Asking Questions](/images/4.png)

4. **View Responses**

   - The responses from the application will appear in the chat interface.
   - You can have interactive conversations and seek information from the uploaded PDFs.

   ![View Responses](/images/5.png)
   
  - You can have a chain of interactive conversations.
    
   ![View Multiple Responses](/images/6.png)

## Contributing

We welcome contributions to improve and enhance the Chat with PDFs application. If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Test your changes thoroughly.
5. Create a pull request against the main repository.

We appreciate your contributions!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
