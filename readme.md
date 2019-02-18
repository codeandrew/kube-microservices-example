# Kubernetes Microservices
> Using Minikube

## Feature : Deployment
> Deployment handles Replica,

> Replica handles Pods

![image](docs/deployment.png)


## Get Started
Start Minikube
` minikube start`

Check IP Address
` minikube ip `

To run all yml files
` kubectl apply -f . `

To check status
` kubectl get all `

## Delete
To Delete pods
` kubectl delete po --all`


### Shorthands
pod = po
`kubectl describe po name`

service = svc
`kubectl describe svc name`

replicaSet = rs
`kubectl describe rs name`

---
### Emergency Rollback

To check history
` kubectl rollout history deploy webapp `

To check status
` kubectl rollout status deploy webapp `
