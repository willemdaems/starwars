```
docker build -t starwars-nginx:1.0.0 -f docker/nginx/Dockerfile .
```

```
docker build -t willemdaems/starwars-nginx:1.0.0 -f docker/nginx/Dockerfile .
```

```
docker push willemdaems/starwars-nginx:1.0.0
```

```
kubectl exec --stdin --tty starwars-nginx -- /bin/sh
```

```
kubectl logs starwars-nginx  --tail 1 --follow
```
