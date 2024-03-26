## Evaluation Metrics

ROUGE: recall oriented under study for jesting evaluation

BLEU: bilingual evaluation understudy

<img width="589" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/797b2ef4-fb17-419f-869c-3da2a91f200c">

### How to calculate ROUGE

<img width="534" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/4ad55c1d-7943-4b2a-8f4e-3210feb19ca4">

<img width="596" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/dcef51d5-f91c-4c56-9261-b6302ab091e8">

<img width="611" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/c72aee59-e624-4340-ab13-d4b3aeb6ab37">

<img width="600" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/849e6e56-8ff6-4b07-b974-f6fa9d8eeea6">

### Limitations of ROUGE

<img width="576" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/61a1e677-e594-4aee-a0a1-6f8405340fe1">

<img width="605" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/bea85c7e-983e-4a1b-a355-b6fe4c44615b">

#### Failed case:

Reference: It is code outside.

Generated 1: It is very code outside.

Generated 2: It is not code outside.

### How to calculate BLEU

<img width="568" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/5ce20ac4-621e-4d40-a30c-f223a891053f">

### Usage of ROUGE and BLEU

> Both rouge and BLEU are quite simple metrics and are relatively low-cost to calculate. You can use them for simple reference as you iterate over your models, but you shouldn't use them alone to report the final evaluation of a large language model. Use rouge for diagnostic evaluation of summarization tasks and BLEU for translation tasks. 

> For overall evaluation of your model's performance, however, you will need to look at one of the evaluation benchmarks that have been developed by researchers. They have many more tasks other than summarization and translation.

## Fine Tune Methods

### Computational challenges

### Parameter efficient fine-tuning (PEFT)  		 	 	 		

Full fine-tuning of large LLMs is challenging 

<img width="535" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/5462fc29-9094-41be-a31f-9d07109140eb">

### Low-Rank Adaptation of Large Language Models (LoRA) 

<img width="586" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/3534eacb-8976-43d8-b261-07c5714ee68e">

<img width="592" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/d4d5b5b5-34b6-453c-acd5-eb5506fbc539">

### Prompt Tuning

<img width="526" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/dac92fac-f912-451d-9229-5c1a4bfdad6d">

<img width="509" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/9cef2e5b-a7a4-4aef-9558-a9e5a34758d7">

<img width="544" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/06342120-fe16-41f6-a462-aaafe59cdea7">


## Reinforcement Learning from Human Feedback (RLHF) 

<img width="604" alt="image" src="https://github.com/hongchaozhang/Course--Generative-AI-with-LLMs/assets/8013842/7c223d04-955e-4996-a347-8774e6040856">


