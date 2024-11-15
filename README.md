# Fine-Tuned Gemma Model for Cybersecurity Helpdesk

This repository contains the fine-tuned Gemma model for creating an AI-powered helpdesk that assists employees with cybersecurity-related queries. The model aims to provide quick, accurate responses to common security questions, enhancing organisational security and reducing the workload on human support staff.

### Project Overview
The project focuses on using the Gemma Model to develop a cybersecurity helpdesk. The model is fine-tuned to address frequently asked questions in the cybersecurity domain, offering employees 24/7 access to guidance and support.

### Features and Benefits
#### Features
- AI-driven helpdesk for cybersecurity queries
- Tailored responses to security-related issues
- Available 24/7 for instant support

#### Benefits
- Efficiency: Automates responses to FAQs, freeing up human resources for complex tasks.
- Accuracy: Delivers consistent and reliable answers to improve employee security awareness.
- Accessibility: Provides round-the-clock assistance for cybersecurity concerns.
  
### Example Questions the Model Can Handle
- How do I set up multi-factor authentication?
 What should I do if I suspect a phishing attempt?
- How do I know if my computer is infected with malware?
- How do I secure my home Wi-Fi network?
- What should I do if I think my computer has been hacked?
- How can I securely back up my data?
- How do I know if an email attachment is safe to open?
- How do I secure my mobile device against threats?
  
### Fine-Tuning Process

The fine-tuning was performed with Keras using LoRA (Low-Rank Adaptation) to adapt the Gemma model for the cybersecurity domain. Here's an overview of the steps:

#### Data Collection:

Synthetic data was generated to simulate common cybersecurity questions and their answers.
Real-world FAQs from cybersecurity guidelines were also incorporated.
Preprocessing:

Text cleaning and formatting to align with the Gemma model's input structure.

#### Fine-Tuning:

Applied LoRA fine-tuning techniques using the Gemma Model.

#### Evaluation:

Achieved high accuracy in generating relevant and precise answers.

### More Details
Link to finetune script: https://www.kaggle.com/code/victorkingoshimua/fine-tune-gemma-model-in-keras-using-lora

