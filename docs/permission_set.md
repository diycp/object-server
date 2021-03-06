---
title: 权限组
---

权限组是授予用户对各种对象和功能的访问权限的设置和权限集合。

假设您在贵组织中拥有“库存”自定义对象。许多用户需要此对象的“读取”访问权限，而少数用户则需要“编辑”访问权限。您可以创建授予“读取”访问权限的权限组，并将其分配到适用用户。然后，您可以创建另一个权限组，可授予“库存”对象的“编辑”访问权限，并将其分配到人数较少的用户组。

系统内置两个权限组：admin, user
- admin 是默认的管理员权限组，工作区管理员自动属于此权限组
- organization_admin 是默认的组织管理员权限组，可设置任何用户加入该权限组，该权限组内用户有其主单位下组织、用户的管理权限
- workflow_admin 是默认的流程管理员权限组，可设置任何用户加入该权限组，该权限组内用户有其单位下审批流程相关对象的管理权限
- user 是默认的普通用户权限组，所有员工都自动属于此权限组

用户可以属于多个权限组，当用户同时属于多个权限组时，最终用户的权限为其在各权限组中的权限叠加。

管理员还可以在权限集中配置授权访问的应用。
