> Jenkins 工具部署   
> https://hub.docker.com/r/jenkins/jenkins/tags?page=1&ordering=last_updated

```shell
docker run --name jenkins -p 8080:8080 -p 50000:50000 -v /home/jenkins:/var/jenkins_home jenkins/jenkins:<iamge-tagname>
```

