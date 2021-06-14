# Basic Chatbot Using Huggingface 🤗 Transformer Model

### Here's a quick look at what this repo aims at making:
![](https://github.com/EsratMaria/All-about-Natural-Language-and-Speech-Processing/blob/master/huggingface-transformers/DialoGPT_DialogRPT/visuals/recording.gif)

## How it works
- I am using Hugging face transformer models to make interactive chat experience. More about huggingface 🤗 can be found ![here](https://github.com/huggingface/transformers)
- I am using DialoGPT model to retrieve possible candidates based on user input
- Once the candidate are retrived I score them using DialogRPT model. 
- The one with the best score is chosen by the bot to reply with
- I have broken down the candidate generation and scoring into separate notebooks ![here](https://github.com/EsratMaria/All-about-Natural-Language-and-Speech-Processing/blob/master/huggingface-transformers/DialoGPT_DialogRPT/QueryCandidate_Retrieval_DialoGPT.ipynb) and ![here](https://github.com/EsratMaria/All-about-Natural-Language-and-Speech-Processing/blob/master/huggingface-transformers/DialoGPT_DialogRPT/Candidate_Scoring_DialogRPT.ipynb)


## Extra
If you want to score a list of candidate given by the user then you can check the notebook ![here](https://github.com/EsratMaria/All-about-Natural-Language-and-Speech-Processing/blob/master/huggingface-transformers/DialoGPT_DialogRPT/Transformer_Scoring_List_of_Candidates.ipynb) which guides you through the process and is a bit different from the above. 
