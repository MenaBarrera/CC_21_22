## Configuración adicional GitHub

### Configurar correo
El primer paso antes de usar git es configurar localmente el correo que utilizará github para identificar en los commits. Para ello en la terminal escribiremos
`git config --global user.email "mamb953@correo.ugr.es"` 
Confirmamos que has establecido correctamente la dirección de correo electrónico en Git:
`git config --global user.email` 

![img](https://github.com/MenaBarrera/CC_21_22/blob/main/documentacion/img/correo_git.png)
### Seguridad
Con el fin de incrementar la seguridad de la cuenta se configuran la clave ssh para acceder a los repositorios y se configura la autenticación de doble factor.

Para configurar la clave ssh se deben seguir los siguientes pasos:
1. Crear el par de claves. `ssh-keygen -t ed25519 -C "mamb953@correo.ugr.es" `
2. Mostrar el contenido de la clave publica y pegarlo en el apartado ssh keys de GitHub. ![img](https://github.com/MenaBarrera/CC_21_22/blob/main/documentacion/img/ssh_github.png)
3. Comprobamos que se puede acceder al repositorio usando ssh.
![img](https://raw.githubusercontent.com/MenaBarrera/CC_21_22/main/documentacion/img/clone%20ssh.png)

### Modificar perfil


### Oh my Zsh
