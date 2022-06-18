# Conversation Practice

[Web Demo](https://conversation-practice.run.goorm.io/) | [conversation-practice on Ainize](https://ainize.ai/)

https://user-images.githubusercontent.com/90930393/174440182-4a524670-7d0b-4d2c-8951-553f6f1e4acb.mp4

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
if port is already allocated, set option '-p {empty port num}:5000'
#### without Docker
```bash
$ pip install -r requirements.txt
$ python3 application.py
```
It is recommended to use Docker.

Now the server is available at http://localhost.


## GPT2-Model List
> openchat: [https://ainize.ai/fpem123/openchat](https://ainize.ai/fpem123/openchat)
> * Used Model
>   * blender.small
>   * blender.medium


## How to develop TabTab on Ainize (with GPT-2 APIs)
https://ai-network.gitbook.io/ainize-tutorials/
