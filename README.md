This chatbox will provide the information about the stress relive steps .

# Stress Reliever

A knowledgeable etiquette chatbot powered by Stress Relief.

## Introduction

This project demonstrates a Retrieval-Augmented Generation (RAG) chatbot using Hugging Face's Inference API, Gradio, and FAISS for efficient similarity search. The chatbot, named "Stress Reliever," is designed to provide helpful advice on the how to maintain a positive environment and good mental health.

## Features

- Uses the Zephyr-7b-beta model from Hugging Face for natural language processing
- Implements RAG to provide context-aware responses
- Utilizes FAISS for efficient similarity search in the knowledge base
- Provides example prompts to demonstrate the chatbot's capabilities
- Offers a user-friendly interface powered by Gradio

## Prerequisites

Before you start, make sure you have the following:

- Python 3.6 or higher
- A Hugging Face account (sign up at [huggingface.co](https://huggingface.co/join))

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/ManpreetKaur4368922/Customized-LLM-APP.git
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Download the PDF of real estate investing and place it in the project directory with the filename `StressRelief.pdf`.

## Usage

To run the chatbot locally:

1. Open a terminal and navigate to the project directory.
2. Run the following command:
   ```
   python app.py
   ```
3. Open your web browser and go to the URL displayed in the terminal (usually `http://127.0.0.1:7860`).

## How It Works

1. The chatbot loads the PDF of Mypdf and processes it into a vector database.
2. When a user asks a question, the system searches for relevant passages in the etiquette guide.
3. The retrieved context is then passed to the LLM along with the user's query.
4. The LLM generates a response based on the provided context and its training.

## Customization

You can customize the chatbot by modifying the following in `app.py`:

- Knowledge base: Replace `StressRelief.pdf` with another PDF to change the chatbot's knowledge domain.
- System message: Edit the `system_message` variable to adjust the chatbot's behavior and tone.
- Model: Change the `InferenceClient` to use a different model from Hugging Face.
- Examples: Modify the `examples` list to showcase different interactions.

## Deployment

This project can be deployed on Hugging Face Spaces:

1. Fork this repository to your GitHub account.
2. Go to [huggingface.co/spaces](https://huggingface.co/spaces) and click "Create new Space".
3. Choose "Gradio" as the SDK.
4. Link your forked GitHub repository.
5. Add your `StressRelief.pdf` file to the Space's files.
6. Deploy and enjoy your etiquette chatbot!

## Disclaimer

This chatbot is based on Stress relief guide and is intended for general advice on how to handle day to day pressure of the surrounding. It should not be considered as a substitute for professional advice in specific situations.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgements

- Hugging Face for providing the Inference API
- Gradio for the user interface framework
- FAISS for efficient similarity search

## Contact

For any questions or feedback, please reach out to ma4368922@alphacollege.me.

