# The Code Unmasker

Large Language Models (LLMs) have made a significant impact on the technology industry, fundamentally transforming the landscape. However, this technology is not yet positioned to replace software engineers. Instead, it can serve as a powerful tool to assist engineers in various tasks, enhancing their daily workflows.

A notable example of such LLMs is Masked Language Models (MLMs), with `CodeBERT` being one prominent instance. Fine-tuned on a diverse dataset of programming languages, CodeBERT is capable of predicting masked tokens in a given text prompt, although its accuracy may vary depending on the input.

This project deploys a simple masked language model as a microservice. It operates alongside another microservice, which accepts code input from a client, processes it, and transmits it to the MLM microservice via a message queue system, specifically `RabbitMQ`.

-----

## Requirements

| Component     |    Version |
|---------------|------------|
| Docker        | `20.10.5`  |

-----

## Project Structure

-----

## Usage