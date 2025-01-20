# University Chatbot with BERT

## Introduction

Welcome to the **University Chatbot** project! This chatbot has been developed using **BERT** (Bidirectional Encoder Representations from Transformers) to provide academic support and assist users with a variety of university-related queries. The goal was to create an efficient, intelligent assistant that can handle different types of student and faculty inquiries seamlessly.

## Exploratory Data Analysis (EDA)

Before training the model, we conducted a thorough **Exploratory Data Analysis (EDA)** on the dataset:
- Cleaned and preprocessed the data to ensure that the chatbot can handle a diverse range of user queries.
- Analyzed query types and user interaction patterns to improve model understanding.
- Visualized key metrics to enhance the training process, leading to a better-performing model.

## Model Development

The heart of the chatbot is the **BERT model**:
1. **Preprocessing:** Data was tokenized and normalized, ensuring proper input for BERT.
2. **Fine-tuning:** Using the Hugging Face **transformers** library, we fine-tuned the pre-trained BERT model specifically for our chatbot’s domain.
3. **Training:** After the preprocessing and fine-tuning, the model was trained on relevant academic data to make it capable of answering university-related questions accurately.

## Performance

The chatbot performs extremely well, achieving:
- **High accuracy** in answering a wide range of questions related to courses, schedules, and campus life.
- **Contextual understanding** that ensures meaningful conversations even during multi-turn dialogues.
- **Fast response time**, making the interaction feel seamless and engaging.

## Setup & Usage

1. Clone the repository:
   git clone https://github.com/Erfaani/UniChatbot.git
  

2. Install the dependencies:
   pip install -r requirements.txt
  

3. Run the chatbot:
   jupyter main.ipynb

4. Start chatting with the bot!

## Contact & Feedback

I would love to hear your thoughts and suggestions about the chatbot. Feel free to reach out to me for any questions or feedback:

**Email:** [Erfanjouybar@gmail.com]  
**GitHub:** [[Github Link](https://github.com/Erfaani/)]  
**LinkedIn:** [[Linkedin link](https://www.linkedin.com/in/erfanjouybar)]  

---

![Chatbot Screenshot](https://i.postimg.cc/SKqx8pD6/Screenshot-2025-01-20-113458.png)