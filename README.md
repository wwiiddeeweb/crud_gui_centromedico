# 馃┗ CRUD para Centro M茅dico, gesti贸n de fichas de pacientes.

> **CRUD con GUI en Java SE + Swing + MySQL!**
> Realizado por [Sebasti谩n Kravetz](mailto:sebastiankravetz@icloud.com) para la asignatura de programaci贸n de software de escritorio (PGY2121) en Duoc UC, Sede Vi帽a Del Mar.

Stack utilizado:

- Java SE (OpenJDK 11)
- IDE NetBeans
- Swing (javax.swing)
- MySQL
- DataGrip
- Maven

![Screenshot CRUD GUI CentroM茅dico por @wwiiddeeweb](crud_gui_centromedico.png "Screenshot CRUD GUI CentroM茅dico por @wwiiddeeweb")

## 馃摝 Dependencias:

- mysql-connector-j@8.0.31

## 馃洜 Ejecuci贸n:

Para ejecutar la aplicaci贸n ya compilada con sus dependencias empaquetadas (Maven):

1. Clonar el repositorio y ejecutar:

```
java -jar target/centromedico-1.0-SNAPSHOT-jar-with-dependencies.jar
```

贸 2. Dirgirse a la carpeta _"target"_ y hacer doble click en el archivo centromedico-1.0-SNAPSHOT-jar-with-dependencies.jar

## 馃捊 Base de Datos:

Se ha proporcionado un archivo _paciente.sql_ para la importaci贸n en una base de datos MySQL que debe desplegar de manera local para que la aplicaci贸n se comunique y pueda persistir los datos de las fichas m茅dicas. El string de conexi贸n est谩 presente en el archivo `/src/main/java/com/skravetz/centromedico/database/Conexion.java` en donde puede configurar el usuario y clave respecto de la configuraci贸n de su servidor local MySQL.
