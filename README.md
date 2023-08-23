# NLP-Projects
Natural Language Processing Projects.
# Introduction

Text Generation is the task of predicting what word comes next, given what words lies ahead of it. It can be thought of as a chain of Auto-Predict task, where the next word is continuously produced, from the current word. While dealing with text, the model needs to be trained to forget old Context, and update new Context, with each new words in the sequence, as each new words received brings some value-addition to the Context. For example, Pronouns are changed when the person talked about changes in the sentence.

Therefore,LSTM Reccurent Neural Networks will be leveraged to perform Text Generation. LSTM has a Context vector, and it has Forget gate to decide which part of the Old Context it should forget, an Input Gate to decide which part of the Input brings what change in the context,and an Output Gate to produce the Output or the next Word in this Text Generation task.
