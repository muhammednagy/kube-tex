Let's create a namespace
`kubectl create ns pd-testing`

to view namespaces
`k get ns`

let's run an nginx pod in that namespace

`kubectl run my-nginx --image=nginx -n pd-testing`

`kubectl get po -n pd-testing`
