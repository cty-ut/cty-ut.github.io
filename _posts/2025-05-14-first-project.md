---
title: "C-bot: My First AI Chatbot Project"
tags: [LLM, Project, Chatbot, Streamlit, Gemini API]
style: fill
color: info
description: A lightweight chatbot built with Streamlit and Google's Gemini API
layout: post
---

# C-bot: My Journey Building an AI Chatbot

![C-bot Screenshot](https://i.imgur.com/z97Pe9V.png)

## Project Overview

Based on a simple chatbot model I created recently, I've implemented several optimizations, added specific features, connected it to a cloud database, and deployed it on Streamlit Cloud. The Render database free tier has limitations, so I'm exploring alternative free database options. This represents my first significant project since formally beginning my programming journey. Despite its simple structure and various limitations, it has been an incredibly rewarding experience for me as a beginner.

## Development Process

### Technical Implementation

I built this application using Streamlit, a straightforward framework for web application development, powered by Google's free Gemini API (thanks Google!). The chatbot successfully implements several features including:

- Multi-modal file processing (documents, images, audio)
- Writing templates for common tasks
- RAG (Retrieval-Augmented Generation) knowledge base
- Multiple AI personas
- Conversation management

During development, I encountered numerous challenges and several complex bugs. However, through a combination of AI assistance and personal problem-solving, I ultimately created code that, while simple, maintains a clean and organized structure.

### Product Perspective

When compared to industry leaders like ChatGPT, Gemini, and Claude, this lightweight project has obvious limitations. Nevertheless, it effectively serves specific use cases. My philosophy as a developer is that even applications with limited functionality should address specific user needs, with careful attention paid to UI design.

I didn't approach this with the intention of creating a commercial product, which allowed me to omit certain features typically necessary for applications with large user bases. This was primarily an educational exercise, so I didn't invest in implementing certain product-oriented features. However, I maintained a product development mindset throughout the design process—a habit I consider essential for any developer.

## Future Directions

Looking ahead, I plan to continue optimizing this project in various ways, only considering a public release when it reaches a sufficient quality threshold. I also recognize the inherent limitations of the Streamlit framework—while excellent for prototyping, it's ultimately too lightweight for more complex applications.

In the future, I hope to utilize mainstream front-end and back-end frameworks to develop a more sophisticated full-stack project. This will help me expand my technical repertoire while maintaining a product-oriented mindset.

Let's grow together!

<div style="display: flex; gap: 20px; margin-top: 30px;">
  <a href="https://github.com/cty-ut/chatbot-with-RAG" style="display: inline-block; padding: 10px 20px; background-color: #24292e; color: white; text-decoration: none; border-radius: 5px; font-weight: bold;">
    <i class="fab fa-github"></i> GitHub Repository
  </a>
  
  <a href="https://chatbot-with-rag-j5kyqjupptewxu2ze9k6qc.streamlit.app/" style="display: inline-block; padding: 10px 20px; background-color: #FF4B4B; color: white; text-decoration: none; border-radius: 5px; font-weight: bold;">
    <i class="far fa-comment-dots"></i> Try C-bot Live
  </a>
</div>