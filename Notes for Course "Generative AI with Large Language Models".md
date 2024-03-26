## Evaluation Metrics

ROUGE: recall oriented under study for jesting evaluation

BLEU: bilingual evaluation understudy





### How to calculate ROUGE











### Limitations of ROUGE





#### Failed case:

Reference: It is code outside.

Generated 1: It is very code outside.

Generated 2: It is not code outside.

### How to calculate BLEU





### Usage of ROUGE and BLEU

Both rouge and BLEU are quite simple metrics and are relatively low-cost to calculate. You can use them for simple reference as you iterate over your models, but you shouldn't use them alone to report the final evaluation of a large language model. Use rouge for diagnostic evaluation of summarization tasks and BLEU for translation tasks. 

For overall evaluation of your model's performance, however, you will need to look at one of the evaluation benchmarks that have been developed by researchers. They have many more tasks other than summarization and translation.

## Fine Tune Methods

### Computational challenges

### Parameter efficient fine-tuning (PEFT)  		 	 	 		

Full fine-tuning of large LLMs is challenging 



 		 	 	 		

### Low-Rank Adaptation of Large Language Models (LoRA) 







### Prompt Tuning







## Reinforcement Learning from Human Feedback (RLHF) 



