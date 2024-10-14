# Easy-to-Read Generation for Cognitive Impaired People

## Introduction

This project addresses the digital divide by focusing on text generation for people with cognitive disabilities.
It introduces the ETR-fr dataset, which contains 523 pairs of French texts aligned with the [Easy-to-Read (ETR) European standard](https://european-union.europa.eu/easy-read_en).
ETR texts use simple vocabulary, clear structure, concrete examples, and contextual summaries to meet the needs of this population.
Additionally, the project presents a generative model fine-tuned using [LoRA](https://huggingface.co/moussaKam/mbarthez) on the [mBARTHez](https://github.com/moussaKam/BARThez) backbone.
The model demonstrates strong performance in generating ETR content compared to full fine-tuning and other tuning methods on [BARTHez](https://github.com/moussaKam/BARThez), [Mistral-7B](https://mistral.ai/fr/news/announcing-mistral-7b/) and [mBART](https://github.com/facebookresearch/fairseq/tree/main/examples/mbart).
The findings highlight the effectiveness of computer-aided text generation for this purpose.

## 
