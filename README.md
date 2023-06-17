# AspCore_Clean_HRLeaveManagement

Solid principles &amp; Clean architecture for aspcore web api template. Includes blazor webassembly ui, aspcore identity for login &amp; user management, symetric jwt token security 

Services are backed by MySql database and secured by Keycloak oidc provider. Hence, before running microservices locally, I also suggested to run below docker compose which runs latest Keycloak and MySql containers. https://github.com/yesilyurtalper/docker_services/blob/master/compose_mysql_keycloak.yml

After db instance startup, run add-migration and update-database commands from package manager console to create app db. You could also run just update-database if your cloned migrations folder for persistance and identity projects are uptodate. 
