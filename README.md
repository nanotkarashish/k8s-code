kubectl config set-credentials yono --client-certificate=/home/ubun tu/k8s-code/users/yono.crt --client-key=/home/ubuntu/k8s-code/users/yono.key

kubectl config set-context yono-prod --cluster=prod  --user=yono --namespace=instavote

kubectl config use-context yono-prod
