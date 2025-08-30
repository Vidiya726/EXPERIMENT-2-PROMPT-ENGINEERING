# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:

# Comparative Analysis of Prompting Patterns in Large Language Models

## Introduction

Prompting is a core mechanism for interacting with Large Language Models (LLMs). The phrasing, structure, and clarity of a prompt strongly influence the quality of generated responses. This report analyzes various prompting patterns, comparing their effectiveness across different scenarios, and provides insights into their strengths, weaknesses, and best-use cases.


##  Objectives

* To examine how **different prompting techniques** affect model responses.
* To compare **broad/unstructured prompts** versus **refined/structured prompts**.
* To analyze **quality, accuracy, and depth** of responses across multiple scenarios.
* To derive insights for effective **prompt engineering strategies**.


## Overview of Prompting Patterns

Different prompting styles have emerged to guide LLM outputs. The key types include:

1. **Zero-Shot Prompting** – Directly asking without examples.
2. **Few-Shot Prompting** – Providing a few examples as context.
3. **Chain-of-Thought Prompting** – Asking the model to reason step by step.
4. **Instruction-Based Prompting** – Giving explicit, clear instructions.
5. **Role-Based Prompting** – Assigning the model a persona or role.

These patterns vary in complexity and effectiveness depending on the task.


##  Experiment Design

To evaluate prompting patterns, three **test scenarios** were designed:

* **Scenario A (Broad Prompt):** “Tell me about climate change.”
* **Scenario B (Refined Prompt):** “Explain the causes and effects of climate change in 150 words, suitable for high school students.”
* **Scenario C (Reasoning Task):** “If a train leaves City A at 9:00 AM at 60 km/h, and another leaves City B at 10:00 AM at 80 km/h towards City A, 200 km apart, when will they meet?”

Each prompt was tested with different prompting techniques.


## Test Cases and Scenarios

* **Broad Prompt (General Knowledge):** Evaluates general awareness and descriptive ability.
* **Refined Prompt (Instructional Writing):** Tests adherence to constraints (word limit, audience).
* **Reasoning Prompt (Logical Problem):** Measures step-by-step problem-solving ability.

These represent **realistic user interactions**: information-seeking, structured writing, and reasoning.


## Quality of Responses

* **Broad Prompts:** Produced vague, sometimes repetitive answers. Role-based prompting added perspective and clarity.
* **Refined Prompts:** Instruction-based prompting delivered the most accurate and constraint-following responses.
* **Reasoning Prompts:** Chain-of-Thought prompting consistently provided correct, step-by-step solutions.


## Accuracy and Depth Analysis

* **Zero-Shot:** Fast but less reliable for complex queries.
* **Few-Shot:** Improves consistency, formatting, and style but requires longer input.
* **Chain-of-Thought:** Achieves highest accuracy in logical tasks.
* **Instruction-Based:** Strong in tasks requiring word limits, structure, or formatting.
* **Role-Based:** Depth varies but highly effective for audience targeting.


## Key Insights

* **Broad prompts** → yield vague outputs; structured prompts improve clarity.
* **Instruction-based prompting** → ensures precise, controlled results.
* **Chain-of-Thought prompting** → best for reasoning and problem-solving.
* **Few-shot prompting** → stabilizes style but increases token cost.
* **Role-based prompting** → customizes tone and improves engagement.
  <img width="1200" height="675" alt="image" src="https://github.com/user-attachments/assets/d6c60736-5ff4-4dd0-8ccc-4144b12074a1" />



##  Output

<img width="1206" height="582" alt="image" src="https://github.com/user-attachments/assets/55b20149-ce1a-4a03-bdb1-d92236e58d68" />

## Result
This comparative study highlights the importance of prompt engineering in maximizing LLM performance.

* For **general knowledge queries**, role-based and instruction-based prompts yield clearer answers.
* For **structured writing**, instruction-based prompts ensure adherence to format and word limits.
* For **reasoning tasks**, Chain-of-Thought prompting delivers the most accurate results.

In conclusion, **there is no universal best prompting style**; the effectiveness depends on the **task type and context**. A thoughtful combination of patterns provides the best overall performance.


