#### kubernetes tips:-

1. working with multiple contexts

KUBECONFIG=config-devk8s:config-prodk8s kubectl config view --merge --flattern > ~/.kube/config

kubectl config get-contexts

or use kubectx my-context-name
