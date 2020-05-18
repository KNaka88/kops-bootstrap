# kops-bootstrap
AWS Cloudformation Template that creates S3 Bucket and EC2 Instance with kops and kubectl

### This template installs
* EC2 Instance that installs followings
  * kubectl (Before you begin section)[https://kubernetes.io/docs/setup/production-environment/tools/kops/#before-you-begin]
  * kops (Step 1 of Creating a cluster)[https://kubernetes.io/docs/setup/production-environment/tools/kops/#installation]
* S3 Bucket that is used to store the clusters state (used in Step 3 of Creating a cluster)[https://kubernetes.io/docs/setup/production-environment/tools/kops/#35-create-an-s3-bucket-to-store-your-clusters-state]
