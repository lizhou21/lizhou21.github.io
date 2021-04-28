---
title: "PhD Thesis Proposal: Generalizing Pre-Trained Neural Language Models"
collection: publications
permalink: /publication/2020-06-01-generalizing-pre-trained-neural-language-models
date: 2020-06-01
paperurl: '/files/language-models.pdf'
citation: 'Garneau, N. (2020)'
---
In its most generic form, a language model is trained to predict the next symbol given a history
of symbols. Symbols can either be words or characters for example. Trained on a corpus, a
language model can therefore predict the probability of a sequence of symbols of indenite
length. The language models are used in several applications of natural language processing
such as machine translation where it is used to obtain the most likely translation into the
target language given a list of candidates. In recent years, neural networks have become the
state of the art in language modelling. It has specifically been shown that these pre-trained
language models are inherently feature extractors (language representations) with which one
can add a simple classifier to accomplish a specific task like text classification or sequence
labelling. The Web contains a colossal amount of textual data and we now see the apogee of
more imposing models in number of parameters which push the state of the art even further.
However, these powerful pre-trained language models can only be effectively transferred to
tasks of the same language which is limited mainly to English for the moment.

While these models obtain exceptional performances on a specific language, transferring them
to another language is an under-explored research avenue. We assume that using an English
pre-trained language model will benefit to any other language model as well as the downstream
tasks in the target language (e.g. sequence labelling in Danish). The main objective of this
proposal is to explore the multilingual transfer of pre-trained language models, therefore to
generalize the models to languages which are under-represented in terms of textual resources.

Transferring language representations from one task to another inherently assume a similar
vocabulary between the language model and downstream task's dataset. Transferring a pretrained language from a source language to a target language invalidates this hypothesis,
especially if the two languages or the dataset have a very different lexicon.

To achieve our goal, we inspire ourselves by the work that has been accomplished to transfer
fixed word representations from a source to a target language. This active field of research
has generated several methods to transfer such pre-trained word representations which is the
starting point for our experiments.

We also plan to explore the use of external metadata such as images or user profiles to condition
a pre-trained language model in a conversational context where the lexicon is different from
the pre-trained model's.

Finally, we propose to study the learning dynamics of pre-trained language models in a multilingual setting by grounding the vectorial representations using a multilingual analogy dataset.
The result of this project will be to provide a way of transfer contextual representations of
words to a target language obtained using an English pre-trained neural language model.
