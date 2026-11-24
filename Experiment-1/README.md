# Experiment 1: Create a 3-Node Kubernetes Cluster Using KIND

## Aim
To create a 3-node Kubernetes cluster using KIND and identify the Kubernetes control-plane components.

## Tools Used
- Docker Desktop
- KIND
- kubectl
- Windows PowerShell

## Cluster Configuration
- 1 Control Plane Node
- 2 Worker Nodes

## Procedure
1. Verified KIND and kubectl installation.
2. Created a KIND configuration file named kind-3node.yaml.
3. Created a Kubernetes cluster using the KIND tool.
4. Verified the cluster nodes using kubectl get nodes.
5. Verified Docker containers using docker ps.
6. Identified Kubernetes system components using kubectl get pods -n kube-system.

## Result
Successfully created a 3-node Kubernetes cluster with one control-plane node and two worker nodes. All three nodes reached the Ready state. Kubernetes system components were verified successfully.
