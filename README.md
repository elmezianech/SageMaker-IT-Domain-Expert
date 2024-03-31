# SageMaker-IT-Domain-Expert

## Dataset Used:
The dataset selected for this project revolves around challenges in ubiquitous data management within the IT domain. It contains discussions on various aspects such as mobility support, context awareness, support for collaboration, adaptivity, and user interaction within ubiquitous computing environments. This dataset serves as the training ground for fine-tuning the language model to become a domain expert in IT-related text generation.


## Steps Used in the Project:

1- Dataset Selection: A dataset relevant to the IT domain is selected. The chosen dataset contains unstructured text discussing challenges and requirements in ubiquitous data management within the IT domain.

2- Environment Configuration:

  -An AWS SageMaker IAM Role is configured to provide necessary permissions for accessing AWS resources.
  -An AWS SageMaker Notebook Instance is set up for developing and running code.
  -A GPU instance (ml.g5.2xlarge) is requested for fine-tuning the language model.
3- Fine-tuning the Language Model:

-The Meta Llama 2 7B foundation model is deployed on the AWS platform.
-Python scripts are employed to fine-tune the model on the selected IT domain dataset, enhancing its understanding of domain-specific language and concepts.
4- Model Deployment:

  -The fine-tuned language model is deployed on SageMaker to make it accessible for inference.
5- Testing and Evaluation:

  -The deployed model is tested and evaluated for its responses to domain-specific knowledge and text-generation tasks relevant to the IT domain.
6- Documentation and Submission:

  -A comprehensive report and presentation documenting the process, challenges, and solution are prepared for submission.


## Technologies Used:

1-Amazon SageMaker: The project utilizes Amazon SageMaker, a fully managed service that provides every developer and data scientist with the ability to build, train, and deploy machine learning models quickly.

2-Meta Llama 2 7B Model: The Meta Llama 2 7B foundation model serves as the base for fine-tuning. This model has been pre-trained for text-generation tasks and will be adapted to the IT domain through fine-tuning.

3-Python: Python programming language is extensively used for scripting and interacting with AWS services, including SageMaker.

4-AWS Services: The project leverages various AWS services, including IAM (Identity and Access Management) for managing access to AWS services securely, EC2 (Elastic Compute Cloud) for requesting GPU instances for model training, and S3 (Simple Storage Service) for storing datasets and model artifacts.
