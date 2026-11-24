\# Experiment 2: Trace kubectl Create Deployment End to End



\## Aim

To trace the complete process of creating a Kubernetes Deployment and understand how Kubernetes components manage Pods and containers.



\## Tools Used

\- Docker Desktop

\- KIND

\- kubectl

\- Windows PowerShell

\- NGINX Docker Image



\## Procedure

1\. Verified the Kubernetes cluster using `kubectl get nodes`.

2\. Created a Deployment using `kubectl create deployment web --image=nginx:1.27 --replicas=2 -v=6`.

3\. Verified Deployment, ReplicaSet and Pods using kubectl commands.

4\. Observed Kubernetes events to understand Pod creation and scheduling.

5\. Identified Deployment, ReplicaSet and Pod records in etcd.

6\. Inspected Pod sandboxes and running containers using `crictl`.

7\. Exposed the Deployment using `kubectl expose deployment web --port=80`.

8\. Verified the Service and EndpointSlices.

9\. Observed Kubernetes network rules using `iptables-save`.

10\. Demonstrated a resource version conflict using `kubectl replace`.



\## Result

Successfully created and traced an NGINX Deployment with two replicas. Verified ReplicaSet, Pods, container runtime, etcd records, Service endpoints and resource version conflict handling.

