

# Escenario:

Leer secretos en Vault desde Jenkins Pipeline para publicar en dockerhub nuestra aplicacion java.

## Configurar Jenkins:

** Instalar los plugins: **
Ir a Admnistracion de plugins y buscar e instalar los siguientes:
* Maven
* Hashicorp Vault
* Hashicorp Vault pipelines

**Configurar conexion Jenkins a Vault:**

Ir a Configuracion de Jenkins/configuracion de sistema, buscar la seccion del plugin de Vault:

Colocar URL de Vault:





## Vault:

Crear un secreto tipo KV en Vault, estas credenciales seran de dockehub para poder publicar nuestra imagen de la java-app

ir a Vault




Configurar vault en Jenkins:

Ir a 



# Requisitos:
* Jenkins
* Vault
* Docker
* Maven
* Java


## 
