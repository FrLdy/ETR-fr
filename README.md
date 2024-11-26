# Easy-to-Read Generation for Cognitive Impaired People

## Introduction

This project addresses the digital divide by focusing on text generation for people with cognitive disabilities.
It introduces the ETR-fr dataset, which contains 523 pairs of French texts aligned with the [Easy-to-Read (ETR) European standard](https://european-union.europa.eu/easy-read_en).
ETR texts use simple vocabulary, clear structure, concrete examples, and contextual summaries to meet the needs of this population.
Additionally, the project presents a generative model fine-tuned using [LoRA](https://huggingface.co/moussaKam/mbarthez) on the [mBARTHez](https://github.com/moussaKam/BARThez) backbone.
The model demonstrates strong performance in generating ETR content compared to full fine-tuning and [Prefix-Tuning](https://github.com/XiangLi1999/PrefixTuning) on [BARTHez](https://github.com/moussaKam/BARThez), [Mistral-7B](https://mistral.ai/fr/news/announcing-mistral-7b/) and [mBART](https://github.com/facebookresearch/fairseq/tree/main/examples/mbart).
The findings highlight the effectiveness of computer-aided text generation for this purpose.

## Available Adapters and Models

<center>

| Model | LoRA   | Prefix           | Full Fine-Tuning |
| ----- | :----: | :------: | :----------------: |
|**mBART**| [Link](https://osf.io/download/xt2vy/) (104.8 MB)          | [Link](https://osf.io/download/fr4sj/) (147.6 MB)           | [Link](https://osf.io/download/6qfys/) (2.1 GB)                                |
| **mBARThez**            |     [Link](https://osf.io/download/p39w8/) (105.0 MB)     | [Link](https://osf.io/download/u93fs/) (577.4  MB)              | [Link](https://osf.io/download/9dwbh/) (1.7 GB)                                  |
| **mT5**            | [Link](https://osf.io/download/jmzg2/) (78.8 MB)          |             [Link](https://osf.io/download/zh6vn/) (218.4 MB) |                                  [Link](https://osf.io/download/wfazd/) (1.8 GB)|
| **Mistral-7B**            | [Link](https://osf.io/download/ctx8g/) (278.9 MB)          |             [Link](https://osf.io/download/jsp5c/) (2.0 GB)| - |
<!--| **xxx**            | [Link]()          |             [Link]() |                                  [Link]()|-->

</center>

<!--## On AdapterHub and HuggingFace-->

<!--Our adapters (LoRA and Prefix) are available on [AdapterHub](https://adapterhub.ml) and full finetuned on [HuggingFace](https://huggingface.co):-->

<!--## For Inference-->
<!---->
<!--```python-->
<!--import adapters-->
<!--import transformers-->
<!--```-->
<!---->
<!--## Hyperparameters Search-->
<!---->
<!--### Best Hyperparameters-->
