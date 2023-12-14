# Proyecto base para empezar a trabajar en Mangolia CE con JAVA y Maven

# Crear el proyecto desde cero

```BASH
mvn archetype:generate -DarchetypeGroupId=info.magnolia.maven.archetypes -DarchetypeArtifactId=magnolia-project-archetype -DarchetypeVersion=RELEASE
```

# Compilar el proyecto

```BASH
mvn clean install
```

# Arrancar el proyecto

En la carpeta de la webapp lanzamos el siguiente comando.

```BASH
cd magnolia-webbri-project-webapp
mvn cargo:run
```

Nos desplegará Magnolia CE en el puerto `8080`
