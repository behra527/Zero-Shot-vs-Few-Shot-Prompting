# Zero-Shot vs Few-Shot Prompting

![Python](https://img.shields.io/badge/Python-3.13-blue)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-orange)
![Gemini API](https://img.shields.io/badge/Gemini%20API-LLM-green)
![Prompt Engineering](https://img.shields.io/badge/Prompt%20Engineering-Zero--Shot%20%7C%20Few--Shot-purple)
![Status](https://img.shields.io/badge/Status-Completed-success)

## Overview

This project is a practical experiment comparing zero-shot and few-shot prompting for a customer-support message classification task.

The experiment uses the Gemini API in Google Colab. Both prompting approaches use the same classification task and test dataset so their outputs can be compared under the same conditions.

## Objective

The main objectives are to:

* Understand zero-shot prompting.
* Understand few-shot prompting.
* Create and test both prompting approaches.
* Use examples to provide additional task-specific guidance.
* Evaluate and compare LLM outputs.

## Zero-Shot Prompting

Zero-shot prompting provides the model with instructions and category definitions but does not provide examples.

In this project, the model is asked to classify customer messages into:

* Billing
* Technical
* Account

## Few-Shot Prompting

Few-shot prompting provides the same instructions along with examples showing customer messages and their expected categories.

The examples help demonstrate the expected input-output pattern before the model receives a new message.

## Evaluation

The same test dataset is used for both approaches.

The evaluation focuses on:

* **Accuracy**  how many predictions match the expected category.
* **Format Compliance**  whether the model returns a valid category in the required format.
* **Consistency**  whether the model produces stable outputs for the same task.

## Tools & Technologies

* Python
* Google Colab
* Gemini API
* Pandas
* Prompt Engineering

## Project Structure

```text
zero-shot-vs-few-shot-prompting/
│
├── Zero-Shot_vs_Few-Shot_Prompting.ipynb
└── README.md
```

## Key Learning

This project demonstrates how different prompting strategies can influence LLM behavior without changing the underlying model.

It also provides practical experience in designing prompts, creating a controlled test dataset, and evaluating LLM outputs using simple and measurable criteria.

## Status

The zero-shot and few-shot prompting workflow and evaluation framework have been completed.
