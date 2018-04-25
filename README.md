DevDungeon Library Maven Archetype
==================================

[![Maven metadata URI](https://img.shields.io/maven-metadata/v/http/central.maven.org/maven2/com/devdungeon/maven/archetypes/library/maven-metadata.xml.svg)]()

This archetype is for creating DevDungeon class library projects.

## Installation

Run mvn install on this project to install it to your local repository
and then you can run mvn archetype:generate using the following command.

## Generating a new project using this arhcetype

Minimal options, will prompt for needed values

    mvn archetype:generate                                  \
      -DarchetypeGroupId=com.devdungeon.maven.archetypes    \
      -DarchetypeArtifactId=library                         \
      -DarchetypeVersion=1.0.5                              \
      
Provide all values at once

    mvn archetype:generate                                  \
      -DarchetypeGroupId=com.devdungeon.maven.archetypes    \
      -DarchetypeArtifactId=library                         \
      -DarchetypeVersion=1.0.5                             \
      -DgroupId=com.devdungeon.tools                        \
      -DartifactId=somelibrary                              \
      -Dversion=1.0.0
