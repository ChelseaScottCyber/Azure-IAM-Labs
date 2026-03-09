# Microsoft Entra ID IAM Lab

## Overview
This lab demonstrates core Identity and Access Management (IAM) operations using Microsoft Entra ID.
The lab simulates common administrative tasks performed by identity administrators.

## Environment
Platform: Microsoft Entra ID
Role: Global Administrator
Tenant Type: Free developer tenant

## Skills Demonstrated

- User provisioning
- Security group creation
- Group membership management
- Role-Based Access Control (RBAC)
- Password reset procedures

## Lab Steps
### Step 1 — Create Users

Navigate to:

Entra ID → Users → New User

Create the following users:

- hr.user
- finance.user
- it.admin

This simulates different departments inside an organization.

![Users Created](screenshots/entra_users_created.png)



### Step 2 — Create Security Groups

Navigate to:

Entra ID → Groups → New Group

Create two security groups:

- HR-Team
- Finance-Team

Security groups are used to manage access for multiple users at once.

![Security Groups](screenshots/entra_security_groups_created.png)

---

### Step 3 — Assign Group Membership

Navigate to:

Entra ID → Groups → HR-Team → Members

Add:

hr.user

Repeat for:

Finance-Team → finance.user

This demonstrates group-based access control.

![Group Membership](screenshots/entra_group_membership.png)



### Step 4 — Assign Administrative Role (RBAC)

Navigate to:

Entra ID → Roles & administrators → User Administrator

Click:

Add assignment

Assign the role to:

it.admin

This demonstrates delegated administration using Role-Based Access Control.

![RBAC Role](screenshots/entra_rbac_role_assignment.png)


### Step 5 — Reset a User Password

Navigate to:

Entra ID → Users → hr.user → Reset Password

Password resets are a common identity lifecycle task.

![Password Reset](screenshots/entra_password_reset.png)

