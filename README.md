# The-AI-Telco-Troubleshooting-Challenge
This project entails the finetuning of the Qwen 2.5 1.5 B Instruct LLM to realize a specialized edge-cloud large language model specialized to troubleshoot network faults. The grand aim is to enhance the accuracy of Qwen2.5-1.5B-Instruct to answer telco troubleshooting questions when answering telco troubleshooting questions in telelogs data.
## Evaluation
The evaluation metric for this challenge is Pass @ 1

This metric measures the ability of the model to produce a correct answer in a single attempt. It is computed by evaluating each of the 4 generated responses individually and averaging the correctness over all samples.

The finetuned model is evaluated on respective capability to troubleshoot network problems together with knowledge retention. Knowledge retention is the ability to maintain general knowledge accuracy after fine-tuning. The private dataset will include network faults whose data has a different structure than telelogs, and general knowledge questions.
