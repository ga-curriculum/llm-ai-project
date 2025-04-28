# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) 
 # LLM AI Project
 ---

## About 

For this project, you will select a dataset of your choice to explore an LLM or AI project. 

## Requirements 
- Your task must be one or more of the following:
  - translation 
  - summarization
  - sentiment analysis
  - entity recognition 
- Your project should involve applying a pretrained model for text data
- Your text must be labeled or annotated data (it is recommended to use a dataset that was previously used for benchmarking or research )
- You must evaluate the performance of your model with appropriate metrics for your task 
- (examples may include: ROUGE or BLEU )
- Use Hugging Face tooling 
- Answer the following questions in a brief writeup: 
  - Why is model appropriate for your task and dataset? 
  - What are the limitations and biases of your model? 
  - How did the model perform on your task? 
  - How would you improve the model in the future? 

Steps: 
1. Identify your task and dataset 
2. Select an appropriate model 
3. Apply model to your data and evaluate 
4. Iterate as needed 
5. Write up final conclusions 

---
## Deliverables 
- Notebook with working code and markdown answering the questions above 
- Brief Presentation to classmates 
  - Consider your audiance 
  - Be sure to highlight importand decisions and findings 
  - Make recommendations for next steps 
---
## Compute Considerations 
#### GPU Access

This project involves using pretrained models which can be computationally intensive.
Important Note for Students Without GPU Access:

If you don't have access to a GPU, consider the following strategies:

- Use smaller model variants (e.g., distilled or tiny versions) that require less computational power
- Process smaller batches of data
- Monitor memory usage carefully to avoid crashes
- Reduce the number of inference examples if necessary
- Utilize Hugging Face's model quantization techniques to reduce memory requirements
- Consider free cloud options like Google Colab (free tier includes limited GPU access)

