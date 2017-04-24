# JavaEE7: Blank Archetype
A totally blank configuration ready JavaEE 7 Project.

What does it contain:
- Empty Java EE Project structure - maven build ready
- Example beans.xml for CDI
- Example perstistence.xml for JPA
- Example JAXRSConfig.java for JAX-RS Web Services

All configuration files have the extension .example by default, so they are not directly active.
If you want to use CDI for example just remove the .example extension and your ready to go.
Need a database remove .example extension from persistence.xml, same for JAX-RS,...

How To use with interactive mode:
```sh
mvn archetype:generate -Dfilter=io.coodoo:JavaEE7-Blank-Archetype
```


```sh
mvn archetype:generate                        \
-DarchetypeGroupId=io.coodoo                  \
-DarchetypeArtifactId=JavaEE7-Blank-Archetype \
-DarchetypeVersion=1.0                        \
-DgroupId=<yourGroupId>                       \
-DartifactId=<yourArtifactId>                 \
-Dversion=1.1-SNAPSHOT
```

Remove ```.example``` extension as needed.
