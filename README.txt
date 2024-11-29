Examples of the prompts
 - prompt_examples.txt <- used in the main experiments 
 - prompt_examples_for_analysis.txt <- used in the qualitative analysis part




A few examples of the real outputs for the three persona patterns.
The real data of the indicators were removed to avoid duplication. 

Day 0 (Trial 0)
 - shor-term/messages_0.csv
 - medium-term/messages_0.csv
 - long-term/messages_0.csv

Day 165 (Trial 4)
 - shor-term/messages_165.csv
 - medium-term/messages_165.csv
 - long-term/messages_165.csv





Note: 
 - In our experiments, GPT-4 was primarily used. When using GPT-3.5, Class 0 (tie) was more frequently output as a prediction. So, GPT-3.5 outperformed GPT-4 in terms of overall accuracy across the three classes, but it was inferior in the F1-score for Class 1 (fall). Additionally, from the perspective of portfolio management, there was a decrease in the cases where LLM outperformed the buy-and-hold or other baseline strategies in terms of Sharp ratio. 
 - If no position adjustment is made in the evaluation, the LLM-based strategy became the best strategy in more cases.
