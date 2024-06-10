# LangChain-practice

This is a simple project to practice LangChain with OpenAI model.  

Developped on local environment using Jupyter Lab.  
To start Jupyter Lab: `jupyter lab`

API keys are stored in local environment variables. You can also add following code to input API keys.

```python
import getpass
import os

os.environ["LANGCHAIN_TRACING_V2"] = "true"
os.environ["LANGCHAIN_API_KEY"] = getpass.getpass()

os.environ["OPENAI_API_KEY"] = getpass.getpass()
```

### LangSmith

Using LangSmith to trace logs, e.g.  
<img width="655" alt="Screenshot 2024-06-09 at 21 44 46" src="https://github.com/Sunying-RONG/LangChain-practice/assets/44567186/c165bdab-8322-47d0-a2e7-83c78f605238">

### LangServe

Using LangServe to serve the app. `python3 serve.py`  
Go to `http://localhost:8000/chain/playground/`  
e.g.  
<img width="850" alt="Screenshot 2024-06-09 at 21 57 01" src="https://github.com/Sunying-RONG/LangChain-practice/assets/44567186/8c68b17f-f9e1-4e17-a636-ed98581223b4">


