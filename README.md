# Lab

./tf for vpc + eks


 EKS+ALB+ISTIO+TLS https://github.com/aws-samples/eks-alb-istio-with-tls
 https://aws.amazon.com/blogs/containers/setting-up-end-to-end-tls-encryption-on-amazon-eks-with-the-new-aws-load-balancer-controller/
 
kubectl create namespace argocd

kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml

kubectl port-forward svc/argocd-server -n argocd 8080:443

kubectl apply -f application.yaml

terraform + RDS SEE https://github.com/terraform-aws-modules/terraform-aws-rds

terraform + security groups https://github.com/terraform-aws-modules/terraform-aws-security-group

terraform + route53 https://github.com/terraform-aws-modules/terraform-aws-route53


