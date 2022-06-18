# Conversation Practice

[Web Demo](https://conversation-practice.run.goorm.io/) | [conversation-practice on Ainize](https://ainize.ai/)

This repository have source code about conversation pracitce. You can practice speaking English in context by talking to the AI bot.
You can talk to the AI bot and get recommendations for the right answer for your situation!
It's powered by GPT-2 models.


## How to run

#### with Docker
```bash
docker build -t flask-application:latest .
```
```
docker run -d -p 5000:5000 flask-application
```
#### without Docker
```bash
$ pip install -r requirements.txt
$ python3 application.py
```

Now the server is available at http://localhost.


## GPT2-Model List
> openchat: [https://ainize.ai/Jeong-Hyun-Su/gpt2-large](https://ainize.ai/fpem123/openchat)
> * Used Model
>   * blender.small
>   * blender.medium


## How to develop TabTab on Ainize (with GPT-2 APIs)
https://ai-network.gitbook.io/ainize-tutorials/
