# Question Generation with Transformers
![image](https://github.com/Aftabbs/Unlocking-the-Power-of-NLP-Automatic-Question-Generation/assets/112916888/f807e137-a1c6-48c6-9849-e4e2c166b101)

![image](https://github.com/Aftabbs/Unlocking-the-Power-of-NLP-Automatic-Question-Generation/assets/112916888/795b15c2-f5a4-493e-99d2-0309d9a51b12)

Welcome to the Question Generation project using Transformers! This project demonstrates how to utilize state-of-the-art natural language processing techniques to automatically generate questions from a given context and answers. We combine the power of transformers, Flash Text, and the T5 model to create this question generation system.

## Table of Contents
- [Introduction](#introduction)
- [Libraries Used](#libraries-used)
- [Why Transformers?](#why-transformers)
- [Why T5 Conditional?](#why-t5-conditional)
- [Pretrained Model](#pretrained-model)
- [Use Case](#use-case)
- [Getting Started](#getting-started)
- [Enhancements and Future Scope](#enhancements-and-future-scope)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Question generation is a challenging natural language processing task that involves creating meaningful questions from provided context and answers. This project showcases how to perform this task effectively using transformer-based models, Flash Text for keyword extraction, and the T5 model for question generation.

## Libraries Used

The project leverages a variety of libraries to accomplish its tasks:

- [transformers](https://github.com/huggingface/transformers): A powerful library for working with transformer models.
- [flashtext](https://github.com/vi3k6i5/flashtext): A library for efficient keyword extraction.
- [pke](https://github.com/boudinfl/pke): Python Keyphrase Extraction toolkit for keyword extraction.
- [nltk](https://www.nltk.org/): Natural Language Toolkit for various NLP tasks.
- [gradio](https://github.com/gradio-app/gradio): Gradio is used for creating easy-to-use user interfaces for interacting with the question generation system.
- [pandas](https://pandas.pydata.org/): Pandas is employed for data manipulation and organization.


## Why Transformers?

Transformers have revolutionized natural language processing tasks due to their ability to capture contextual information effectively. They excel in tasks like question generation by understanding the relationships between words and generating coherent questions.

## Why T5 Conditional?

The T5 (Text-to-Text Transfer Transformer) model is a versatile transformer architecture that can be applied to a wide range of text generation tasks, including question generation. Its "conditional generation" capability makes it well-suited for creating questions based on context and answers.

## Pretrained Model

In this project, we leverage a pretrained T5 model specifically fine-tuned for question generation. The pretrained model we used is `ramsrigouthamg/t5_squad_v1`. Fine-tuning on a question-answering dataset makes it adept at generating questions from context and answers.

## Use Case

The primary use case of this project is to automatically generate questions from provided context and answers. This can be valuable for various applications, including educational platforms, chatbots, and content generation. Users can input context and answers, and the system generates meaningful questions to enhance interaction and engagement.

## Getting Started

To get started with the project, follow these steps:
1. Install the required libraries: `pip install transformers flashtext pke nltk`
2. Load the pretrained T5 question generation model.
3. Preprocess your context and answers.
4. Call the `get_question` function to generate questions.

## Enhancements and Future Scope

1. **Multi-Lingual Support:** Extend the project to support question generation in multiple languages.
2. **Fine-Tuning:** Fine-tune the T5 model on domain-specific data to improve question quality for specific topics.
3. **Context Expansion:** Incorporate more extensive context analysis techniques for generating context-aware questions.
4. **Interactive Web Interface:** Create a user-friendly web interface for users to input context and answers and receive questions interactively.
5. **Performance Metrics:** Implement evaluation metrics to quantify question quality and refine the generation process.

## Contributing

Contributions to the project are welcome! If you have suggestions, bug reports, or enhancements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
