# Bitrix24 LDAP testing tool
PHP script which provides testing tools for integration between Bitrix24 and Microsoft Active Directory. This fork contains fix to support Russian language (not my script)

## Usage:
- First put `ldaptest.php` in to `/home/bitrix/www`and open it in browser `yourdomain.tld/ldaptest.php`
- Then create service account in your AD with default permissions, and put login and pass to this script
- `host` - your Domain Controller (ex. 192.168.1.50, mydc.local etc), default port `389`
- `Base DN` ex. `DC=yourdomain,DC=tld`
- `Filter` - LDAP filter what you need [help→](https://social.technet.microsoft.com/wiki/contents/articles/5392.active-directory-ldap-syntax-filters.aspx)
- `Fields` - fields from AD what you need, ex. `mail,givenName,sn`