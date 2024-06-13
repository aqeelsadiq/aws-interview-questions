1. What is AWS Identity and Access Management (IAM)?
AWS IAM is a service that allows you to manage users, groups, and permissions for accessing AWS resources. It provides centralized control over authentication and authorization.
2. What is the difference between authentication and authorization in AWS IAM?
Authentication is the process of verifying the identity of users or entities, while authorization is the process of granting or denying access to resources based on policies and permissions.
3. What is an IAM policy?
An IAM policy is a JSON document that defines permissions. It specifies what actions are allowed or denied on which AWS resources for whom (users, groups, or roles).
4. What is the purpose of IAM groups?
IAM groups allow you to group users and apply policies to them collectively, simplifying permission management by granting the same set of permissions to multiple users.
5. How does IAM enforce the principle of least privilege?
IAM enforces the principle of least privilege by allowing you to define specific permissions for users, groups, or roles, reducing the risk of unauthorized access.
6. What is the difference between IAM policies and resource-based policies?
IAM policies are attached to identities (users, groups, roles), while resource-based policies are attached to AWS resources (e.g., S3 buckets, Lambda functions) to control access from different identities.

7. How can you implement multi-factor authentication (MFA) in IAM?
You can enable MFA for IAM users to require an additional authentication factor (e.g., a code from a virtual MFA device) along with their password when signing in.