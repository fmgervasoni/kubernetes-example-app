# kubernetes Microservices example

## Arquitecture

<img src="https://user-images.githubusercontent.com/21206716/224573151-71066ddb-3a1a-47d8-aae0-85ca617a2363.png" width=50% height=50%>

## Steps

1. Deploy PODs
2. Create Services (ClusterIP)
1. redis
2. db
3. Create Services (NodePort),
1. voting-app
2. result-app

tip: if you want to deploy this app on an cloud provider you need to change the Port type from `NodePort` to `LoadBalancer` on voting service and result service.
