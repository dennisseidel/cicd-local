# Setup CICD locally

# start jenkins in docker 

https://github.com/bitnami/bitnami-docker-jenkins

```bash
docker-compose up
```

# tunnel to it with ngrok 

http://blog.benhall.me.uk/2015/01/tunnelling-docker-container-using-ngrok/

```bash
brew cask install ngrok
ngrok http 38080
```

# integrated github with jenkins

https://blog.tentamen.eu/jenkins-and-github-integration-using-webhooks/


# add git credentials 

https://alanedwardes.com/blog/posts/git-username-password-environment-variables/

# integrate github with jenkins declarative pipeline

https://dzone.com/articles/jenkins-declarative-pipeline-and-awesome-github-in