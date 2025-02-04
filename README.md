# My B2C samples

## The B2C Multi-tenant sample code has been split into several repos

**In order to provide scripted deployment of (just) the [B2C multi-tenant demo](https://github.com/mrochon/b2csamples/tree/master/Policies/MultiTenant) I have moved
the VS projects related to this demo (UI and reST APIs) to separate repos. This repo will still contain the related
IEF policies as well as policies for other samples and REST functions related to them.**

## New (Sep 2021)
| Date | Change |
| Sep 2021 | New: Federate B2C as IdP for AAD (Direct Federation) |
| Sep 2021 | New: JIT Migration |
| Sep 2021 | Change: Simplified Invitation sample |

## Samples list

| Name  | Description  |
|---|---|
| [AppRoles](https://github.com/mrochon/b2csamples/tree/master/Policies/AppRoles)  | Support for application roles using standard AAD features |
| [B2CSendOTPWithO365](https://github.com/mrochon/b2csamples/tree/master/Policies/b2cSendOtpWith0365)  | Send email OTP using O365 |
| [CheckEmail](https://github.com/mrochon/b2csamples/tree/master/Policies/CheckEmail)  | Prevents users from signing up or in using emails with specific email domains |
| [EmailOrUserId](https://github.com/mrochon/b2csamples/tree/master/Policies/EmailAndUserId)  | Allow users to signup with both an email and a user id and user either to signin later on |
  [EmailOrPhoneMFA](https://github.com/mrochon/b2csamples/tree/master/Policies/EmailOrPhoneMFA)  | Allows local users to use either their email or phone for 2nd FA |
| [ForceADWhenAvaialble](https://github.com/mrochon/b2csamples/tree/master/Policies/ForceAADwhenAvailable)  | Users who signup with an email address supported by an AAD tenant will be automatically redirected there (rather than defining local password in B2C) |
| [IdTokenSelfHint](https://github.com/mrochon/b2csamples/tree/master/Policies/IdTokenSelfHint)  | Allows long-running native apps to initiate profile edit without needing to re-authenticate user |
| [Invite](https://github.com/mrochon/b2csamples/tree/master/Policies/Invitation)  | Create/use an invitation link using client_assertion request |
| [JIT Migrate](https://github.com/mrochon/b2csamples/tree/master/Policies/JitMigrate)  | Migrate users using an API to verify their legacy passwords |
| [MultiTenant](https://github.com/mrochon/b2csamples/tree/master/Policies/MultiTenant)  | Supports use of a single B2C tenant to support a muli-tenant SaaS application |
| [RefreshToken](https://github.com/mrochon/b2csamples/tree/master/Policies/RefreshToken)  | Rejects refresh token exchange if user requested its revocation |
| [SamlIdP](https://github.com/mrochon/b2csamples/tree/master/Policies/SAMLIdP)  | Invite B2C users as B2B users in an Azure AD |
