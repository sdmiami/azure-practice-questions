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

#### Q3
You would like to add a user who has a Microsoft account to your subscription. Which type of user
account is this? Select one.

- [ ] A. Cloud identity
- [ ] B. Directory-Synchronized
- [ ] C. Provider identity
- [ ] D. Guest User
- [ ] E. Hosted identity

<details><summary>SHOW ANSWER</summary>
<p>

- [ ] A. Cloud identity
- [ ] B. Directory-Synchronized
- [ ] C. Provider identity
- [x] D. Guest User
- [ ] E. Hosted identity

```
Explanation
Guest user. Guest users are users added to Azure AD from a third party like Microsoft or Google.
```
</p>
</details>

---

#### Q4
You are configuring Self-service Password Reset. Which of the following is not a validation method?
Select one.

- [ ] A. An email notification.
- [ ] B. A text or code sent to a user's mobile or office phone.
- [ ] C. A paging service.
- [ ] D. A set of security questions

<details><summary>SHOW ANSWER</summary>
<p>

- [ ] A. An email notification.
- [ ] B. A text or code sent to a user's mobile or office phone.
- [x] C. A paging service.
- [ ] D. A set of security questions

```
Explanation
A paging service. At least one authentication method is required to reset a password. Choices include email
notification, a text or code sent to user’s mobile or office phone, or a set of security questions.
```
</p>
</details>

---

#### Q5
You are assigning Azure AD roles. Which role will allow the user to manage all the groups in your Teams
tenants and be able to assign other administrator roles? Select one.

- [ ] A. Global administrator
- [ ] B. Password administrator
- [ ] C. Security administrator
- [ ] D. User administrator

<details><summary>SHOW ANSWER</summary>
<p>

- [x] A. Global administrator
- [ ] B. Password administrator
- [ ] C. Security administrator
- [ ] D. User administrator

```
Explanation
Global administrator. Only the global administrator can manage groups across tenants and assign other
administrator roles.
```
</p>
</details>

---

#### Q6
You need to target policies and review spend budgets across several subscriptions you manage. What
should you do? Select one.

- [ ] A. Create resource groups
- [ ] B. Create management groups
- [ ] C. Create billing groups
- [ ] D. Create Azure policies

<details><summary>SHOW ANSWER</summary>
<p>

- [ ] A. Create resource groups
- [x] B. Create management groups
- [ ] C. Create billing groups
- [ ] D. Create Azure policies

```
Explanation
Create management groups. Management groups can be used to organize and manage subscriptions.
```
</p>
</details>

---

#### Q7
You would like to categorize resources and billing for different departments like IT and HR. The billing
needs to be consolidated across multiple resource groups and you need to ensure everyone complies
with the solution. What should you do? {Choose two to complete a solution}.

- [ ] A. Create tags for each department.
- [ ] B. Create a billing group for each department.
- [ ] C. Create an Azure policy.
- [ ] D. Add the groups into a single resource group.
- [ ] E. Create a subscription account rule.

<details><summary>SHOW ANSWER</summary>
<p>

- [x] A. Create tags for each department.
- [ ] B. Create a billing group for each department.
- [x] C. Create an Azure policy.
- [ ] D. Add the groups into a single resource group.
- [ ] E. Create a subscription account rule.

```
Explanation
Create tags for each department and Create an Azure policy. You should create a tag with a key:value pair
like department:HR. You can then create an Azure policy which requires the tag be applied before a resource
is created.
```
</p>
</details>

---

#### Q8
Your company financial comptroller wants to be notified whenever the company is half-way to spending
the money allocated for cloud services. What should you do? Select one.

- [ ] A. Create an Azure reservation.
- [ ] B. Create a budget and a spending threshold.
- [ ] C. Create a management group.
- [ ] D. Enter workloads in the Total Cost of Ownership calculator.

<details><summary>SHOW ANSWER</summary>
<p>

- [ ] A. Create an Azure reservation.
- [x] B. Create a budget and a spending threshold.
- [ ] C. Create a management group.
- [ ] D. Enter workloads in the Total Cost of Ownership calculator.

