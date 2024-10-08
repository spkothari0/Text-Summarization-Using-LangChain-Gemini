# Text Summarization Using Langchain and OpenAI GPT and Gemini

This project demonstrates various text summarization methods utilizing the Langchain framework and Gemini-pro model. The tool can summarise large bodies of text efficiently and effectively, leveraging advanced language processing techniques.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)

## Introduction

Text summarization is performed using various techniques and the summarization model provided by LangChain with different techniques to handle simple to large and complex text. Text summarization is the process of condensing a piece of text to a shorter version, retaining the most important information. This project employs Langchain and Gemini's Pro model to provide high-quality summaries of input texts. The application supports various text formats and is designed for easy integration and deployment.

## Features

- Summarizes long texts into concise summaries.
- Utilizes Gemini's Pro to generate summaries.
- Used customized prompt and chains

## Installation

To get started with the project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/spkothari0/Text-Summarization-Using-LangChain-Gemini.git
   cd Text-Summarization-Using-LangChain-Gemini
   ```

2. Install dependencies using Poetry:

   ```bash
   poetry install --no-root
   ```

3. Set up your environment variables:

   - Rename the `.env.example` file to `.env` and update the variables inside with your own values. Example:

   ```bash
   mv .env.example .env
   ```

4. Activate the Poetry shell to run the examples:

   ```bash
   poetry shell
   ```

5. Run the code examples:

   Run the ipynb file using the kernel that was created in the above step.
