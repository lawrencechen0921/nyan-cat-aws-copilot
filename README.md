# AWS Copilot demo with Nyan-Cat Website

## Create your Dockerfile 
```Docker

FROM nginx:alpine
EXPOSE 80
COPY . /usr/share/nginx/html

```
Then use AWS Copilot command line tool `copilot init`.
After deploying to AWS ECS you would get a *URL* to your website!

## Conclusion
Congratulations! You know how to use AWS Copilot to build up your own resources!
After this lab, you would learn-
* Develop website with AWS Copilot.
* Having Basic concept of Container Service with Command Line Tools!
* Understanding underlying infrastructure behind AWS Copilot.