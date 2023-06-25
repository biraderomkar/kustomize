# Prequisites:
1. Local k8s cluster setup: Please checkout my video to setup local cluster
   
   https://www.youtube.com/watch?v=DGVlF_Ao3OY

2. Install Kubectl CLI

Note: Kustomize comes pre bundled with kubectl version >= 1.14. You can check your version using kubectl version --short --client. If version is 1.14 or greater there's no need to take any steps.

But if you want to have standalone kustomize cli then please follow below steps:

# Install Kustomize
curl -s "https://raw.githubusercontent.com/
  kubernetes-sigs/kustomize/master/hack/install_kustomize.sh"  | bash

sudo mv kustomize /usr/local/bin

kustomize version
kustomize -h
