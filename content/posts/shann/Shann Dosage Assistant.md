---
title: Shann Dosage Assistant
date: 2025-05-04
tags:
  - frank-shann
  - healthcare
  - ai
  - llm
  - mern
  - docker
---
Give the website a try, login credential needed (guest | wildernessguest098)

[www.badroosterdevbox.space](https://www.badroosterdevbox.space)
![software usage gif](/posts/shann/img/shann_output.gif)

## Problem Statement
Healthcare practitioners often struggle with accessing quick, accurate medication dosage information guideline. Traditional methods of looking up dosage information can be time-consuming, error-prone, and may not account for individual patient factors. Medical materials may be scattered across different sources, making it difficult to find consolidated information when needed.

## Aim

Shann Dosage Assistant aims to solve the challenge of providing reliable, accessible, and personalised medication dosage information by coupling Frank Shann's timeless paper and an intelligent assistant that leverages modern technology to:

1. Provide fast access to medication dosage information
2. Provide tight contextual boundary to dosage-related queries according to Shann's guidance
3. Integrate large language models to understand natural language questions about medications discussed
4. Maintain a searchable database of medication information
5. Provide information in a user-friendly, accessible interface

## Solution Approach

Shann MERN AI assistant addresses these challenges through:

1. **AI-Powered Responses**: Integration of large language models (Gemini 2.0 Flash) through Google GenAI to understand and respond to natural language queries about medication dosages
2. **Database Integration**: MongoDB for storing and retrieving medication information
3. **Modern Web Interface**: React-based frontend with Chakra UI for an intuitive, responsive user experience
4. **RAG Architecture**: Un-vectorised retrieval-augmented generation to provide accurate, contextualised responses
5. **Full-Stack Integration**: MERN + Docker stack implementation allowing for scalable and maintainable application architecture

## Intended Audience

- Healthcare professionals (doctors, nurses, pharmacists)
- Medical students and healthcare trainees
- Other professionals managing medication regimens

## Expected Impact

By providing an intelligent dosage assistant, the system aims to:

- Provide access to reliable medication information
- Reduce medication errors
- Save time for healthcare providers
- Provide evidence-based medical suggestion
- Provide medical guidance where senior resources are scarce

## Solution Architecture

![solutions architect diagram](/posts/shann/img/shann_architecture.png)

## Technical Specification

This solution leverages modern AI capabilities while maintaining a focus on providing practical, reliable medication information through an accessible interface. This is a full-stack MERN (MongoDB, Express, React, Node.js) application which incorporates LLM services through Google GenAI Gemini Flash 2.0 model, connected using LangChain framework.  These services are load balanced and routed by NGINX while containerised using Docker, giving a scalable and maintainable solution.

For full technical detail, please visit the [Github Repository](https://github.com/bad-rooster/shann-mern)

## Further Improvements


## Acknowledgements  
- [Prof. Frank Shann](https://findanexpert.unimelb.edu.au/profile/2416-frank-shann) - Textbook Author
- [Timotius Hanjaya GP](https://www.linkedin.com/in/timotius-dr/) - Medical Advisor
- [Google Gen AI](https://cloud.google.com/ai/generative-ai) - AI model used
- [LangChain](https://www.langchain.com/) - Framework for LLM applications  
- [Ollama](https://ollama.ai/) - Run LLMs locally
- [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling  
- [React](https://reactjs.org/) - A JavaScript library for building user interfaces  
- [MongoDB](https://www.mongodb.com/) - Document database  
- [Express](https://expressjs.com/) - Web framework for Node.js  