# Deploying to Google Cloud Platform

Here are the steps to manually deploy back-end to Google Cloud Platform.

GCP Services used:

- App Engine
- CLoud SQL
- Vertex AI
- Cloud Storage
- Cloud Logging

## Service Architecture

![ArchitectureAPI](https://github.com/hibrizys/imageDocsTookar/blob/main/Service%20Architecture.png)

## App Engine

- Create Application on App Engine

![AppEngine1](https://github.com/hibrizys/imageDocsTookar/blob/main/appengine1.png)

- Configure Application and select region asia-southeast2

![AppEngine2](https://github.com/hibrizys/imageDocsTookar/blob/main/appengine2.png)

- Configure the Resources with language Node.js

![AppEngine3](https://github.com/hibrizys/imageDocsTookar/blob/main/appengine3.png)

- dont forget put app.yaml to your folder API in GCP

![AppEngine4](https://github.com/hibrizys/imageDocsTookar/blob/main/appengine4.png)

- run " gcloud app deploy " on terminal

![AppEngine5](https://github.com/hibrizys/imageDocsTookar/blob/main/appengine5.png)

- and then u can see the output

![AppEngine6](https://github.com/hibrizys/imageDocsTookar/blob/main/appengine6.png)

## Vertex AI

- Create Dataset for Image Classification (Single-label) and choose Region us-central1 (lowa)

![vertexai1](https://github.com/hibrizys/imageDocsTookar/blob/main/vertexai1.png)

- Import image to your dataset

![vertexai2](https://github.com/hibrizys/imageDocsTookar/blob/main/vertexai2.png)

- Label your image and then train new model

![vertexai3](https://github.com/hibrizys/imageDocsTookar/blob/main/vertexai3.png)

- and the you can see the output of your model

![vertexai4](https://github.com/hibrizys/imageDocsTookar/blob/main/vertexai4.png)

![vertexai5](https://github.com/hibrizys/imageDocsTookar/blob/main/vertexai5.png)

- then you can deploy and test your model

![vertexai6](https://github.com/hibrizys/imageDocsTookar/blob/main/vertexai6.png)

- here some example the output will be

![vertexai7](https://github.com/hibrizys/imageDocsTookar/blob/main/vertexai7.png)

## Cloud Logging

- 