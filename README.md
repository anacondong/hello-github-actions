## Welcome to "Hello World" with GitHub Actions

This course will walk you through writing your first action and using it with a workflow file.

**Ready to get started? Navigate to the first issue.**

spring boot CI/CD
ref: https://aws.plainenglish.io/hands-on-ci-cd-for-spring-boot-applications-using-github-actions-and-aws-1cbc1e2c9d54
sona: https://sonarcloud.io/dashboard?branch=springboot&id=anacondong_hello-github-actions

build img
cd springboot
docker build -t anacondong/springboot .

to be deploy locally:
cd ./k8s
kubectl apply -f service.yml
kubectl apply -f deployment.yml
kubectl get service springboot-api-service
kubectl cluster-info

http://<<cluster-info-ip>>:<<service-PORT>>


Cools
