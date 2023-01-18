Let's create an nginx deployment with 3 replicas
`k create deployment nginx --image=nginx --replicas=3`

you can scale it like this
`kubectl scale deployment/nginx --replicas=10
`
or update its image like this

`kubectl set image deployment/nginx nginx=nginx:1.16.1`