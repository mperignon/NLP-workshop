# NLP workshop for Insight

This repository contains the jupyter notebooks and data files we'll be using during the workshop.

Please clone this repo into your local machine. Open a terminal and type:
```
git clone https://github.com/mperignon/NLP-workshop.git
```

I **very strongly** recommend that you create a separate environment before installing the required packages to avoid potentially messing up your current Python setup. To create a new environment (here named "NLP") using Anaconda, run:
```
conda create -n NLP python=3.7
```

Switch to this environment by typing:
```
conda activate NLP
```

The minimum list of required packages is in the file `requirements.txt`. Automatically install them by running:
```
pip install -r requirements.txt
```

Download the spaCy language model for English by running:
```
python -m spacy download en_core_web_sm
```
