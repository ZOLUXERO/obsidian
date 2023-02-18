```
apiVersion: apps/v1
kind: ReplicaSet
metadata:
  name: myapp-replicaset
  labels:
    app: myappanyname
    type: front-or-back-end
spec:
  template:
    metadata:
      name: myapp
      labels:
        app: myappanyname
        type: front-or-back-end
    spec:
      containers:
      - name: nginx
	image: nginx
  replicas: 3
  selector:  -> la mayor diferencia entre replica controller vs replica set es OPCIONAL (toma el path de un pod creado anteriormente para ser tomado en cuenta y saber que pods debe monitorear)
    matchLabels:
      type: front-or-backend
```
