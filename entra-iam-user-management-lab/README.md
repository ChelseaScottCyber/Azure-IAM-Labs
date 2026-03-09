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

### 1. Create Users
Three users were created to simulate different departments.

- hr.user
- finance.user
- it.admin

![Users Created](screenshots/entra_users_created.png)

---

### 2. Create Security Groups

Security groups created:

- HR-Team
- Finance-Team

![Groups Created](screenshots/entra_security_groups_created.png)

---

### 3. Configure Group Membership

Users were added to their corresponding department groups.

![Group Membership](screenshots/entra_group_membership.png)

---

### 4. Assign RBAC Role

The **User Administrator** role was assigned to the IT admin account to simulate delegated administration.

![RBAC Role](screenshots/entra_rbac_role_assignment.png)

---

### 5. Password Reset

Password reset was tested for a user account to demonstrate lifecycle management.

![Password Reset](screenshots/entra_password_reset.png)

---

## Key Takeaways

This lab demonstrates fundamental IAM administration tasks including identity provisioning, access control, and privilege management within Microsoft Entra ID.
