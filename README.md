
Protein Language Model are Transformer-like models that are trained on massive sets of protein sequences (represented as text) in an attempt to learn the biological 'grammar' of proteins.These models have a broad range of application, thanks to their generative and embedding abilities.

In this workshop, we will get more familiar with this type of model, how they differ from their NLP counterparts and the tasks they can address. we will also get a short overview of the existing open-source models and datasets.

During the hands-on session, we will start from a pre-trained language model and develop a basic example of protein function multi label classifier. We will then develop compare and benchmark different classification approaches, including a simple retrieval-augmented enhancement, and fine tuning.

Session Outline:

Part 1: Introduction to Protein Language Models
An overview of protein language models (PLMs) and their significance in bioinformatics for synthetic biology use cases. This part includes an explanation of how PLMs differ from traditional natural language processing models, and examples of popular PLMs such as ProBERT, ProtTrans, Ankh..

Part 2: Hands-On Exercise

Part 2.1: Setup and first interactions
After setting up a google Colab environment (Python), you will get familiar with protein language model by retrieving a protein language model from Huggingface's repository and start playing with a protein dataset from the literature. This includes exploring the dataset content, get to know more about the protein function prediction task and experiment simple encoding/decoding of proteins sequences.

Part 2.2: 

<a target="_blank" href="https://colab.research.google.com/github/EtienneGof/plm_intro/blob/main/playin_with_protein.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Classification and fine-tuning 
In this session you will develop a protein function classifier by finetuning a small pre-trained protein language model. On the basis of this fine-tuned model, we will try to leverage the new embeddings and enhance the performance with retrieval-augmented classification.
