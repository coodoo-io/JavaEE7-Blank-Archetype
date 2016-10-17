# JavaEE7: Blank Architype
A totally blank configuration ready JavaEE Project!

What does it contain:
- Empty Java EE Project
- beans.xml for CDI
- perstistence.xml for JPA
- JAXRSConfig.java for JAX-RS Webservices
- jboss-web.xml for running .war in root context (localhost:8080 instead of localhost:8080/yourProjectName)

All configuration files have the extension .example by default.
So if you want to use CDI for example just remove the .example extension and your ready to go.
Need a database remove .example extension from persistence.xml, same for JAX-RS,...

How To use:
```sh
mvn archetype:generate -Dfilter=io.coodoo:JavaEE7-Blank-Architype
```
then remove ```.example``` extension as needed.
