# Neural-Translation-from-Japanese-to-English
## About this Project
This is an ongoing project with the aim to use deep learning to perform Japanese to English translation. There are currently two implementations, one that uses an Encoder Decoder with Attention model and one that uses Transformers. The Encoder Decoder with Attention was implemented with the help of the PyTorch NLP from Scratch tutorials at https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html while the Transformer model was implemented with the help of the Language Translation with Transformers tutorial at https://pytorch.org/tutorials/beginner/translation_transformer.html.  
## Technologies Used
- Python
- PyTorch
- HuggingFace
- spaCy
- Numpy
- Natural Language Toolkit (NLTK)
## Data and Code
Everything is written in Python and PyTorch is used for the deep learning aspects of this project. Other technologies such as tokenizers and bleu score evaluators come from spaCy and NLTK respectively. Much of text preprocessing is handled by Python and PyTorch. A Japanese-English dataset from the Tatoeba Collection was used to train both models.
## Current/Future Work
Current work involves coding an original implementation of the transformer from the paper *Attention is all you Need* and improving Bleu scores.
## References
- *Attention is all you Need*: https://arxiv.org/abs/1706.03762
- NLP from Scratch: Translation with a Sequence to Sequence Network and Attention: https://pytorch.org/tutorials/intermediate/seq2seq_translation_tutorial.html
- Language Translation with nn.transformer and torchtext: https://pytorch.org/tutorials/beginner/translation_transformer.html
- Tatoeba: https://tatoeba.org/en/
