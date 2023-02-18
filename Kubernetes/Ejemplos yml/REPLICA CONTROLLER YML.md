```
apiVersion: v1
kind: ReplicationController
metadata:
  name: myapp
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
```
