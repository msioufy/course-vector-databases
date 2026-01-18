# Setting up your environment


```
conda create -n vector-databases -yq python=3.12
conda activate vector-databases

conda install jupyter
pip install dotenv
pip install openai
pip install torch transformers  # BGE Models
pip install torch open_clip_torch langchain-experimental  # OpenClip Model
pip install pinecone
```