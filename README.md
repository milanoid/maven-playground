# Maven playground

![build status](https://github.com/milanoid/maven-playground/actions/workflows/maven.yml/badge.svg?branch=main)

A playground project for Udemy [course](https://www.udemy.com/course/apachemaven/) _Apache Maven: Secrets of Building and Managing Java and Java Spring Projects. Learn to use the Java Build Tool_.

## Maven terminology

Archetype
-
- a project template
- a sample project

`mvn archetype:generate` - offers a list of 3k+ archetypes to use

e.g. archetype [maven-archetype-quickstart](https://maven.apache.org/archetypes/maven-archetype-quickstart/):


`mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4`
