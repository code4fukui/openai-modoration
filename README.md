# openai-moderation
日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A library for accessing OpenAI's content moderation API.

## Features
- Classify text content as safe or unsafe based on OpenAI's content moderation model
- Supports batch processing of multiple text inputs
- Easy to integrate into your application

## Requirements
- Python 3.6 or later
- OpenAI API key

## Usage

### Installation
Install the library using pip:

```
pip install openai-moderation
```

### Example Usage
```python
from openai_moderation import OpenAIModerator

moderator = OpenAIModerator(api_key="your_openai_api_key")

text = "This is a sample text to be moderated."
response = moderator.moderate_text(text)

print(response)
```

## License
This project is licensed under the [MIT License](LICENSE).
