---
title: 'Public Folders role: Exchange 2013 Help'
TOCTitle: Public Folders role
ms:assetid: b858f04c-ac0b-495f-9193-8b9645781f73
ms:mtpsurl: https://technet.microsoft.com/library/Dd876930(v=EXCHG.150)
ms:contentKeyID: 49289393
ms.reviewer: 
ms.topic: article
description: About the Public Folders role in Microsoft Exchange Server
manager: serdars
ms.author: serdars
author: msdmaguire
f1.keywords:
- NOCSH
mtps_version: v=EXCHG.150
---

# Public Folders role

_**Applies to:** Exchange Server 2013_

The `Public Folders `management role enables administrators to manage public folders in an organization.

This role doesn't enable you to manage whether public folders are mail-enabled. To mail-enable or disable a public folder, you must be assigned a role associated with the `Mail Enabled Public Folders `role. For more information, see [Mail Enabled Public Folders role](mail-enabled-public-folders-role-exchange-2013-help.md).

## Default management role assignments

This role has role assignments to one or more role assignees. The following table indicates whether the role assignment is regular or delegating, and also indicates the management scopes applied to each assignment. The following list describes each column:

  - **Regular assignment**: Regular role assignments enable the role assignee to access the permissions provided by the management role entries on this role.

  - **Delegating assignment**: Delegating role assignments give the role assignee the ability to assign this role to role groups, users, or USGs.

  - **Recipient read scope**: The recipient read scope determines what recipient objects the role assignee is allowed to read from Active Directory.

  - **Recipient write scope**: The recipient write scope determines what recipient objects the role assignee is allowed to modify in Active Directory.

  - **Configuration read scope**: The configuration read scope determines what configuration and server objects the role assignee is allowed to read from Active Directory.

  - **Configuration write scope**: The configuration write scope determines what organizational and server objects the role assignee is allowed to modify in Active Directory.

### Default management role assignments for this role

<table>
<colgroup>
<col/>
<col/>
<col/>
<col/>
<col/>
<col/>
<col/>
</colgroup>
<thead>
<tr class="header">
<th>Role group</th>
<th>Regular assignment</th>
<th>Delegating assignment</th>
<th>Recipient read scope</th>
<th>Recipient write scope</th>
<th>Configuration read scope</th>
<th>Configuration write scope</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="organization-management-exchange-2013-help.md">Organization Management</a></p></td>
<td><p>X</p></td>
<td><p>X</p></td>
<td><p><code>Organization</code></p></td>
<td><p><code>Organization</code></p></td>
<td><p><code>OrganizationConfig</code></p></td>
<td><p><code>OrganizationConfig</code></p></td>
</tr>
<tr class="even">
<td><p><a href="public-folder-management-exchange-2013-help.md">Public Folder Management</a></p></td>
<td><p>X</p></td>
<td><p> </p></td>
<td><p><code>Organization</code></p></td>
<td><p><code>Organization</code></p></td>
<td><p><code>OrganizationConfig</code></p></td>
<td><p><code>OrganizationConfig</code></p></td>
</tr>
</tbody>
</table>