```
Explanation
Create a budget and a spending threshold. Billing Alerts help you monitor and manage billing activity for
your Azure accounts. You can set up a total of five billing alerts per subscription, with a different threshold
and up to two email recipients for each alert. Monthly budgets are evaluated against spending every four
hours. Budgets reset automatically at the end of a period.
```
</p>
</details>

---

#### Q9
Your organization has several Azure policies that they would like to create and enforce for a new branch
office. What should you do? Select one.

- [ ] A. Create a policy initiative
- [ ] B. Create a management group
- [ ] C. Create a resource group
- [ ] D. Create a new subscriptions

<details><summary>SHOW ANSWER</summary>
<p>

- [x] A. Create a policy initiative
- [ ] B. Create a management group
- [ ] C. Create a resource group
- [ ] D. Create a new subscriptions

```
Explanation
Create a policy initiative. A policy initiative would include all the policies of interest. Once your initiative is
created, you can assign the definition to establish its scope. A scope determines what resources or grouping
of resources the policy assignment gets enforced on.
```
</p>
</details>

---

#### Q10
Which of the following would be good example of when to use a resource lock? Select one.

- [ ] A. An ExpressRoute circuit with connectivity back to your on-premises network.
- [ ] B. A non-production virtual machine used to test occasional application builds.
- [ ] C. A storage account used to temporarily store images processed in a development environment.
- [ ] D. A resource group for a new branch office that is just starting up.

<details><summary>SHOW ANSWER</summary>
<p>

- [x] A. An ExpressRoute circuit with connectivity back to your on-premises network.
- [ ] B. A non-production virtual machine used to test occasional application builds.
- [ ] C. A storage account used to temporarily store images processed in a development environment.
- [ ] D. A resource group for a new branch office that is just starting up.
```
Explanation
An ExpressRoute circuit with connectivity back to your on-premises network. Resource locks prevent other
users in your organization from accidentally deleting or modifying critical resources.
```
</p>
</details>

---

#### Q11
Your company hires a new IT administrator. She needs to manage a resource group with first-tier web
servers including assigning permissions . However, she should not have access to other resource groups
inside the subscription. You need to configure role-based access. What should you do? Select one.

- [ ] A. Assign her as a Subscription Owner.
- [ ] B. Assign her as a Subscription Contributor.
- [ ] C. Assign her as a Resource Group Owner.
- [ ] D. Assign her as a Resource Group Contributor.

<details><summary>SHOW ANSWER</summary>
<p>

- [ ] A. Assign her as a Subscription Owner.
- [ ] B. Assign her as a Subscription Contributor.
- [x] C. Assign her as a Resource Group Owner.
- [ ] D. Assign her as a Resource Group Contributor.
```
Explanation
Assign her as a Resource Group owner. The new IT administrator needs to be able to assign permissions.
```
</p>
</details>

---

#### Q12
You have three virtual machines (VM1, VM2, and VM3) in a resource group. The Helpdesk hires a new
employee. The new employee must be able to modify the settings on VM3, but not on VM1 and VM2.
Your solution must minimize administrative overhead. What should you do? Select one.

- [ ] A. Assign the user to the Contributor role on the resource group.
- [ ] B. Assign the user to the Contributor role on VM3.
- [ ] C. Move VM3 to a new resource group and assign the user to the Contributor role on VM3.
- [ ] D. Assign the user to the Contributor role on the resource group, then assign the user to the Owner role on VM3.

<details><summary>SHOW ANSWER</summary>
<p>

- [ ] A. Assign the user to the Contributor role on the resource group.
- [x] B. Assign the user to the Contributor role on VM3.
- [ ] C. Move VM3 to a new resource group and assign the user to the Contributor role on VM3.
- [ ] D. Assign the user to the Contributor role on the resource group, then assign the user to the Owner role on VM3.
```
Explanation
Assign the user to the Contributor role on VM3. This means the user will not have access to VM1 or VM2.
The Contributor role will allow the user to change the settings on VM1.
```
</p>
</details>