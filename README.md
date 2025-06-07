# MEDIGUIDE: End to end Medical Chatbot 

# How to run?
### STEPS:

Clone the repository

```bash
[Project repo: https://github.com/harshitgoel2601/mediguide]
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n mediguide python=3.10 -y
```

```bash
conda activate mediguide
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone & TogetherAI api credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
TOGETHER_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```




### Techstack Used:

- Python
- LangChain
- Flask
- Together API
- Pinecone




    
