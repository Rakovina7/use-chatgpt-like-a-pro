Best Practices Of Using Chatgpt Like a Pro


# Table of Contents

1. [Different models & alternatives](#different-models--alternatives)
2. [Common mistakes](#common-mistakes)
3. [Writing prompts](#writing-prompts)
4. [Different markdowns and styling](#different-markdowns-and-styling)
5. [Structured prompt](#structured-prompt)



# Different models & alternatives


## Models

[Click to see the refferance from OpenAI](https://openai.com/blog/chatgpt)

| Model | Uses Cases | Name | Status |
|----------|------------|------|------|
| GPT-3 | A set of models that can understand and generate natural language | Generative Pre-trained Transformer 3  | Public |
| GPT-3.5  | A set of models that improve on GPT-3 and can understand as well as generate natural language or code | Generative Pre-trained Transformer 3.5 | Private (20$) |
| GPT-4 | A set of models that improve on GPT-3.5 and can understand as well as generate natural language or code | Generative Pre-trained Transformer 4 | Private-Beta |
| Codex | A set of models that can understand and generate code, including translating natural language to code | OpenAI Codex  | Deprecated |
| DALL-E | A model that can generate and edit images given a natural language prompt | DALL-E  |  Private-Beta |


## Alternatives 

### [The Bai](https://chatbot.theb.ai/#/chat)




## Common mistakes

1. **Vague or Ambiguous Prompts**: Asking prompts that are too general or lack context can confuse ChatGPT and result in an incorrect or irrelevant answer. For example, asking "Is python a good programming language?" without specifying a use case won't provide an accurate answer. Instead, ask "I am about to develop a backend application, is python suitable for my use case? Write the cons and pros of using python as backend." to provide context.

2. **Complex Questions**: ChatGPT is designed to provide simple and straightforward answers, so asking complex questions that require in-depth analysis or scientific knowledge can result in unclear responses. Instead, ask specific and concise questions that ChatGPT can understand. 

3. **Lack of Context**: Providing enough context for ChatGPT to understand the request is crucial. Without enough information, ChatGPT may not provide an accurate answer. For example, asking "I am getting {{this error}} in my code, why is that happening?" without sending your actual code and expected behaviour will not help you.

4. **Unclear Language**: Using unclear language or phrases with multiple meanings can lead to confusion and incorrect answers from ChatGPT. Use clear and specific language to avoid this. For example, instead of asking "What's the name of the thing you put on a wall to hang stuff?" ask "What is the name of the item used to hang things on a wall?"

5. **Requesting Personal Opinion**: ChatGPT is an AI language model and does not have personal opinions. Asking ChatGPT questions that require personal opinions will result in an inability to provide an answer. If you want an opinion, ask him to act as the expert of field that your question is related, and ask him nicely to state, so for example instead of "What is your opinion about using ElasticSearch" ask "Act as a database administrator. My data includes nested json, tell me if I should use ElasticSearch or not, if not, then provide me alternatives that are better for my use case. I understand and accept that your answer could not be the best possible solution because you're an AI language model, however i wish to know your answer". The last part is very critical **I understand and accept that your answer could not be the best possible solution because you're an AI language model, however i wish to know your answer". The last part is very critical**


avoiding these common mistakes and providing clear and specific prompts with enough context, you can ensure accurate and relevant answers from ChatGPT. 


## Writing Prompts

Here are 5 useful prompt that you may use

1. **Act as a ..**: When answering, please assume the role of a professional and provide a detailed and accurate response. It is not necessary to specify a specific level of experience or years of knowledge, as this does not necessarily enhance the accuracy of the answer.

2. **Remember all our conversation again, and read this code that I will send you below. just write "OK" as respond to my text, and load the codes in your memory for future use case** : This prompt is used to inject up-to-date details to chatGpt, then you may rename the conversation and keep it and re-use it in future, for example chatgpt doesn't know django 4.2 is released but through django chanelogs, you may update him and have an updated chatgpt that knows django 4.2 is out and what has changed!

3. ** Remember all our conversation again and read the codes I've sent you previously. Now that you've seen all the code, I want you to do: ** This prompts is like the 

4. ** Read ... from book .. **: This prompt will  load resources from a book, and it helps very much with the answer that chatgpt is providing for you, because you'll redirect chatgpt to use more useful content.


5. ** Use documention, refferance and papers to backup your answer **: this prompt will redirect chatgpt to more scholar and academic answers



## Different markdowns and styling


Here are 2 useful prompt that you may use to change the styling of chatgpt answers

1. ** Sketch the table with column as ..../.../.../.../ **

2. ** write me an article in coding's markdown



## Structured prompt

The best structure for writing prompt is the following one

```

TASK:

...

-----------------------
PROMPT: 

1.  ...
2.  ...
3.  ...

-----------------------
MESSAGE: 


```
