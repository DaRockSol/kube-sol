# kube-sol
Running a solana node on kubernetes... you know because I would run a Ford Model T on Kubernetes if I could

I have been using the files in the deploy and services folder to run a solana node on my Rancher Desktop kubernetes node.

I hope you find this useful if you are running development nodes on your own infra.

# Requirements

A local Kubernetes cluster... These days I have been using Rancher Desktop, but minikube, KinD, Kubernetes on Docker for Desktop.

## Deployment

```
git clone https://github.com/DaRockSol/kube-sol

cd kube-sol

kubectl apply -f deploy/
kubectl apply -f services/
```

That should be enough to get you started :-)
