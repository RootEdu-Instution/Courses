# Kubernetes
## Archticture
> Master

1. Kubeapi Server
2. Scheduler
3. ETCD
4. Controller Manager

> Worker
1. kubelet
2. kube-proxy
3. CRI

## Pod
> Environment Variables

> running commands

> Attaching volumes

> Using secrets and ConfigMaps

> ImagePullSecrets - https://kubernetes.io/docs/tasks/configure-pod-container/pull-image-private-registry/

> Liveness Probe

> Readiness Probe
 
## Volumes
> PV

> PVC

> StorageClasses

## Services

> ClusterIP

> NodePort

> LoadBalancer

## roles, rolebinding

## troubleshooting
> kubectl logs

> kubectl exec

## Upgrades
> cordon

>
TODO
1. Istio
2. argo cd
3. ingress
4. sts
5. daemonsets
6. jobs/cronjobs
7. service accounts
8. Scheduling
9. Sidecar container
    8.1 nodeAffinity

    8.2 Podaffinity

    8.3 Taint and tollerations 

    8.4 nodeName
