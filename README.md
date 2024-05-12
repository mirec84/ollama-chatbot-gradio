# Local Llama 3 UI
Chat UI for local offline Llama3 Model to chat with.

## Architecture
![Alt text](architecture.png?raw=true "Architecture")

## Streamlit UI
![Alt text](llama3_gradio.png?raw=true "Streamlit UI")

## Prerequisites
- Install Ollama - https://ollama.com/
- Install Python 3

## Download Llama 3 model 
In your terminal:

  `ollama pull llama3:latest`

## Install Python libraries
In your terminal:

  `pip3 install -r requirements.txt`

## Run the Streamlit app

  `python3 run gradio_app_v1.py`

## Create Shell alias
Add into your `bashrc` or `zshrc` file:

  `alias llama='cd ~/llama3_local; python3 run gradio_app_v1.py'`

NOTE: update the `cd ~/llama3_local` with the path, where you've saved this project.

## Run the shell alias to call it from any directory

  `llama`

  
