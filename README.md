Best Practices Of Using Chatgpt Like a Pro


# Table of Contents

1. [Different models](#different-models--alternatives)
2. [Alternatives & Tools](#alternatives)
3. [Common mistakes](#common-mistakes)
4. [Writing prompts](#writing-prompts)
5. [Different markdowns and styling](#different-markdowns-and-styling)
6. [Structured prompt](#structured-prompt)
7. [Examples](#examples)



# Different models & alternatives


## Models

[Click to see the refferance from OpenAI](https://platform.openai.com/docs/models)

| Model | Uses Cases | Name | Status |
|----------|------------|------|------|
| GPT-3 | A set of models that can understand and generate natural language | Generative Pre-trained Transformer 3  | Public |
| GPT-3.5  | A set of models that improve on GPT-3 and can understand as well as generate natural language or code | Generative Pre-trained Transformer 3.5 | Private (20$) |
| GPT-4 | A set of models that improve on GPT-3.5 and can understand as well as generate natural language or code | Generative Pre-trained Transformer 4 | Private-Beta |
| Codex | A set of models that can understand and generate code, including translating natural language to code | OpenAI Codex  | Deprecated |
| DALL-E | A model that can generate and edit images given a natural language prompt | DALL-E  |  Private-Beta |


## Alternatives

  #### [The Bai - A free chatgpt that uses 3.5](https://chatbot.theb.ai/#/chat)
  #### [Open-source fully autonomous application showcasing Chat GPT](https://github.com/Torantulino/Auto-GPT)



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

3. **Remember all our conversation again and read the codes I've sent you previously. Now that you've seen all the code, I want you to do:** This prompts is like the 

4. **Read ... from book ..** : This prompt will  load resources from a book, and it helps very much with the answer that chatgpt is providing for you, because you'll redirect chatgpt to use more useful content.


5. **Use documention, refferance and papers to backup your answer** : this prompt will redirect chatgpt to more scholar and academic answers



## Different markdowns and styling


Here are 2 useful prompt that you may use to change the styling of chatgpt answers

1. **Sketch the table with column as ..../.../.../.../**
Example:
```
compare python and java

use a table
Column 1 python, column 2 Java
Rows: Pros / Cons / Speed / Clean code pratices / careers / use cases / and include 10 other row as well
```

2. **write me an article in coding's markdown**



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
INPUT: 


```

### Example
```
TASK:
Fixing grammar mistake & paraphrasing

-----------------------
PROMPT: 
1. Act as grammarly extension which fixes grammar mistake
2. Rephrase 99% of words in the article
3. Rewrite it using a Human Tone
4. Make it to not be detected by plagiarism checker


-----------------------
INPUT: 

Astronomers using the James Webb Space Telescope (JWST) have just discovered the four most distant galaxies ever seen, located a little over 13 billion light-years from Earth. This means astronomers are seeing what galaxies looked like only 300 to 500 million years after the Big Bang, in the infancy of our now almost 14 billion-year-old universe, according to two new(opens in new tab) studies(opens in new tab) published April 4 in the journal Nature Astronomy.

"The frontier is moving almost every month," Pieter van Dokkum(opens in new tab), a professor of astronomy at Yale University who was not involved in the studies, said in a commentary(opens in new tab) published in Nature Astronomy. There are now "only 300 million years of unexplored history of the universe between these galaxies and the Big Bang," van Dokkum added.

This may sound like familiar news, as several studies have recently claimed possible detections of even older galaxies using JWST in the past few months. The four newly discovered galaxies are different, though — astronomers have actually confirmed these are ancient galaxies and not some other celestial body, or a closer-by galaxy masquerading as a more distant one.
```



## Examples

[Django Expert Support Bot](https://github.com/ManiMozaffar/django-expert-bot)
