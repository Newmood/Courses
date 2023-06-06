#### Common security settings
- Add 2 step verification settings
- Enforce paswrod policies (min length, max length)
- Deny access to apps that use less secure sign in technology
- Review security settings for a particular user
- Enforce 2SV
- Use exception group for disabling 2SV for a subset of OU members
- Configure session controls

1. What are some best practices for reinforcing and monitoring the security of your domain? Disable access to less secure apps, View and manage your users' security settings, Set up 2-step verification
2. The IT manager at your organization wants to know the advantages of using 2-step verification for your organization. What should you say? It'll greatly reduce the risk of unauthorized access if a user's password is compromised, It'll reinforce our domain’s password security by requiring our users to enter an additional code or use a security key to sign in
3. The IT manager at your organization hasn't had a chance to explore the admin console yet but wants to know what individual security settings he can manage for a user. What are some examples you could give him? Require a password change; Determine if the user is enrolled in 2-step verification; Temporarily disable the user's login challenge for 10 minutes
4. Where do you go to manage your users' password strength? Security > Password management
5. Your organization has decided to enforce 2-step verification in 2 weeks. What actions should you keep in mind when enforcing 2-step verification? You'll want to provide a lead time for users to enroll before enforcement; You'll want to confirm that all of your users are enrolled before enforcement; When you create new user accounts after enforcement, you will want to allow them a grace period before they need to enroll otherwise they will be locked out of their accounts


#### Single Sign On (SSO)
- SSO using google as IdP
- Use 3rd party IdPs
- Secure LDAP (use google directory as an LDAP server for authentication, authorization and directory lookups)

1. Your IT manager has just informed you that your organization has an account now with Asana and would like you to enable Single Sign On with the application. Where in the admin console would you go to configure a third-party pre-integrated cloud application, like Asana, as your service provider? Apps > Web and mobile apps > Add App > Search for apps. Then search for Asana from the list of predefined application
2. What of the following are true of the Secure LDAP service? (Choose 3) It allows you to connect your LDAP-based applications and services to Google Workspace; Users authenticate against the Google Workspace directory to gain access to LDAP compliant applications and services; It reduces maintenance as directory information is consolidated into one directory
3. When adding a pre-integrated SAML application to your Google Workspace account, which of the following must you add/upload the Service Provider's configuration? (Choose 3) 
Google Certificate; Entity ID URL; SSO URL
4. When using a third party IdP which of the following is disabled/hidden in Google Workspace? Require password change

#### Application security
- Admin SDK API access
- Managing connected apps (3LO, OAuth 2.0 tokens)
- Each API has one or more scopes which determine the precise access allowed
- We can enable or disable access to each API, create a list of trusted apps that you will allow to use disabled APIs

1. Your organization wants to prevent any external application from accessing Gmail and Drive data. How would you ensure such access is prevented? From Security > API Permissions, ensure Trust domain owned apps is enabled. From Security > API Permissions > MANAGE GOOGLE SERVICES, restrict access to the Gmail and Drive services.
2. You have been asked to create an allowlist of Marketplace apps to restrict which apps a user can install onto their devices. What must you do first? Change the Marketplace settings to allow users to install only allowed applications from Google Workspace Marketplace
3. What is the expected behavior when a user tries to install a Marketplace app that has not been allowed? When the user attempts to install the app they will see a message advising that the app cannot be installed because it has not been allowed
4. What happens to already installed applications if you block API access from the Security > API Permissions section?  Already installed applications will stop working and OAuth tokens will be revoked

#### Security Tools
- Alert center
- User activity reports
- Security center (Security best practices, analytics, actionable insights)

1. Where would you go to review security recommendations for your organization? Security health page
2. Which of the following statements is NOT TRUE about the alert center? The alert center consolidates all admin created email alerts into one place
3. When examining messages in the security investigation tool what actions can you apply to a message? (Choose 3) Mark message as spam; Delete message; View header
4. You have been asked by your CEO to provide a list of users who have not yet enrolled into 2-step Verification. Where can you find that information?  Users Account Activity Report

