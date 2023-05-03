# HuggingChat_api_v01
A Python api to use free open source HuggingChat service v0.1

No API keys. No signup. Just pip install hugchat
[![PyPi](https://img.shields.io/pypi/v/hugchat.svg)](https://pypi.python.org/pypi/hugchat)
[![Support_Platform](https://img.shields.io/pypi/pyversions/hugchat)](https://pypi.python.org/pypi/hugchat)
[![Downloads](https://static.pepy.tech/badge/hugchat)](https://pypi.python.org/pypi/hugchat)


##  How to Use

### Basic mode
```bash
pip install hugchat
```

```py
from hugchat import hugchat
chatbot = hugchat.ChatBot()
print(chatbot.chat("Code a snake game"))

