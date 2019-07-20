how do I embed a sequence of words? From context-free to contextual embeddings
--------------------------

## Abstract ENG

The goal of this talk is answering to a simple question in the field of Natural Language Processing, "how do I embed a sequence of words?". To respond this question, we analyze the reference literature related to Word Representations in Vector Space. Starting from traditional Distributional Semantic Models, we'll move to "context-free" approaches, such as Word2Vec, FastText and GloVE, that generate a single "word embedding" representation for each word in the vocabulary (so *bank* would have a similar representation to *bank deposit* and *river bank*). Finally, we will focus on "contextual models" such as ELMo, BERT, ULMFiT, OpenAI transformer, and XLNet which generate a representation of each word that is based on the order of the other words/sequence of characters in the sentence. For each method we'll highlight pros, cons and application examples.

## Abstract ITA

Il goal di questo task è porre le basi per rispondere ad una semplice domanda nel campo del "Natural Language Processing" ossia, “Come *embeddare* in maniera efficace una sequenza di parole?". Per rispondere a questa domanda analizzeremo la letteratura di riferimento nel campo del *Word Representations in Vector Space*. Partendo da approcci classici basati su *Distributional Semantic", introdurremo modelli *context-free*, come Word2Vec, FastText e GloVE, il cui obiettivo è generare una *word embedding* per ogni parola nel vocabolario di riferimento (dove per esempio la parola *bank* avrà una rappresentazione simile a *bank deposit* e *river bank*). Infine, ci concentreremo sui "contextual models", come ELMo, BERT, ULMFiT, OpenAI transformer e XLNet, che sono in grado di generare una rappresentazione di una parola basata sull'ordine in cui sono osservate le altre parole/sequenza di caratteri nella frase osservata. Per ognuno degli approcci analizzeremo pro, contro e fornire degli esempi di task in cui applicarli


- [slides](./embedding_for_fun.pdf)

## Setup

In order to setup di environments please use [virtualenv](https://docs.python-guide.org/dev/virtualenvs/) or [miniconda](https://docs.conda.io/en/latest/miniconda.html). We suggest to use the latter.

1. install miniconda

2. setup the environments:

```
$ conda create --name dl_tf1 python=3
$ conda activate dl_tf1
$ base setup_tf1.sh
```

3. create the environments and install libraries

```
$ conda create --name dl_tf2 python=3
$ conda activate dl_tf2
$ bash setup_tf1.sh
```


4. open jupyter notebooks

```
$ jupyter notebook
```
