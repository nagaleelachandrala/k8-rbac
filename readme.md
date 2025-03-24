# RBAC
REGION_CODE=us-east-1 CLUSTER_NAME=expense1
ACC_ID=273354630431

Permissions
OIDC provider
eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve