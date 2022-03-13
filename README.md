# domoticz-on-k8s
## Requirements
* Background with K8s, ArgoCD, Cert Manager and Kustomize
* Cert manager
* ArgoCD
* zigbee supported USB adapter - https://www.zigbee2mqtt.io/guide/adapters/ 

## Installation
* Edit k8s/kustomization.yaml file. Adjust it for your requirements.
* Create directories according to the local-storage paths (pls look at the k8s/kustomization.yaml)
* Deploy by applying argocd application definition:
  * kubectl apply -f argocd-application-definition.yaml
