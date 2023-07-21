# POS_Tagging_NLP
Part-of-Speech (PoS) tagging is the task of labelling each word in a sentence with its appropriate part of speech; in the last years, the majority of researchers mainly used Deep Learning tools for developing POS tagging models, which include neural network architectures. In this assignment, we tested four different neural
architectures (BiLSTM/ GRU + Dense Layers) for PoS tagging. One important aspect of this task was the embedding of OOVs words, which we handled by choosing the mean of the word context embeddings when it was possible. Finally, the two best models according to the macro F1 score were the BiLSTM followed by a Dense layer (BiLSTM model) and the two-layer BiLSTM followed by a Dense Layer (ML-BiLSTM model).
In this folder you can find:
- jupyter notebook with the models (BiLSTM, ML-BiLSTM, BiGRU, BiDense);
- the PDF report of the work;
- the weights of the models that you can upload in the notebook.

<br><br>
Authors: [Andrea Alfonsi](https://github.com/andreaAlfonsi), [Gianluca Di Tuccio](https://github.com/DitucSpa), [Lorenzo Orsini](https://github.com/lorenzo-orsini)
