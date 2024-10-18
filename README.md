# Carpinter�a Web Application

## Descripci�n

Este es un proyecto b�sico de una aplicaci�n web para la gesti�n de una carpinter�a, desarrollado utilizando las siguientes tecnolog�as:

- **Java 17**
- **JSP** (Java Server Pages) para la interfaz de usuario.
- **JSTL** (JSP Standard Tag Library) para manejar las etiquetas en JSP.
- **JasperReports** para la generaci�n de reportes.
- **MySQL 8** como base de datos.
- **Maven** para la gesti�n de dependencias.

## Requisitos previos

Antes de ejecutar este proyecto, aseg�rate de tener instalados los siguientes componentes en tu entorno:

1. **Java 17**: El proyecto est� basado en Java 17.
2. **Apache Tomcat 10** o superior: Para desplegar la aplicaci�n web.
3. **MySQL 8**: Base de datos para el almacenamiento de datos de la aplicaci�n.
4. **Maven**: Para gestionar las dependencias del proyecto.
5. **JasperReports**: Para generar reportes dentro de la aplicaci�n.

## Configuraci�n del proyecto

### 1. Configuraci�n de la base de datos

- La base de datos **MySQL 8** debe ser configurada de acuerdo con los scripts SQL ubicados en la carpeta `data/`.
- Ejecuta los scripts en tu servidor MySQL para crear las tablas necesarias para la aplicaci�n.

### 2. Configuraci�n de JasperReports

Aseg�rate de tener JasperReports configurado para la generaci�n de reportes. Los archivos `.jasper` deben ser referenciados correctamente en el c�digo Java correspondiente.

### 3. Configuraci�n de Maven

El archivo `pom.xml` incluye todas las dependencias necesarias para el proyecto. Para instalar las dependencias:

```bash
mvn install
