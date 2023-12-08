# Usage

1. Convert the file from wav to m4a to compress it. You can right click in finder and choose to encode, then select the "pod cast" option. 
2. python voice2text.py -o transcribe <path-to-m4a-file>
3. Upload the generated file to the [Career Coach GPT](https://chat.openai.com/g/g-YGvqDytze-interview-coach)

# Technical Notes: 

Based Upon: https://platform.openai.com/docs/tutorials/meeting-minutes but note that the code given in their examples does not work! 

Also See: [OpenAI Speech to text API Docs](https://platform.openai.com/docs/guides/speech-to-text)


# Environment Setup
```
python -m venv env

source env/bin/activate

pip install openai
pip install python-docx
```


