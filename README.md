# spring-boot-tomcat-deploy

## tomcat-users
```xml
<role rolename="manager-gui"/>
        <role rolename="manager-script"/>
        <user username="admin" password="password" roles="manager-gui,manager-script" />
```