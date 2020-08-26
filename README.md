# kops-bootstrap
AWS Cloudformation Template that creates S3 Bucket and EC2 Instance with [kops](https://github.com/kubernetes/kops) and [kubectl](https://kubernetes.io/docs/reference/kubectl/kubectl/)

### This template does followings for you
* EC2 Instance that installs followings
  * kubectl
  * kops
* Create S3 Bucket that is used to store the clusters state (used in Step 3 of Creating a cluster)
* Attach IAM Policy to the EC2 instance so that kops can do its own job
