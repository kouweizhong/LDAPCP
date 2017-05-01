DAPCP for SharePoint 2013 and 2016
===================
![People picker with LDAPCP](https://cloud.githubusercontent.com/assets/8788631/25440961/3b8db40a-2aa1-11e7-9070-aee808950f38.PNG)

> **Notes:** 
> - This project used to be hosted on [Codeplex](https://ldapcp.codeplex.com/) but it was moved here since Codeplex is shutting down.
> - Please [click here](https://github.com/Yvand/LDAPCP/wiki/How-to-install-LDAPCP) to see how to install LDAPCP and [visit the wiki](https://github.com/Yvand/LDAPCP/wiki) to find documentation.

Features
-------------
- Easy to configure with administration pages added in Central administration > Security. 
- Queries multiple servers in parallel (multi-threaded connections). 
- Populates properties (e.g. email, SIP, display name) upon permission creation. 
- Supports rehydration for provider-hosted add-ins. 
- Supports dynamics tokens "{domain}" and "{fqdn}" to add domain information on permissions to create. 
- Implements SharePoint logging infrastructure and logs messages in Area/Product "LDAPCP". 
- Ensures thread safety. 
- Implements augmentation to add group membership to security tokens.

Customization capabilities
-------------
- Customize list of claim types, and their mapping with LDAP objects. 
- Enable/disable augmentation globally or per LDAP connection. 
- Customize display of permissions. 
- Customize LDAP filter per claim type, e.g. to only return users member of a specific security group. 
- Set a keyword to bypass LDAP lookup. e.g. input "extuser:partner@contoso.com" directly creates permission "partner@contoso.com" on claim type set for this. 
- Set a prefix to add to LDAP results, e.g. add "domain\" to groups returned by LDAP. 
- Hide disabled users and distribution lists. 
- Developers can easily do a lot more by inheriting base class.

