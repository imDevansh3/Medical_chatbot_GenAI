# End-to-end-Medical-Chatbot-Generative-AI
![Chat UI](https://github.com/imDevansh3/Medical_chatbot_GenAI/blob/main/images/Screenshot%202025-07-18%20at%201.27.03%E2%80%AFPM%20copy.png)

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/imDevansh3/Medical_chatbot_GenAI
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone & openai credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone
