---
layout: default
---

# GPT

![lrate](https://upload.wikimedia.org/wikipedia/commons/9/91/Full_GPT_architecture.png)

<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Full_GPT_architecture.png" alt="GPT">

Ábra 1: Transformer architektúra. Forrás: [wikipedia](https://en.wikipedia.org/wiki/Generative_pre-trained_transformer#/media/File:Full_GPT_architecture.png).

## GPT méretei

| Model | Architecture | Parameter count | Training data | Release date | Training cost
| --- | --- | --- | --- | --- | --- |
| GPT-1 | 12-level, 12-headed Transformer decoder (no encoder), followed by linear-softmax. | 117 million | BookCorpus: 4.5 GB of text, from 7000 unpublished books of various genres. | June 11, 2018 | 30 days on 8 P600 GPUs, or 1 petaFLOP/s-day.
GPT-2 | GPT-1, but with modified normalization | 1.5 billion | WebText: 40 GB of text, 8 million documents, from 45 million webpages upvoted on Reddit. | February 14, 2019 (initial/limited version) and November 5, 2019 (full version) | "tens of petaflop/s-day", or 1.5e21 FLOP.
GPT-3 | GPT-2, but with modification to allow larger scaling | 175 billion | 499 Billion tokens consisting of CommonCrawl (570 GB), WebText, English Wikipedia, and two books corpora (Books1 and Books2). | May 28, 2020 | 3640 petaflop/s-day, or 3.1e23 FLOP.
GPT-3.5 | Undisclosed | 175 billion | Undisclosed | March 15, 2022 | Undisclosed
GPT-4 | Also trained with both text prediction and RLHF; accepts both text and images as input. Further details are not public. | Undisclosed. Estimated 1.7 trillion | Undisclosed | March 14, 2023 | Undisclosed. Estimated 2.1e25 FLOP.

## Emberi agy méretei
- 86 milliárd neuron van az agyban.
- Minden neuronnak átlagosan körülbelül 7000 szinaptikus kapcsolata van más neuronokkal. Ez a szinapszisok számát 600 milliárd környékére teszi. Kisgyermekeknél a szinaptikus metszés komoly megkezdése előtt a becsült szám eléri az 1 kvadrilliót.