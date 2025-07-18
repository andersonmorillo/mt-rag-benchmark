# MTRAGEval

🎉 Welcome to MTRAGEval! MTRAGEval is a task for Evaluating Multi-Turn RAG Conversations at [SemEval 2026](https://semeval.github.io/SemEval2026/). 🎉

# Join Our Mailing List!

[MTRAGEval Mailing List](https://groups.google.com/g/mtrageval)

# Training and Trial Data

The MTRAG Benchmark is released as the trial and training data for MTRAG. You can access the full dataset [here](../../README.md)

# 📋 Tasks

* Task A: Retrieval Only
* Task B: Generation with Reference Passages (Reference)
* Task C: Generation with Retrieved Passages (RAG)

Read more about our tasks in our [proposal](proposal.pdf)

# Evaluation Scripts

Stay Tuned! Coming Soon!

# 📆 Timeline (Tentative)

* Sample and Training data ready 15 July 2025
* Evaluation start 10 January 2026 Task A and C
* Evaluation end 20 January 2026 Task A and C
* Evaluation start 21 January 2026 Task B
* Evaluation end by 31 January 2026 Task B
* Paper submission due February 2026
* Notification to authors March 2026
* Camera ready due April 2026
* SemEval workshop Summer 2026 (co-located with a major NLP conference)


<!-- ## Task A: Retrieval Only

Given the conversations, use the following [script](/scripts/conversations2retrieval.py) to convert the conversation into input to send the retriever. You can achieve this anyway you desire such as a rewrite of the conversation, using only the last question, trying to generate an answer etc.. 

[Conversations](/human/conversations/conversations.json)  
[Corpora](/corpora/)  
[Sample Data](/human/retrieval_tasks/)  

Your final output should be a tsv file that includes the query-id and corpus-id for all relevant passages per question.

### Output Format:

```
query-id \t corpus-id \t score
```

The score will not be used, so it can always be 1. The corpus-id is per line. If the query has multiple relevant passages, they should be on separate lines. Sample output can be seen in the Sample Data folder above.

## Task B: Generation with Reference Passages

[Data](/human/generation_tasks/reference.jsonl)

## Task C: Full RAG

[Data](/human/generation_tasks/reference+RAG.jsonl)

## Evaluation Scripts -->

## Task Organizers

Sara Rosenthal [✉️](sjrosenthal@us.ibm.com)  
Yannis Katsis [✉️](yannis.katsis@ibm.com)  
Vraj Shah [✉️](vraj@ibm.com)  
Marina Danilevsky [✉️](mdanile@us.ibm.com)   