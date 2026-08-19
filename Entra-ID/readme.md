## Microsoft Entra ID

* "Microsoft Entra ID is Microsoft's cloud-based identity and access management service. It provides a centralized place to manage identities such as users, groups, service principals, and managed identities.

* Entra ID is primarily responsible for authentication - verifying who the user or application is. For authorization to Azure resources, we use Azure RBAC, where we assign roles such as Reader, Contributor, or Owner to an identity at a particular scope, such as a subscription, resource group, or resource.

* For example, we can create a managed identity for an Azure resource and assign it an appropriate RBAC role so that it can access another Azure resource without storing credentials. Entra ID also supports features such as MFA, Single Sign-On, and Conditional Access"