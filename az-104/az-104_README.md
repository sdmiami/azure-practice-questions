## AZ-104: Microsoft Azure Administrator

---
#### Q1 
Your users want to sign-in to devices, apps, and services from anywhere. They want to sign-in using an
organizational work or school account instead of a personal account. You must ensure corporate assets
are protected and that devices meet standards for security and compliance. Specifically, you need to be
able to enable or disable a device. What should you do? Select one.

- [ ] A. Enable the device in Azure AD.
- [ ] B. Join the device to Azure AD.
- [ ] C. Connect the device to Azure AD.
- [ ] D. Register the device with Azure AD.


<details><summary>SHOW ANSWER</summary>
<p>

- [ ] A. Enable the device in Azure AD.
- [x] B. Join the device to Azure AD.
- [ ] C. Connect the device to Azure AD.
- [ ] D. Register the device with Azure AD.

```
Explanation
Join the device to Azure AD. Joining a device is an extension to registering a device. This means, it provides
you with all the benefits of registering a device, like being able to enable or disable the device. In addition, it
also changes the local state of a device. Changing the local state enables your users to sign-in to a device
using an organizational work or school account instead of a personal account.
```
</p>
</details>

---
#### Q2
Identify three differences from the following list between Azure Active Directory (AD) and Active Directory
Domain Services (AD DS). Select three.

- [ ] A. Azure AD uses HTTP and HTTPS communications
- [ ] B. Azure AD uses Kerberos authentication
- [ ] C. There are no Organizational Units (OUs) or Group Policy Objects (GPOs) in Azure AD
- [ ] D. Azure AD includes Federation Services
- [ ] E. Azure AD can be queried through LDAP

<details><summary>SHOW ANSWER</summary>
<p>

- [X] A. Azure AD uses HTTP and HTTPS communications
- [ ] B. Azure AD uses Kerberos authentication
- [X] C. There are no Organizational Units (OUs) or Group Policy Objects (GPOs) in Azure AD
- [X] D. Azure AD includes Federation Services
- [ ] E. Azure AD can be queried through LDAP

```
Explanation
Although the list is by no means conclusive, and you may identify others not listed, here are several characteristics of Azure AD that make it different to AD DS: Azure AD is primarily an identity solution, and it is
designed for Internet-based applications by using HTTP and HTTPS communications; because Azure AD is
HTTP/HTTPS based, it cannot be queried through LDAP. Instead, Azure AD uses the REST API over HTTP
and HTTPS. Because Azure AD is HTTP/HTTPS based, it does not use Kerberos authentication. Instead, it
uses HTTP and HTTPS protocols such as SAML, WS-Federation, and OpenID Connect for authentication
(and OAuth for authorization). Azure AD users and groups are created in a flat structure, and there are no
Organizational Units (OUs) or Group Policy Objects (GPOs). While Azure AD includes federation services,
and many third-party services (such as Facebook), AD DS supports federation.
```

</p>
</details>

---