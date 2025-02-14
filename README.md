# **Mi proyecto Web** 🦖

## ❣️ **¡Bienvenido a mi proyecto!** ❣️

Este proyecto se enfoca en el estudio y la aplicación de sistemas de control de versiones, específicamente Git y GitHub, como herramientas clave en el desarrollo de software. El propósito principal es comprender cómo estas herramientas permiten llevar un registro detallado de los cambios realizados en un proyecto a lo largo del tiempo, facilitando la colaboración entre diferentes desarrolladores y evitando conflictos durante el proceso de desarrollo.

El proyecto busca enseñar los conceptos fundamentales de Git, como la creación de repositorios, el control de versiones, la ramificación (branching) y las fusiones (merging), así como la integración de Git con GitHub para almacenar y compartir proyectos en línea.

A través de la implementación práctica de Git y GitHub, se pretende aprender a organizar y controlar el desarrollo de proyectos de manera efectiva

## Características y funcionalidades 

**Git**
 ![Texto alternativo](https://i.imgur.com/ayph4Vh.png)
- **Seguimiento de cambios**: Git permite llevar un registro completo de todos los cambios realizados en los archivos del proyecto, lo que facilita la revisión y restauración de versiones anteriores si es necesario.
- **Commit de cambios**: Cada cambio realizado en el código o archivos se puede "confirmar" (commit), lo que permite capturar el estado exacto del proyecto en momentos específicos.
- **Ramas (Branching)**: Git permite la creación de ramas para el desarrollo de nuevas características o la corrección de errores sin afectar la versión principal del proyecto.
- **Fusión de ramas (Merging)**: Cuando una rama ha sido desarrollada y probada, puede ser fusionada de vuelta a la rama principal sin perder los cambios realizados.


**Git Hub**
 ![Texto alternativo](https://i.imgur.com/cdl92KT.png)
- **Repositorios remotos**: GitHub ofrece una plataforma para almacenar repositorios de código de manera remota, lo que permite a los desarrolladores colaborar en proyectos desde cualquier lugar del mundo.
- **Forks y Pull Requests**: GitHub permite que cualquier usuario realice un "fork" del proyecto para hacer cambios y luego envíe un "pull request" para que esos cambios sean revisados e incorporados al proyecto principal por los administradores.


## Instalación de Git en Windows  
Dirígete al sitio web oficial de Git _(haciendo clic en el icono de git que aparece abajo):_ 

[![Imagen Git](https://i.imgur.com/6ew7sk8.png)](https://git-scm.com/downloads/win)
- Haz clic en "Click here to download" si tienes Windows y tu ordenador usa 64bits, si no tendras que revisar cual intalador necesitas de la lista de abajo 
![Texto alternativo](https://i.imgur.com/1WX2ar4.png)
- Ejecuta el archivo descargado y sigue los pasos del instalador. Asegúrate de seleccionar las opciones predeterminadas si no estás seguro de qué elegir.
- Una vez finalizada la instalación, abre Git Bash (una terminal de comandos especial para Git) desde el menú de inicio y verifica que Git está instalado correctamente ejecutando el siguiente comando:
  
![Texto alternativo](https://i.imgur.com/D1bNQug.png)
### Configurar Git
- Abre la terminal o Git Bash y ejecuta los siguientes comandos, reemplazando Tu Nombre y tu-email@ejemplo.com por tu información personal:
  
![Texto alternativo](https://i.imgur.com/NMOpFx0.png)

### Clonar un repositorio a tu máquina local
Ahora que tienes un repositorio en GitHub, puedes clonar una copia de él en tu ordenador para empezar a trabajar en el proyecto.
- Abre la terminal o Git Bash y navega hasta el directorio donde quieras clonar el repositorio.
- Usa el siguiente comando (reemplaza URL_DEL_REPOSITORIO con la URL de tu repositorio en GitHub):
  
![Texto alternativo](https://i.imgur.com/Chk3Y6P.png)

como ejemplo:

![Texto alternativo](https://i.imgur.com/Qn2vIbm.png)
### Realizar cambios y guardarlos
- Realizar cambios en los archivos: Edita los archivos del proyecto con tu editor de texto o IDE favorito.
- Añadir los cambios a Git: Una vez que hayas realizado cambios, utiliza los siguientes comandos para añadir y confirmar los cambios.
Para añadir los cambios, ejecuta:

![Texto alternativo](https://i.imgur.com/azlR9YV.png)

Para confirmar los cambios (hacer un commit), ejecuta:

![Texto alternativo](https://i.imgur.com/7bwcaye.png)

Subir los cambios a GitHub: Después de hacer un commit, puedes subir tus cambios a GitHub usando:

![Texto alternativo](https://i.imgur.com/SrZURhg.png)

Cambia a la rama principal:

![Texto alternativo](https://i.imgur.com/mKb1k49.png)

Luego, fusiona los cambios de la otra rama:

![Texto alternativo](https://i.imgur.com/bX9bKHs.png)

### Crear una nueva rama (branch)
Si quieres trabajar en una nueva funcionalidad sin afectar la rama principal, crea una nueva rama de la siguiente forma:

![Texto alternativo](https://i.imgur.com/BnSoD88.png)

## Requisitos previos
Para que el proyecto funcione correctamente y puedas trabajar con Git y GitHub de manera efectiva, hay algunas dependencias y configuraciones que debes tener en cuenta:

### **- Sistema operativo compatible**

El proyecto es compatible con los siguientes sistemas operativos:

Windows (7 o superior)

macOS (10.9 o superior)

Linux (cualquier distribución moderna)

### **- Instalación de Git**
Git es una herramienta fundamental para el control de versiones y es indispensable para interactuar con repositorios tanto locales como remotos. Asegúrate de tener Git instalado y correctamente configurado.

![Texto alternativo](https://i.imgur.com/D1bNQug.png)

### **- Cuenta en GitHub**
Para poder utilizar GitHub como repositorio remoto, necesitas tener una cuenta en GitHub
- Regístrate en GitHub si aún no tienes una cuenta.
- Crear repositorios en GitHub y gestionar tus proyectos de manera remota.
### **- Conexión a Internet**
Una conexión a internet estable es necesaria para:

- Clonar repositorios remotos.
- Subir (push) tus cambios a GitHub.
- Descargar (pull) los cambios realizados.

### **- Editor de texto o IDE**
Para editar el código, necesitarás un editor de texto o un entorno de desarrollo integrado (IDE). 

Algunos populares son:

- Visual Studio Code: Ligero y con muchas extensiones útiles para trabajar con Git.
### **- Configuración de Git (Nombre y Correo)**

Antes de comenzar a usar Git, es importante que configures tu nombre y correo electrónico. Esto es necesario para que Git registre correctamente tus contribuciones al proyecto.
Como ya explique anteiormente en el apartado de _"configurar Git"_

### **- Permisos de acceso al repositorio en GitHub**

Si estás colaborando en un proyecto privado, necesitarás permisos para acceder al repositorio en GitHub. Asegúrate de:

Ser invitado al repositorio si es privado.
Tener acceso de escritura para poder subir cambios (en proyectos donde solo tienes acceso de lectura, no podrás hacer push).

### **- Conocimiento básico de Git y GitHub**
Aunque no es una dependencia técnica estricta, tener un conocimiento básico de cómo usar Git y GitHub es altamente recomendable para evitar errores comunes y facilitar el flujo de trabajo.
- Hacer commits, push y pull.
- Trabajar con ramas.
- Resolver conflictos de fusión (merge).

## Licencia

Este proyecto está licenciado bajo los términos de la Licencia Pública General GNU v3 (GPL v3)

- Puedes usar, copiar, modificar y distribuir el software de manera gratuita, siempre que las versiones modificadas también estén disponibles bajo la misma licencia GPL v3.
- Cualquier software derivado debe ser distribuido bajo la misma licencia GPL v3.
- Debes proporcionar acceso al código fuente completo cuando distribuyas el software o sus modificaciones.
## Authors

- [@Isabel Barroso](https://github.com/isabel992)
