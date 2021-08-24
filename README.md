# codeigniter-by-bernardo-pineda
Start files for Bernardo Pineda's Codeigniter 3 course that originally is 2.3GB

# I cannot upload the .htaccess inside system folder
1. create a .htaccess file and copy the code below
2. put it inside system folder

```
<IfModule authz_core_module>
	Require all denied
</IfModule>
<IfModule !authz_core_module>
	Deny from all
</IfModule>
```

