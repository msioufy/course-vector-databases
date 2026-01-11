# Setting up your environment


```
conda create -n vector-databases -yq python=3.12
conda activate vector-databases

conda install jupyter
pip install dotenv
pip install openai
pip install pinecone
pip install torch transformers  # 8.1 BGE Models
pip install torch open_clip_torch langchain-experimental  # 8.2 OpenClip Model
```