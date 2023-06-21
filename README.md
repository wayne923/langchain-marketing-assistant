# How to Automate Youtube and Blog Content with LangChain & OpenAI: A Step-by-Step Guide

This repo contains the code for AI-powered Marketing Assistant that uses LangChain and OpenAI to streamline your content creation process. Using LangChain you will create a SequentialChain that consists of a series of chains  - a blog post chain, a YouTube script chain, and a YouTube visuals chain.

## The detailed step-by-step guide can be found in either our YouTube or Medium article below.

YouTube
https://www.youtube.com/@principlesofai/videos

Medium
https://medium.com/@wayne923/fc6ed231ffa6

![alt text](https://github.com/wayne923/langchain-marketing-assistant/blob/main/marketing_assistant_image.png?raw=true)

## Overview of the Code

The code consists of an app.py file that is used to set up and run the AI-powered marketing assistant.

The app.py includes:
* Setting up the environment
* Building Blocks of LangChain
* Mastering the Basics of Chains in LangChain
* Integrating the assistant with Streamlit to build a Web App

The .env file is used to securely store your OpenAI API key.

### Example of what you will learn

```
# LLMChain Example

# Model
llm = OpenAI(temperature=0.9)

# Prompt
blog_prompt_template = PromptTemplate(
    input_variables = ['product_description'],
    template = 'Write a blog post on {product_description}'
)

# Chain
blog_chain = LLMChain(llm=llm, prompt=blog_prompt_template, verbose=True)

# Run
product_description = 'best eco-friendly coffee'
blog_chain.run(product_description)
```

## Follow me to stay updated

YouTube - www.youtube.com/@principlesofai

Instagram - www.instagram.com/principlesofai

LinkedIn - www.linkedin.com/in/wayn9/
