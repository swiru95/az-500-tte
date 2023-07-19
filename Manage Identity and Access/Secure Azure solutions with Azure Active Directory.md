### Task 1: Review Azure AD
###### Portal & Entra
1) [Azure Active Directory](https://portal.azure.com/#view/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/~/Overview)  
2) [Entra Microsoft](https://entra.microsoft.com/#home) (optional)
3) [Entra Plans and Pricing](https://www.microsoft.com/en-us/security/business/microsoft-entra-pricing?rtc=1)

### Task 2: Manage users and groups
##### View Users and Groups
###### Portal & Entra

1) [Users](https://portal.azure.com/#view/Microsoft_AAD_UsersAndTenants/UserManagementMenuBlade/~/AllUsers)
   [Users - Entra](https://entra.microsoft.com/#view/Microsoft_AAD_UsersAndTenants/UserManagementMenuBlade/~/AllUsers)
2) [Groups](https://portal.azure.com/#view/Microsoft_AAD_IAM/GroupsManagementMenuBlade/~/AllGroups)
   [Groups - Entra](https://entra.microsoft.com/#view/Microsoft_AAD_IAM/GroupsManagementMenuBlade/~/AllGroups/menuId/AllGroups)

####### Powershell
```powershell
#Module Az
Get-AzADUser
Get-AzADGroup
Get-AzADGroupMember

#Module AzureAD
Get-AzureADUser
Get-AzureADGroup
Get-AzureADGroupMember
```
##### Add Users and Groups
###### Portal & Entra
TO EASY TO WRITE

####### Powershell
```powershell
#Module Az
New-AzADUser
New-AzADGroup
Add-AzADGroupMember

#Module AzureAD
New-AzureADUser
New-AzureADGroup
Add-AzureADGroupMember
```
##### MFA Management
###### Portal & Entra
TO EASY TO WRITE - need Azure AD Prem 2

####### Powershell
```powershell
#list
Get-MgUserAuthenticationPhoneMethod

#set
New-MgUserAuthenticationPhoneMethod
```


