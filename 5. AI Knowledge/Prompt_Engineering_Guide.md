# Prompt Engineering Guide

## 1. Zero-Shot Prompting
Asking the model to perform a task without any examples.
*   *Example:* "Summarize this text in three bullet points."

## 2. Few-Shot Prompting
Providing a few examples (input-output pairs) within the prompt to guide the model's behavior.
*   *Example:* 
    *   Input: "Great service!" -> Sentiment: Positive
    *   Input: "Too slow." -> Sentiment: Negative
    *   Input: "Average experience." -> Sentiment: 

## 3. Chain of Thought (CoT)
Asking the model to explain its reasoning step-by-step before giving the final answer.
*   *Technique:* Add "Let's think step by step" to your prompt.

## 4. ReAct (Reason + Act)
A framework where the model generates both reasoning traces and task-specific actions (e.g., searching the web or using a calculator).

## 5. System Prompts
Defining the "persona" or "behavioral guardrails" of the AI at the start of a session.
*   *Example:* "You are a senior technical writer who specializes in simplifying complex cloud concepts."

Note: Updated on 2026-05-03
