# dvg-poc-k8s

## AWS Login
https://bridge.hosted-tools.com/documentation/3011

## Argocd
https://dvg-poc.argocd.hosted-temp.com

## Connect to aws cli
aws configure

### optional

        export AWS_ACCESS_KEY_ID=""
        export AWS_SECRET_ACCESS_KEY=""
        export AWS_DEFAULT_REGION="eu-central-1"

## Kubectl connect

aws eks --region eu-central-1 update-kubeconfig --name dvg-poc-eks-Ajumpg2k
