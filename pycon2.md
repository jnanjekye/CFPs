## Title 

Setting up a python deep learning pipeline on kubernetes 

## Duration

30 minutes

## Description 

Machine learning in python involves creating and training models on a dataset . These models are eventually deployed to production
to serve different user needs and requests. Using python, deep learning pipelines implemented with tensorflow can be deployed to a 
single server depending on complexity and the model but deploying them to a kubernetes cluster gives us more benefits and results.

This talk shall cover details with a demo on how to implement and deploy a python deep learning pipeline on kubernetes using 
tensor flow an open source deep learning infrastructure.At the end of this talk, you will understand how to use kubernetes 
and helm to simplify and automate deployments, scale and manage tensorflow deep learning pipelines on a kubernetes cluster. 

## Who and why

This talk is intended for intermediate machine learning enthusiasts to understand how to implement a deep learning pipeline on 
kubernetes. From the content in this presentation, participants shall understand how to use kubernetes to simplify deployments, 
scale and manage tensorflow deep learning pipelines on kubernetes. 

## Outline 

1. Overview of kubernetes (5 Minutes)

As pointed out earlier, deep learning pipelines implemented with tensorflow can be deployed to a single server depending on 
complexity and the model but deploying them to a kubernetes cluster gives better results. I will start by giving an overview on
kubernetes along with the benefits of deploying deep learning pipelines on a kubernetes cluster instead of a single server.

2. Overview to deep learning with Tensorflow (5 Minutes)

I will then cover the basics of a typical machine learning implementation using tensorflow with alot of details on building and serving
tensorflow models. The key concepts on servables, servable verions, servable streams, models. loaders, sources, aspired versions and 
managers shall be discussed along with the general lifecycle of servable. Under this I  willcover the folowing topics.
  - Architecture of tensorflow serving
  - Serving tensorflow models
  - Building a basic tensorflow ModelServer

3. Deploy a deep learning training on a kubernetes cluster (10 Minutes)

I will last but not least discuss how to deploy a TensorFlow Serving Docker image to a kubernetes cluster.

4. Deep Learning on CPU/GPUs and kubernetes  (10 Minutes)

I will finally cover how to run a deep learning training on a kubernetes cluster with GPU and CPU nodes.

## Additional notes 

I share my experience working on open source projects. I have authored an articles on the subject for the Apress blog and  another on opensource.com.

I am a regular speaker at both local (uganda, kenya) and international conferences. I give mostly technical talks on the python at conferences like PyconZA in south Africa among others. I have shared a link to some of the recorded talks on youtube.

https://www.youtube.com/results?search_query=Joannah+Nanjekye
