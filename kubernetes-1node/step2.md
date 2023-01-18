
Run `kubectl run my-nginx --image=nginx  --port=80
`
and try to exec into the server 
`k exec my-nginx  -it -- bash`

you can try to `curl localhost:80`