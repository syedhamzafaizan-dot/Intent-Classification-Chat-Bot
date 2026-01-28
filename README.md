# 🤖 Joana - Intent Classification Chatbot

A simple AI chatbot that understands what you're trying to say and responds naturally using neural networks!

## What Does It Do?

Joana is a friendly chatbot that can:
- Greet you back when you say hello
- Tell you about herself
- Help you with account creation
- Handle complaints
- Say goodbye politely
- Thank you for compliments

She uses machine learning to understand the *intent* behind your message, not just match keywords!

## How It Works (Simple Version)

1. **Training Data**: We teach Joana example phrases for each type of conversation
2. **Text Processing**: Converts your words into numbers the computer can understand
3. **Neural Network**: A "brain" with 16 neurons in two layers learns patterns
4. **Prediction**: When you type something, Joana figures out what you want
5. **Response**: She picks a friendly response from her learned phrases

## Getting Started

### What You Need
- Python 3.14 (or 3.8+)
- A few packages (we'll install them for you!)

### Installation

```bash
pip install nltk colorama numpy scikit-learn Flask
```

Customizing Joana is also possible -- Make her yours truly 😊
Add Your Own Test Messages
Find Section 10 in the notebook and edit the my_messages list:
```python
my_messages = [
    "Hi there",
    "What's your name?",
    "I need help",
    "Your custom message here!"
]
```
Add New Intents (Teach Her New Things!)
Edit Section 2 to add new conversation types:

```python 
{
    "tag": "joke",
    "patterns": ["Tell me a joke", "Make me laugh", "Say something funny"],
    "responses": ["Why did the chatbot cross the road? To get to the other server! 😄"]
}
```
Accuracy
The chatbot typically achieves 95-100% training accuracy on the sample data. With more training examples, it gets even smarter!

