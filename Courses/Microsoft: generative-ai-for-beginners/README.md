
# Introduction to Generative AI and Large Language Models

```How do Generative Pre-trained Transformer models work```

- **Tokenizer, text to numbers**: Large Language Models receive a text as input and generate a text as output. However, being statistical models, they work much better with numbers than text sequences. That’s why every input to the model is processed by a tokenizer, before being used by the core model. A token is a chunk of text – consisting of a variable number of characters, so the tokenizer's main task is splitting the input into an array of tokens. Then, each token is mapped with a token index, which is the integer encoding of the original text chunk.

Below is a visual example of how this might look

![tokenizer-example](https://github.com/kalistamp/llm/blob/main/Courses/Microsoft%3A%20generative-ai-for-beginners/images/tokenizer-example.png)


- **Predicting output tokens**: Given n tokens as input (with max n varying from one model to another), the model is able to predict one token as output. This token is then incorporated into the input of the next iteration, in an expanding window pattern, enabling a better user experience of getting one (or multiple) sentence as an answer. This explains why, if you ever played with ChatGPT, you might have noticed that sometimes it looks like it stops in the middle of a sentence.

- **Selection process, probability distribution**: The output token is chosen by the model according to its probability of occurring after the current text sequence. This is because the model predicts a probability distribution over all possible ‘next tokens’, calculated based on its training. However, not always the token with the highest probability is chosen from the resulting distribution. A degree of randomness is added to this choice, in a way that the model acts in a non-deterministic fashion - we do not get the exact same output for the same input. This degree of randomness is added to simulate the process of creative thinking and it can be tuned using a model parameter called temperature.

```The response may vary despite using the same prompt. An LLM is non-deterministic, the response vary, however, you can control its variance via a temperature setting. You also shouldn't expect it to do things perfectly, it's here to do the heavy-lifting for you which often means you get a good first attempt at something that you need to gradually improve.```



***
***
***


# Exploring and comparing different LLMs

### Foundation Models versus LLMs

The term Foundation Model was [coined by Stanford researchers](https://arxiv.org/abs/2108.07258?WT.mc_id=academic-105485-koreyst) and defined as an AI model that follows some criteria, such as:

- **They are trained using unsupervised learning or self-supervised learning**, meaning they are trained on unlabeled multi-modal data, and they do not require human annotation or labeling of data for their training process.
- **They are very large models**, based on very deep neural networks trained on billions of parameters.
- **They are normally intended to serve as a ‘foundation’ for other models**, meaning they can be used as a starting point for other models to be built on top of, which can be done by fine-tuning.


To further clarify this distinction, let’s take ChatGPT as an example. To build the first version of ChatGPT, a model called GPT-3.5 served as the foundation model. This means that OpenAI used some chat-specific data to create a tuned version of GPT-3.5 that was specialized in performing well in conversational scenarios, such as chatbots.

![Multimodel](https://github.com/kalistamp/llm/raw/main/Courses/Microsoft%3A%20generative-ai-for-beginners/images/Multimodal.png)


***
***
***

# NEXT

