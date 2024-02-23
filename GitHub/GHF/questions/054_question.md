# Which GitHub Enterprise Cloud authentication options use a centralized identity provider (ldP) to control and secure access to organization resources?

> Both GitHub SAML SSO and Enterprise Managed Users can leverage an ldP for authentication. If you configure SAML SSO, members of your organization Will continue to sign into their personal accounts on GitHub.com. When a member accesses most resources within your organization, GitHub redirects the member to your ldP to authenticate. 
> 
> With Enterprise Managed Users, you manage the lifecycle and authentication of your users on GitHub.com from an external identity management system, or IdP.
> 
> [GitHub Docs - About identity and access management](https://docs.github.com/en/enterprise-cloud@latest/admin/identity-and-access-management/understanding-iam-for-enterprises/about-identity-and-access-management)

1. [x] SAML single sign-on (SSO) and Enterprise Managed Users
1. [ ] GitHub does not currently support the use of centralized IdPs
1. [ ] GitHub personal accounts with 2FA
1. [ ] SAML single sign-on (SSO) excluding Enterprise Managed Users