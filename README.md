# Azure AD B2B (Business) and Azure AD B2C (Consumer)

## Azure AD B2B (Business)

Allows external organizations to connect to your apps. 

* Manage the user based on the user's identity
* Offsore the management to the original organization from where the user's identity comes from
* Let the user self manage the account. 
* 

Service architecture benefits
|      AD B2B Feature         |         Benefit               
|----------------|-------------------------------
|Dynamic Groups  | Assign user to groups based on attributes such as the user's email, userType, [Rule syntax](https://docs.microsoft.com/en-us/azure/active-directory/b2b/use-dynamic-groups)
|Self manage via MyApps Portal         | Update profile and account information [Ref](https://docs.microsoft.com/en-us/azure/active-directory/user-help/my-apps-portal-end-user-access)
|Single sign-on     | One account to access domain-joined devices, company resources, software as a service (SaaS) applications, and web applications [SSO](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/what-is-single-sign-on)
| Guest user access   | A simple invitation and redemption process lets partners use their own credentials to access your company's resources. [Guest user](https://docs.microsoft.com/en-us/azure/active-directory/b2b/what-is-b2b) 
|Enforce multi-factor authentication| External users will need more than just a user name and password to access your resources. [MFA](https://docs.microsoft.com/en-us/azure/active-directory/b2b/b2b-tutorial-require-mfa)


[B2B Best Practices](https://docs.microsoft.com/en-us/azure/active-directory/b2b/b2b-fundamentals)
