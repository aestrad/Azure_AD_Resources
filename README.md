# Azure AD B2B (Business) and Azure AD B2C (Consumer)

## Azure AD B2B (Business)


## Self managed options

* Allows external organizations to connect to your apps. 
* Manage the user based on the user's identity
* Offsore the management to the original organization from where the user's identity comes from
* Let the user self manage the account. 

Service architecture benefits
|      AD B2B Feature         |         Benefit               
|----------------|-------------------------------
|Dynamic Groups  | Assign user to groups based on attributes such as the user's email, userType, [Rule syntax](https://docs.microsoft.com/en-us/azure/active-directory/b2b/use-dynamic-groups)
|Self manage via MyApps Portal         | Update profile and account information [Ref](https://docs.microsoft.com/en-us/azure/active-directory/user-help/my-apps-portal-end-user-access)
|Single sign-on     | One account to access domain-joined devices, company resources, software as a service (SaaS) applications, and web applications [SSO](https://docs.microsoft.com/en-us/azure/active-directory/manage-apps/what-is-single-sign-on)
| Guest user access   | A simple invitation and redemption process lets partners use their own credentials to access your company's resources. [Guest user](https://docs.microsoft.com/en-us/azure/active-directory/b2b/what-is-b2b) 
|Enforce multi-factor authentication| External users will need more than just a user name and password to access your resources. [MFA](https://docs.microsoft.com/en-us/azure/active-directory/b2b/b2b-tutorial-require-mfa)


[B2B Best Practices](https://docs.microsoft.com/en-us/azure/active-directory/b2b/b2b-fundamentals)


# Azure AD A2C (Consumer)

## NOTES:
   * Only available on an Enterprise Subscription. Not available on a Goverment Subscription.
   * Sharepoint and other office apps do not accept B2C tokens. TODO: 2020 Review this. 

## Manage users and federate to identity providers

* Allows you to federate to any identity provider which supports protocols: OpenID Connect, SAML.
* Define and customize the authentication and authorization via policies.

|      AD B2C Feature         |         Benefit               
|----------------|-------------------------------
|Builtin Policies for federating to social platforms  |  Configure and customize the login page, registration page and any additional attributes you want the user to provide during registration. [User flows](https://docs.microsoft.com/en-us/azure/active-directory-b2c/user-flow-overview)
|Custom policies|Connect your own or any identity provider as long as any of the protocols (SAML, OpenID Connect) is supported. [Reference](https://docs.microsoft.com/en-us/azure/active-directory-b2c/custom-policy-overview)|
