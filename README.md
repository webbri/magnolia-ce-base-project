- [Base Project to Start Working with Magnolia CE Using JAVA and Maven](#base-project-to-start-working-with-magnolia-ce-using-java-and-maven)
  - [Create the Project from scratch](#create-the-project-from-scratch)
  - [Compile the Project](#compile-the-project)
  - [Start the Project](#start-the-project)
  - [Create a Maven Module inside the project](#create-a-maven-module-inside-the-project)
- [Proyecto base para empezar a trabajar en Mangolia CE con JAVA y Maven](#proyecto-base-para-empezar-a-trabajar-en-mangolia-ce-con-java-y-maven)
  - [Crear el proyecto desde cero](#crear-el-proyecto-desde-cero)
  - [Compilar el proyecto](#compilar-el-proyecto)
  - [Arrancar el proyecto](#arrancar-el-proyecto)

# Base Project to Start Working with Magnolia CE Using JAVA and Maven

## Create the Project from scratch

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
cd magnolia-project-webapp
mvn cargo:run
```

It will deploy Magnolia CE on port `8080`.

## Create a Maven Module inside the project

```BASH
mvn archetype:generate -DarchetypeGroupId=info.magnolia.maven.archetypes -DarchetypeArtifactId=magnolia-module-archetype -DarchetypeVersion=RELEASE
```

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
cd magnolia-project-webapp
mvn cargo:run
```

Nos desplegará Magnolia CE en el puerto `8080`
