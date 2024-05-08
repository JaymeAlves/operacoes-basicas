# Goals achieved

This is a screenshot of the result of the pipeline

<img src="img/resultados-jenkins.PNG">

this is the code of the pipeline

<img src="img/jenkins-script.PNG">

I instancieted the jenkins with docker to make this test, this is how I executed the image:

```
docker run -d -v jenkins_home:/var/jenkins_home -p 8080:8080 -p 50000:50000 --restart=on-failure jenkins/jenkins:lts-jdk17
```