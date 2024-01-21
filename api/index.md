# Insane Shops API Documentation

## Introduction

The Insane Shops API allows you to integrate the shop system and other features of Insane Shops into your plugin. This documentations provides information on how to import the API library, find the latest version, obtain the API instance, and how to use the API instance.

## Importing the API

We provide importation of the API’s using our personally hosted library repository manager. This allows you to import the API using Maven and Gradle for easy access around the world.
<br>

To add the Insane Shops API library to your project you need to add the following information to your `package.xml`.

To use the Insane Shops API, add the following repository and dependency information to your project’s build file:

```xml
<repositories>
    <repository>
        <id>techscode</id>
        <url>https://repo.techscode.com/repository/techscode-apis/</url>
    </repository>
</repositories>

<dependency>
    <groupId>me.TechsCode</groupId>
    <artifactId>InsaneShopsAPI</artifactId>
    <version>VERSION</version>
    <scope>provided</scope>
</dependency>
```

Make sure to replace `VERSION` with the desired version. You can browse available versions **[here](https://repo.techscode.com/#browse/browse:techscode-apis:me%2FTechsCode%2FInsaneShopsAPI)**.

## Getting the API Instance

To obtain an instance of the Insane Shops API, use the following method:

```java
InsaneShopsAPI api = InsaneShops.getAPI();
```

This instance provides various methods for managing economic features, which are explained in detail on the other pages of this API documentation.