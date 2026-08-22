# Benchmark Design

## Purpose
The purpose of this benchmark is to evaluate and compare hallucination behaviour in different LLM's model in different domain and difficulty.

The benchmark will use standardized questions and evaluation criteria to ensure that all models are tested under comparable conditions..
## Domains
The benchmark will contain 6 or more domains.
The final domains will be selected based on:
1. The difficulty of the domain for human and LLM's both.
2. Relevance to real world and its use.
3. Importance of the domain in real world
4. Sufficient diversity between domains.

Final domians: To be decided.

## Question Types

Benchmark may include:
1. Fact check questions.
2. Code-related/Bug fix problems
3. MCQ type questions
4. Explanation-based questions
5. Multi step problem solving questions
6. Questions involving potentially nonexistent or misleading information

## Difficulty

Questions will be divided into difficulty levels.

Difficulty will be determined using factors such as:
1. Complexity of the question (Whether it is straight forward or not)
2. Length of the question
3. Common mistakes questions
4. availability of the answer

## Standardized Testing Conditions

All models will receive:

- The same question
- The same prompt structure
- No previous conversation context
- Clearly documented generation parameters
- A predefined response format where possible

Model-specific settings and limitations will be recorded.

## Benchmarks flow
Question Dataset
       ↓
Question + Standard Prompt
       ↓
Selected LLM
       ↓
Model Response
       ↓
Automatic Evaluation
       +
Human Verification
       ↓
Final Labels
       ↓
Statistical Analysis
       ↓
Results and Comparison

