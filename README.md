Auto Tagging Support Tickets Using LLM

Objective
The objective of this project is to automatically classify support tickets into relevant categories using a Large Language Model (LLM). The system predicts the top 3 most probable tags for each ticket.

Dataset
Helpdesk Dataset  
https://www.kaggle.com/datasets/itssuru/helpdesk-dataset  

Alternative:
Customer Support on Twitter  
https://www.kaggle.com/datasets/thoughtvector/customer-support-on-twitter  

Methodology

Zero-Shot Classification
- Used facebook/bart-large-mnli
- Implemented zero-shot classification
- No fine-tuning required

Candidate Labels
Example categories:
- Billing Issue
- Technical Problem
- Account Access
- Refund Request
- General Inquiry

Top-3 Tag Prediction
- Sorted predictions by probability
- Returned top 3 tags per ticket

Evaluation Approach
- Compared prediction confidence scores
- Tested multiple candidate label sets

Key Results
- Achieved accurate tagging without training
- Demonstrated LLM-based classification
- Efficient CPU-based implementation

Skills Demonstrated
- Prompt Engineering
- Zero-shot Learning
- LLM Integration
- Multi-class Ranking
- Practical NLP Deployment

Future Improvements
- Fine-tune smaller transformer for efficiency
- Deploy using Streamlit
- Add feedback-based learning loop
