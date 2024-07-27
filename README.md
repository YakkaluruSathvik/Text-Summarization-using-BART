# Text Summarization using BART

## Overview

This project implements a text summarization application using LangChain and HuggingFace models. It leverages bart-large-cnn LLM from HuggingFace to summarize text effectively. The summarization process employs a Recursive Summarization technique, which ensures comprehensive and coherent summaries by breaking down the text into manageable chunks and summarizing them iteratively.

## Features

- **Language Modeling**: Utilizes bart-large-cnn LLM from HuggingFace for generating text summaries.
- **Recursive Summarization**: Breaks down large texts into smaller sections, summarizes each section, and then combines these summaries to form a final coherent summary. This iterative approach enhances the accuracy and readability of the summaries.
- **Example Testing**: The technique is rigorously tested with various examples to ensure its effectiveness and reliability.
