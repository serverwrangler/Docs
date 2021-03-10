## Logon Session Events  

* 4624 - Successful logon  

* 4647 - User initiated logoff  

* 4625 - Logon failure  

* 4778 - Remote desktop session reconnected  

* 4779 - Remote desktop session disconnected  

* 4800 - Workstation locked  

* 4801 - Workstation unlocked

* 4802 - Screen saver invoked  

* 4803 - Screen saver dismissed  


## Logon Types  

* 2 - Interactive  
* 3 - Network (i.e. mapped drive)  
* 4 - Batch (i.e. scheduled task)  
* 5 - Service (service startup)  
* 7 - Unlock (i.e. unattended workstation with password protected screen saver)  
* 8 - Network Cleartext (Most often indicates a logon to ISS with "basic authentication")  
* 10 - Remote Desktop  
* 11 - Logon with cached credentials  


## Logon Failure Codes  

* 0xC0000064 - Username does not exist  

* 0xC000006A - Username correct / password incorrect  

* 0xC0000234 - User is currently locked out  

* 0xC0000072 - Account is currently disabled  

* 0xC000006F - User tried to logon outside of their day of week or time of day restrictions  

* 0xC0000070 - Workstation restrictions  

* 0xC00000193 - Account expiration  

* 0xC0000071 - Expired password  

* 0xC0000133 - Clocks between DC and other computer too far out of sync  

* 0xC0000224 - User is required to change password at next logon  

* 0xC0000225 - Evidently a bug in Windows and not a risk  

* 0xC000015b - The user has not been granted the requested logon type at this machine  


## User Account Changes

* 4720 - Account Created  

* 4722 - Account Enabled  

* 4723 - User changed own password  

* 4724 - Privileged User changed this user's password  

* 4725 - Account Disabled  

* 4726 - Account Deleted  

* 4738 - Account Changed  

* 4740 - Account Locked Out  

* 4767 - Account Unlocked  

* 4781 - Account Name Changed  


## Group Changes  

### Security  

#### Local:  

* 4731 - Created  

* 4735 - Changed  

* 4734 - Deleted  

* 4732 - Member added  

* 4722 - Member removed  

#### Global:  

* 4727 - Created  

* 4737 - Changed  

* 4730 - Deleted  

* 4728 - Member added  

* 4729 - Member removed  

#### Universal:  

* 4754 - Created  

* 4755 - Changed  

* 4758 - Deleted  

* 4756 - Member added  

* 4757 - Member removed  

### Distribution  

#### Local  

* 4744 - Created  

* 4745 - Changed  

* 4748 - Deleted  

* 4746 Member added   

* 4747 Member removed   

#### Global  

* 4749 Created  

* 4750 Changed  

* 4753 Deleted  

* 4751 Member added  

* 4752 Member removed  

#### Universal

* 4759 Created  

* 4760 Changed  

* 4763 Deleted  

* 4761 Member added  

* 4762 Member removed  


## Domain Controller Authentication Events  

* 4768 - A Kerberos authentication ticket (TGT) was requested  

* 4771 - Kerberos pre-authentication failed  

* 4820 - A Kerberos TGT was denied because the device does not meet the access control restrictions  

## Kerberos Failure Codes  

* 0x6 - Bad user name  

* 0x7 - New computer account  

* 0x9 - Administrator should reset password  

* 0xC - Workstation restriction  

* 0x12 - Account disabled, expired, locked out, or logon hours restriction  

* 0x17 - The user's password has expired  

* 0x18 - Bad password  

* 0x20 - Frequently logged by computer accounts  

* 0x25 - Workstation's clock too far out of sync with the DC's  

