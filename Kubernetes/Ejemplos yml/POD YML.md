```
apiVersion: v1
kind: Pod
metadata:
  name: myapp
  labels:
    app: myappanyname
    type: front-or-back-end
spec:
  containers:
  - name: nginx
    image: nginx
```
