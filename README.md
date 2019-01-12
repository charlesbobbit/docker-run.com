# docker-run.com

https://docker-run.com

docker-run.com enables you to run your Docker Containers in production. All you have to do is fill the url of your Docker image.

![image](https://github.com/acro5piano/docker-run.com/blob/master/demo.gif)

# Why

We all know Docker in production environment is great. Stateless deployment, shared environment in both development and production, and more. However, we have to do a lot of work when we manage our containers in production, such as Blue-Green deployment, Containers health check, and learn Kubernates. Do you imagine if we can run Docker Containers just by telling the url of your Docker image?

- No need to create Fargate instance
- No need to learn Kubernates
- No need to write deploy script
- No need to care about scalability
- No need to set up your certificates

Yes, docker-run.com is here: A new and better way to run Docker Containers in production.

# How to use

As you can see the above demo, all you have to do is input your docker image url. docker-run.com creates an unique domain to your application.

Deploy? It is quite easy, no need to install any CLI:

```
curl -XPOST -H 'Authorization: YOUR_TOKEN' -d HOST/IMAGE:VERSION https://docker-run.com/APP_ID/renew
```

# Project status

Currently docker-run.com is alpha. We will launch beta version by April 2019, so please watch us.
