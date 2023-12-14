- [Base Project to Start Working with Magnolia CE Using JAVA and Maven](#base-project-to-start-working-with-magnolia-ce-using-java-and-maven)
  - [Compile the Project](#compile-the-project)
  - [Start the Project](#start-the-project)
- [Proyecto base para empezar a trabajar en Mangolia CE con JAVA y Maven](#proyecto-base-para-empezar-a-trabajar-en-mangolia-ce-con-java-y-maven)
  - [Crear el proyecto desde cero](#crear-el-proyecto-desde-cero)
  - [Compilar el proyecto](#compilar-el-proyecto)
  - [Arrancar el proyecto](#arrancar-el-proyecto)

# Base Project to Start Working with Magnolia CE Using JAVA and Maven

Create the Project from Scratch

```BASH
mvn archetype:generate -DarchetypeGroupId=info.magnolia.maven.archetypes -DarchetypeArtifactId=magnolia-project-archetype -DarchetypeVersion=RELEASE
```

## Compile the Project

```BASH
mvn clean install
```

## Start the Project

In the webapp folder, execute the following command.

```BASH
cd magnolia-webbri-project-webapp
mvn cargo:run
```

It will deploy Magnolia CE on port `8080`.

---

# Proyecto base para empezar a trabajar en Mangolia CE con JAVA y Maven

## Crear el proyecto desde cero

```BASH
mvn archetype:generate -DarchetypeGroupId=info.magnolia.maven.archetypes -DarchetypeArtifactId=magnolia-project-archetype -DarchetypeVersion=RELEASE
```

## Compilar el proyecto

```BASH
mvn clean install
```

## Arrancar el proyecto

En la carpeta de la webapp lanzamos el siguiente comando.

```BASH
cd magnolia-webbri-project-webapp
mvn cargo:run
```

Nos desplegará Magnolia CE en el puerto `8080`
