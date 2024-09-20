# IT-Domain-Expert-Model
This model has been fine-tuned from the Meta Llama 2 7B foundation model for generating informative, accurate and contextually relevant text responses in the IT domain, based on user prompt input.

This is part of the capstone project on Udacity's `Introduction to Generative AI with AWS`.
The main components of this project include:
- Amazon SageMaker -> training, fine-tuning, deploying and evaluation of the Meta Llama 2 7B foundation model
- AWS S3 Bucket -> storing the model parameters and weights
- Instance type:
   - `ml.g5.2xlarge` (AWS) -> model training
   - `ml.g5.12xlarge` (AWS) -> model deployment and endpoint usage
