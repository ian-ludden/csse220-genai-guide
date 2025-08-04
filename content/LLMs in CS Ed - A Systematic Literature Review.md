---
tags:
  - teaching
  - csse220
date: 2025-07-02
---
# Large Language Models in Computer Science Education: A Systematic Literature Review
- [DOI link](https://doi.org/10.1145/3641554.3701863)
- in SIGCSE 2025
## Main Takeaway:
An experiment in one Slovenian web dev course with second-year undergraduate students suggests LLM use for seeking additional explanations may be neutral/helpful, but high LLM use for generating code and debugging may hinder development of independent problem-solving skills. 
## Key Quotes:
### From 1. Introduction:
> we introduce the following research questions and hypotheses that frame our research: 
> RQ1. What is the overall impact of Large Language Model (LLM) usage on the final grades of undergraduate students in programming courses?  
> 
> H1. A higher average usage of LLMs for studying is negatively correlated with the final grades of undergraduate programming students.  
> 
> RQ2. How does the use of LLMs for generating code, seeking additional explanations, and   debugging specifically impact the final grades of undergraduate students in programming courses?  
> 
> H2a. The use of LLMs for generating code is negatively correlated with student final grades.  
> 
> H2b. The use of LLMs for seeking additional explanations does not significantly impact student  final grades.  
> 
> H2c. The use of LLMs for debugging is negatively correlated with student final grades. 
### From 4.1. Data Overview: 
> Looking at the overall use of LLMs, there is a visible trend of decreasing final grades with increased average LLM use. This generalized trend [...] suggests that greater reliance on LLMs might be associated with poorer performance in the controlled assignment, supporting the idea that while LLMs are helpful, they may also impede the development of independent problem-solving skills. 
### From 4.3. Results and Interpretations:
> These results indicate a significant impact of LLM usage on learning outcomes in the context of programming education. ==The significant inverse correlation associated with code generation and debugging suggests that reliance on LLMs for these critical thinking-intensive activities could be detrimental to students’ ability to independently solve programming tasks.== This might imply that while LLMs can be a valuable resource for learning and problem-solving, their use needs to be balanced with the development of independent coding skills, especially in an educational setting where the ultimate goal is to foster self-sufficiency in problem-solving. ==On the other hand, the non-significant correlation for seeking additional explanations suggests that this type of LLM usage does not have a clear negative impact on student performance==, potentially indicating that it serves more as a supplementary learning tool rather than a crutch that impedes skill development. 
## Abstract:
Large language models (LLMs) are becoming increasingly better at a wide range of Natural Language Processing tasks (NLP), such as text generation and understanding. Recently, these models have extended their capabilities to coding tasks, bridging the gap between natural languages (NL) and programming languages (PL). Foundational models such as the Generative Pre-trained Transformer (GPT) and LLaMA series have set strong baseline performances in various NL and PL tasks. Additionally, several models have been fine-tuned specifically for code generation, showing significant improvements in code-related applications. Both foundational and fine-tuned models are increasingly used in education, helping students write, debug, and understand code. We present a comprehensive systematic literature review to examine the impact of LLMs in computer science and computer engineering education. We analyze their effectiveness in enhancing the learning experience, supporting personalized education, and aiding educators in curriculum development. We address five research questions to uncover insights into how LLMs contribute to educational outcomes, identify challenges, and suggest directions for future research.
## BibTeX:
```bibtex
@inproceedings{10.1145/3641554.3701863,
author = {Raihan, Nishat and Siddiq, Mohammed Latif and Santos, Joanna C.S. and Zampieri, Marcos},
title = {Large Language Models in Computer Science Education: A Systematic Literature Review},
year = {2025},
isbn = {9798400705311},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3641554.3701863},
doi = {10.1145/3641554.3701863},
abstract = {Large language models (LLMs) are becoming increasingly better at a wide range of Natural Language Processing tasks (NLP), such as text generation and understanding. Recently, these models have extended their capabilities to coding tasks, bridging the gap between natural languages (NL) and programming languages (PL). Foundational models such as the Generative Pre-trained Transformer (GPT) and LLaMA series have set strong baseline performances in various NL and PL tasks. Additionally, several models have been fine-tuned specifically for code generation, showing significant improvements in code-related applications. Both foundational and fine-tuned models are increasingly used in education, helping students write, debug, and understand code. We present a comprehensive systematic literature review to examine the impact of LLMs in computer science and computer engineering education. We analyze their effectiveness in enhancing the learning experience, supporting personalized education, and aiding educators in curriculum development. We address five research questions to uncover insights into how LLMs contribute to educational outcomes, identify challenges, and suggest directions for future research.},
booktitle = {Proceedings of the 56th ACM Technical Symposium on Computer Science Education V. 1},
pages = {938–944},
numpages = {7},
keywords = {code generation, cs education, large language models},
location = {Pittsburgh, PA, USA},
series = {SIGCSETS 2025}
}
```