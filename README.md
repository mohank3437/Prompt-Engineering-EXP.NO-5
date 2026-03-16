

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT

Introduction

Artificial Intelligence (AI) systems such as large language models rely heavily on prompts to understand user requests and generate meaningful responses. A prompt is the instruction or input given to the AI model to guide its output. The way a prompt is structured can significantly affect the accuracy, relevance, and quality of the response.

Prompting patterns are systematic ways of designing prompts so that the AI model can perform tasks effectively. Different prompting techniques are used depending on the type of task, such as reasoning, translation, summarization, or explanation. This study analyzes several commonly used prompting patterns and compares their performance using different test scenarios.

Objectives of the Study

The main objectives of this study are:

* To understand different prompting patterns used in AI systems

* To compare the effectiveness of these prompting methods

* To evaluate their performance through practical test scenarios

* To identify which prompting pattern works best for specific tasks

Types of Prompting Patterns
1. Zero-Shot Prompting

Zero-shot prompting refers to asking the AI model to perform a task without providing any prior examples. The model relies entirely on its pre-trained knowledge to generate the response.

Example Prompt

Translate the following sentence into Spanish:
"I love learning new technologies."

Output

Me encanta aprender nuevas tecnologías.

Advantages

* Simple and quick to use

* Requires minimal prompt design

* Suitable for general knowledge tasks

Limitations

* May produce inaccurate results for complex tasks

* Lacks guidance for pattern recognition

2. Few-Shot Prompting

Few-shot prompting provides a small number of examples before asking the model to perform the task. These examples help the AI understand the expected format or pattern.

Example Prompt

English → French
Hello → Bonjour
Good evening → Bonsoir
Thank you → Merci
Good morning → ?

Output

Bonjour

Advantages

* Improves accuracy compared to zero-shot prompting

* Helps AI recognize patterns more effectively

Limitations

* Requires carefully selected examples

* Longer prompts may increase processing time

3. Chain-of-Thought Prompting

Chain-of-Thought prompting encourages the model to solve problems step by step before providing the final answer. This technique improves reasoning capabilities.

Example Prompt

If a book costs ₹50 and you buy 4 books, how much money do you spend? Explain step by step.

Output

Step 1: Cost of one book = ₹50
Step 2: Number of books purchased = 4
Step 3: Total cost = 50 × 4
Step 4: Total cost = ₹200

Final Answer: ₹200

Advantages

* Improves logical reasoning and accuracy

* Useful for mathematical and analytical problems

Limitations

* Generates longer responses

* Requires more computational resources
4. Role-Based Prompting

In role-based prompting, the AI model is assigned a specific role or perspective before answering the question.

Example Prompt

Act as a software engineer and explain the concept of data structures.

Advantages

* Produces responses with appropriate tone and expertise

* Helpful for educational or professional explanations

Limitations

Effectiveness depends on prompt clarity

5. Instruction-Based Prompting

Instruction-based prompting clearly specifies what the AI should do and how the output should be structured.

Example Prompt

Explain cloud computing in 5 bullet points.

Advantages

* Provides structured responses

* Easy to understand and evaluate

Limitations

May limit creative responses

Test Scenarios

To evaluate the effectiveness of different prompting patterns, several test scenarios were conducted.

<img width="870" height="309" alt="image" src="https://github.com/user-attachments/assets/936ce43d-6be5-4cd5-8ae3-d6b8d79ea26e" />

<img width="789" height="237" alt="image" src="https://github.com/user-attachments/assets/c45ada93-221d-47ee-bfe0-33f371525f63" />

<img width="832" height="343" alt="image" src="https://github.com/user-attachments/assets/5e4dcbab-c27a-47bb-a412-93ff9f55e0f8" />

<img width="841" height="318" alt="image" src="https://github.com/user-attachments/assets/684a0265-d130-4e8a-b9f8-508f630f6803" />

<img width="933" height="398" alt="image" src="https://github.com/user-attachments/assets/7056e630-5ed0-4585-b7fe-5d3374b873c9" />

Findings

Based on the test scenarios conducted in this study, several observations were made:

1.Zero-shot prompting works well for simple tasks but may struggle with complex reasoning problems.

2.Few-shot prompting significantly improves accuracy by providing examples.

3.Chain-of-thought prompting produces the best results for logical and mathematical problems.

4.Role-based prompting improves explanation quality and makes responses more informative.

5.Instruction-based prompting ensures well-structured and organized outputs.

Conclusion

Prompting patterns play a crucial role in improving the performance of AI systems. The study shows that no single prompting technique is ideal for all tasks. Instead, the choice of prompting pattern should depend on the complexity and nature of the task.

For simple tasks, zero-shot prompting is sufficient, while complex reasoning tasks benefit from chain-of-thought prompting. Few-shot prompting improves pattern recognition, and role-based prompting enhances explanation quality. Future research can focus on combining multiple prompting techniques to achieve even better results in AI applications.

# RESULT: The prompt for the above said problem executed successfully
