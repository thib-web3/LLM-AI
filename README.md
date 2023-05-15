# LLM-AI for EXCLUSIBLE

There are hundreds of LLMs on the market. This repository is a comparative list of the most established.

**Table Of Contents**
- [Pre-trained LLM](#pre-trained-llm)
- [LLM Training Frameworks](#llm-training-frameworks)
- [Useful Resources](#useful-resources)
- [Sources](#sources)

## Pre-trained LLM

### Paid License
| Name of Model | License | Accessibility                                        | Dataset Used for Training                               | Parameters  | Features                                                                                                                           | Author |
| ------------- | ------- | ---------------------------------------------------- | ------------------------------------------------------- | ----------- | ---------------------------------------------------------------------------------------------------------------------------------- | ------ |
| GPT-4         | Paid    | Limited access via ChatGPT and API (with a waitlist) | 45TB of various, including books, articles and websites | 175 billion | Almost any NLU, NLG, and multimodal task; advanced reasoning and instruction-following capabilities; improved safety and alignment | OpenAI |

### Research only
| Name of Model | License                     | Accessibility                                        | Dataset Used for Training                                                  | Parameters                                                                   | Features                                                                                                                           | Author                   |
| ------------- | --------------------------- | ---------------------------------------------------- | -------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ------------------------ |
| GPT-4         | Paid                        | Limited access via ChatGPT and API (with a waitlist) | 45TB of various, including books, articles and websites                    | 175 billion                                                                  | Almost any NLU, NLG, and multimodal task; advanced reasoning and instruction-following capabilities; improved safety and alignment | OpenAI                   |
| LLaMA         | Open source, Non-Commercial | App required                                         | CCNet, C4, GitHub, Wikipedia, Books, ArXiv, Stack Exchange                 | ?                                                                            | Exploring the capabilities and limitations of large language models for various natural language processing tasks                  | Meta AI                  |
| Alpaca        | CC BY-NC 4.0                | GitHub                                               | 52k examples generated by the Self-Instruct technique                      | 7 billion                                                                    | Instruction-following model, generates natural language texts from instructions                                                    | Standford Alpaca project |
| Vicuna        | Non-Commercial              | Hugging Face, GitHub                                 | Fine-tuned on user-shared conversations collected from ShareGPT            | 13 billion                                                                   | Generates natural language texts with high quality and diversity                                                                   | LMSYS                    |
| Pythia        | Apache 2.0                  | GitHub                                               | ?                                                                          | ?                                                                            | Autoregressive transformers across time and scale using various methods such as probing, attribution, and visualization            | EleutherAI               |
| GALACTICA     | ?                           | ?                                                    | Scientific articles, websites, textbooks, lecture notes, and encyclopedias | ?                                                                            | Science fine-tuned                                                                                                                 | Meta AI                  |
| StableLM      | CC BY-NC-SA 4.0             | Hugging Face                                         | The Pile                                                                   | 3 billion and 7 billion (alpha version), 15 billion and 65 billion (planned) | Conversational and coding tasks, with low parameter count and high efficiency                                                      | Stability AI             |

### Open Source
| GPT-4      | Paid                        | Limited access via ChatGPT and API (with a waitlist) | 45TB of various, including books, articles and websites                    | 175 billion                                                                  | Almost any NLU, NLG, and multimodal task; advanced reasoning and instruction-following capabilities; improved safety and alignment | OpenAI                   |
| ---------- | --------------------------- | ---------------------------------------------------- | -------------------------------------------------------------------------- | ---------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ------------------------ |
| LLaMA      | Open source, Non-Commercial | App required                                         | CCNet, C4, GitHub, Wikipedia, Books, ArXiv, Stack Exchange                 | ?                                                                            | Exploring the capabilities and limitations of large language models for various natural language processing tasks                  | Meta AI                  |
| Alpaca     | CC BY-NC 4.0                | GitHub                                               | 52k examples generated by the Self-Instruct technique                      | 7 billion                                                                    | Instruction-following model, generates natural language texts from instructions                                                    | Standford Alpaca project |
| Vicuna     | Non-Commercial              | Hugging Face, GitHub                                 | Fine-tuned on user-shared conversations collected from ShareGPT            | 13 billion                                                                   | Generates natural language texts with high quality and diversity                                                                   | LMSYS                    |
| Pythia     | Apache 2.0                  | GitHub                                               | ?                                                                          | ?                                                                            | Autoregressive transformers across time and scale using various methods such as probing, attribution, and visualization            | EleutherAI               |
| GALACTICA  | ?                           | ?                                                    | Scientific articles, websites, textbooks, lecture notes, and encyclopedias | ?                                                                            | Science fine-tuned                                                                                                                 | Meta AI                  |
| StableLM   | CC BY-NC-SA 4.0             | Hugging Face                                         | The Pile                                                                   | 3 billion and 7 billion (alpha version), 15 billion and 65 billion (planned) | Conversational and coding tasks, with low parameter count and high efficiency                                                      | Stability AI             |
| HuggingGPT | ?                           | ?                                                    | ?                                                                          | ?                                                                            | AI that delegates to other AI from HuggingFace (and ChatGPT) platform                                                              | Microsoft                |

## LLM Training Frameworks

| Name            | Link                                   | Feature                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| --------------- | -------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Alpa            | https://github.com/alpa-projects/alpa  | System for training and serving large-scale neural networks. Scaling neural networks to hundreds of billions of parameters has enabled dramatic breakthroughs such as GPT-3. Alpa aims to automate large-scale distributed training and serving with just a few lines of code.                                                           |
| DeepSpeed Chat  | https://github.com/microsoft/DeepSpeed | DeepSpeed is an easy-to-use deep learning optimization software suite that enables unprecedented scale and speed for DL Training and Inference.                                                                                                                                                                                                                                                                                                        |
| Megatron-LM     | https://github.com/NVIDIA/Megatron-LM  | Large, powerful transformer developed by the Applied Deep Learning Research team at NVIDIA. This repository is for ongoing research on training large transformer language models at scale.                                                                                                                                                                                                                                                            |
| Colossal-AI     | https://colossalai.org/                | user-friendly tools to kickstart                                                                                                                                                                                                                                                                                                                                                                                                                       |
| BMTrain         | https://github.com/OpenBMB/BMTrain     | Efficient large model training toolkit that can be used to train large models with tens of billions of parameters. It can train models in a distributed manner while keeping the code as simple as stand-alone training.                                                                                                                                                                                                                               |
| Mesh TensorFlow | https://github.com/tensorflow/mesh     | Formalizes and implements distribution strategies for your computation graph over your hardware/processors. Mesh TensorFlow is implemented as a layer over TensorFlow. |

## Useful Resources
- [Emergent Mind](https://chat.lmsys.org/?arena) - Chat with two models side-by-side and vote for which one is better! Includes a Leaderboard.
- [Run ChatGPT-like AI in 60 lines of code](https://jaykmody.com/blog/gpt-from-scratch/#input-%2F-output)

## Sources
- [Open-llms](https://github.com/eugeneyan/open-llms)
- [Awesome-llm](https://github.com/sanjibnarzary/awesome-llm)
- [Open Source ChatGPT like list](https://github.com/SunLemuria/open_source_chatgpt_list)
- [OS Fine-tuned LLMs](https://medium.com/geekculture/list-of-open-sourced-fine-tuned-large-language-models-llm-8d95a2e0dc76)
- [Awesome Open LLM](https://github.com/Hannibal046/Awesome-LLM#open-llm)
