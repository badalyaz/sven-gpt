# SvenGPT chatbot
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

SvenGPT is a chatbot built using the OpenAI's Chat GPT API "gpt-3.5-turbo-16k" and Flask Server.    

## Requirements

1. Flask module to create a web server.
2. Langchain framework for using language model
3. OpenAI API key


## Getting Started

To get started using this application, please follow the steps below:

1. Create Conda environment `conda create --name <env-name>` and activate it `conda activate <env-name>`
2. Clone this repository
3. Run the command `pip install -r requirements.txt` to install the necessary Python packages.
4. Export your OpenAI key `export OPENAI_API_KEY=<your-key>`
5. Run the command `python app.py` to start the application.

**Accessing to the web app:**
   - To access the application after running the server, you need to open your web browser and enter the following URL: http://localhost:8080, and start chat.

<br>
   <img src="static/images/SvenGPT.gif" style="display: block;margin-left: 23px;margin-right: auto;max-width: 800px;height: auto;">