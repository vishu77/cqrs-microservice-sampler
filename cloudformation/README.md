# Introduction

This is the cloudformation based provisioning for the CQRDS demo application. The naive implementation uses docker-compose as a PoC created by the developers but now we need to move everything into AWS. For this we opted for cloudformation, though things are missing.

We would like the application to be running in AWS using ECS to host the containers. The containers should be stored in ECR. Your task is to  extend the cloudformation provided as above.