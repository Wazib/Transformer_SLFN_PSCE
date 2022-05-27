# Transformer Encoder Architecture with Selective Learning and Enhanced Word Representation

This code is associated with the paper:

Ansar, Wazib, Saptarsi Goswami, Amlan Chakrabarti, and Basabi Chakraborty. “A Novel Selective Learning based Transformer Encoder Architecture with Enhanced Word Representation.” Submitted to Applied Intelligence, Springer.

## Introduction
With the advent of transformers with attention mechanisms, there have been widespread advances in natural language processing (NLP). However, these models are very complex and computationally intensive. In addition, the performance of such models depends on the feature representation strategy used to encode the input text. To address these issues, we propose a novel transformer encoder architecture with Selective Learn-Forget Network (SLFN) and contextualized word representation enhanced through Parts-of-Speech Characteristics Embedding (PSCE). The novel SLFN selectively remembers important information in the text through a gated mechanism. It enables parallel processing and improves the efficacy along with efficiency of the transformer while processing the dependencies intertwined in long sequences. The intuitive PSCE handles ambiguity, distinguishes word entailments based on context and effectively understands syntactic and semantic information in text. The single block architecture is very efficient, with 96.1% reduction in parameters compared to BERT. The proposed architecture offers 6.8% higher accuracy than the Vanilla Transformer architecture and is significantly improved over the various state-of-the-art models for sentiment analysis across three datasets in different domains.


## Task Definition
The proposed architecture was used for sentiment analysis tasks. Through the sentiment analysis task, one can determine the polarity of emotions or opinions in a sentence. The point to consider is that emotions can vary from context to context. For example, terms such as "bull" and "bear" are used in finance to describe positive and negative views, respectively. But in general context, do not convey polarized emotions. The term "negative", on the other hand, conveys a negative or pessimistic view, but does not convey any polarizing emotion when associated with the photographic film used in the film.

## Data Sets
The data sets can be obtained from the following links:

Movie Review: http://ai.stanford.edu/~amaas/data/sentiment/

SemEval 2014 Task 4: http://alt.qcri.org/semeval2014/task4/

Financial PhraseBank: https://www.researchgate.net/publication/251231364_FinancialPhraseBank-v10

