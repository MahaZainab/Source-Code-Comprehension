# CodeQA

## Description:
It is a questioning answering dataset.  QA-based source code comprehension is the ability to read a code snippet and then answer questions about it, which requires understanding both source code and natural language. 

Given a code snippet and a question, a textual answer need to be generated.

#### Note:  
QA-based source code comprehension has direct use in education to facilitate programming learning, where a system automatically answers questions about codes that someone has read.  A more gen
eral use is to help improve software maintenance since it can advance the readability of code.

Moreover, it can provide diverse information that can be leveraged to help perform a wide range of software engineering tasks, such as bug detection, specification inference, testing and code synthesis.

## Dataset
Java Question Anwer Pairs: 119,7787

[Python](https://github.com/MahaZainab/CodeQA/tree/main/python) Question Anwer Pairs: 70,085 


[Dataset Link](https://github.com/jadecxliu/CodeQA) 
## Methodology
This paper has done construction process(from comments) and conduct semantic analysis.

## Experiments:
-Seq2Seq

-Transformers

## Aim:

1. Extract only Python code from the dataset.

Answer: The current experiment is done on Python Dataset.

2. Start with a small subset of dataset  (~50 examples)

Answer: 70,085 question answer pairs are used 

3. Try with an open-source LLM of your choice to generate the answers

Answer:  Llama is used.

4. Compare with gold-annotated answers.

Answers: Both are giving satisfactory answers. Accuracy of LLM is higher than implemented
Now assume LLMs are deployed in a tutoring system to teach students coding. 
1. How good are LLMs providing answers?

2. Can LLMs provide reasoning to the answers?

3. Can LLMs teach step-by-step?

