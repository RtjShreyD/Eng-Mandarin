# Eng-Mandarin

This repository is made as experiments with
Natural Language Processing and its techniques, demonstrating a basic application of translation from English to Mandarin(Chinese) language. 
The model demonstrated here is not perfect in translation between the two languages and still has multiple scope of improvement, however its performance is one of the best among the algorithms used in NLP for translations and is based upon Sequence-to-Sequence ecoder-decoder model.
The encoders tried are Seq2Seq, Seq2Seq with added Attention(Linear, Bilinear, Dot Product) and the one shown in the Train.ipynb notebook is a pure SelfStackedAttention encoder having Dot Product Attention
The loss at the end of 10 epochs in the current model is around 1.9 ~ 2.1 approx which is still has scope of improvement in the current model script only. Next we could try for 50 epochs. Another thing that can minimize the loss is, to make the preprocessed dataset to be more efficient, as we can make all the dataset converted to simplified Chinese script before passing through training module.
The repository will be kept updated with new content and improvised versions of Eng-Mandarin translator, as soon as some progress is made.

Datasets have been obtained from : https://tatoeba.org/eng/downloads

Credits: http://www.realworldnlpbook.com/blog/building-seq2seq-machine-translation-models-using-allennlp.html
