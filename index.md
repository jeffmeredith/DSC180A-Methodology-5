# Jeffrey Meredith
# jemeredith@ucsd.edu

## Section B03
## Mentor: Arya Mazumdar

### 1. What is the most interesting topic covered in your domain this quarter?
The most interesting topic covered this quarter was using the PAIR algorithm to jailbreak various LLM models. PAIR works by pitting an attacker LLM against a target LLM. The attacker LLM has a system prompt instructing it to try a variety of jailbreak methods as well as instructing it on how to improve based on its chat history with the target LLM. Additionally, the system prompt changes if enough iterations are explored without success. The other topic we covered was the exploration of defenses against jailbreak attacks such as Semantic Smoothing LLM.

### 2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.
In Quarter 2, I'd consider exploring the effectiveness of a new jailbreak defense mechanism that builds on Semantic Smoothing. Semantic Smoothing disrupts the jailbreak prompt with character level swaps. I think another way to disrupt the jailbreak prompt is by using another LLM to simply translate or paraphrase the incoming prompt so that the meaning is preserved while the wording is changed. This could potentially prevent the target LLM from producing objectionable content.

### 3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?
I would change my approach by spending less time on implementing the PAIR algorithm on so many different LLMs and just implementing it on one or two so that we could start focusing more on implementing various defense mechanisms. Spending more time on implementing and studying a wide variety of defense mechanisms against jailbreaks would prepare us better for Quarter 2, when we will try to make a new and improved defense mechanism. Additionally, I want to study exactly how models like Claude and Llama-2 are so much more difficult to jailbreak than other models.

### 4. What other techniques would you be interested in using in your project?
I'd also be interested in utilizing white-box access to open-source LLMs such as Vicuna and Llama-2. This is complicated because making full use of white-box access means studying the actual weight values and making insights from those. This requires use of neural networks and other complex models because there are millions of parameters and weights. We can not simply create a simple visualiztion to understand the context of these weights because there are too many.