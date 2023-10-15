# LLM for radiologists

This repository contains the code for a large language model (LLM) that was built for radiologists. It can be used to answer questions about skeletal injuries , generate radiology reports, and more.

## Libraries used

- Langchain
- Huggingface
- FAISS
- OpenAI
- NLTK

## Deployment

Before running the notebook , upload the Osborn Brain Imaging textbook to the drive or download it .
Textbook drive link : https://drive.google.com/file/d/1h-6wvlOx9vVuHimUmWOrHNk36lm4lOjd/view?usp=drive_link

If the above mentioned textbook added to the drive , change pdf_paths to :
```bash
  pdf_paths = ["/content/drive/MyDrive/Osborn Brain Imaging.pdf"]
```
If downloaded locally change the path accordingly.

## Features

- QA with Vectorised Textbook information
- Remembers context of conversation
- Few Shot Answering 

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`OPENAI_API_KEY` : <your OpenAI Api Key>

`HUGGINGFACE_API_KEY` : <your Hugging Face Api Key>



Now run the notebook!

