# My AskAI Python Package

Welcome to the [My AskAI](https://myaskai.com/), AI customer support, Python Package! This package allows developers to easily integrate AI-powered customer support and chatbot capabilities into their applications using My AskAI's advanced AI platform.

## Features

- **AI Customer Support**: Automate customer inquiries with high accuracy and respond in real-time.
- **Chatbot Integration**: Enhance your applications with smart conversational agents.
- **Easy to Use**: Simple API structure for seamless integration.
- **API Access**: API access is inlcuded in all paid plans

## Installation

Install the package using pip:

```bash
pip install myaskai-py
```

## Getting Started

Here's a quick guide on how to setup My AskAI in your JavaScript project.

### Importing the SDK

First, import the SDK into your project:

```python
from myaskaipy import MyAskAI
```

### Initializing My AskAI

Create an instance of My AskAI with your API key and a unique ID:

```python
myAskAI = MyAskAI('your_api_key_here', 'your_unique_id_here')
```

### Making Queries

You can now use this instance to make queries to the My AskAI API:

```python
def getAnswer(query) {
    const response = myAskAI.query(query)
    if (response):
        print('Answer:', response.answer)
        // Handle other parts of the response if necessary
    else:
        print('Failed to get an answer')

}
```

## Documentation

For more detailed documentation, please visit our [homepage](https://myaskai.com/).

## Support

If you need any help using the SDK or have any questions, please visit our [support page](https://myaskai.com/).

## Enhance Your Application

Leverage the power of AI to improve your customer support and chatbot functionality today by integrating MyAskAI into your application!

---

For further information and updates, please visit our official website: [My AskAI](https://myaskai.com/).
