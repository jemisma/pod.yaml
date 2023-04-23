# pod.yaml
apiVersion: v1
kind: Pod
metadata:
name: apache2
labels:
mycka: simplilearn
spec:
containers:
- name: mycontainer

image: docker.io/httpd
ports:
- containerPort: 80
