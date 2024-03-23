## Project : Build a AI-powered Image Gallery

....

**openai**: [OpenAI](https://openai.com/):  OpenAI Python library to create GPT-3 applications. Streamlit: [Streamlit](https://streamlit.io/): Streamlit is an open-source Python toolkit that facilitates the development of stunning, personalized online applications for data science and machine learning. **streamlit-chat**: Adding a chatbot to your Streamlit app is possible with the help of the Streamlit component known as "streamlit-chat"  [Streamlit Chat](https://pypi.org/project/streamlit-chat/):. It generates replies to user input using OpenAI's GPT-3. **python-dotenv**: [Python Dotenv](https://pypi.org/project/python-dotenv/): Adds the key-value pair to the environment variable by reading it from the.env file. Using the 12-factor principle, it is excellent for controlling app settings both in development and production. **pillow**: [Pillow](https://pypi.org/project/Pillow/): Pillow is Alex Clark and Contributors' amiable PIL fork. The Python Imaging Library (PIL) was created by Fredrik Lundh and his collaborators.

Requirements:

## Create a virtual environment :

**MacOS/Linux**:

```
python3 -m venv env
```

**Windows**:

```
python -m venv env
```

## Activate the virtual environment :

```
source env/bin/activate
```

## Installation:

**MacOS/Linux**:

```
pip3 install -r requirements.txt
pip3 install streamlit streamlit-chat
```

**Windows**:

```
pip install -r requirements.txt
pip install streamlit streamlit-chat
```

## [Get an API key](https://platform.openai.com/account/api-keys)

### Set the key as an environment variable:

`export OPENAI_API_KEY=YOUR OPEN AI KEY`

.env file:

```
OPENAI_API_KEY=YOUR OPEN AI KEY
```

## Start the app:

`streamlit run main.py`
