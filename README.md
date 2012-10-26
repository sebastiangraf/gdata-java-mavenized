gdata-java-mavenized
====================

Mavenized fork of the gdata-java-api retrievable under http://code.google.com/p/gdata-java-client/

This project just took the sources, added the external libs as dependencies and acted as base for the third-party upload on maven central as described under https://docs.sonatype.org/display/Repository/Uploading+3rd-party+Artifacts+to+The+Central+Repository

The lib should thereby be accessible under 

```xml
<dependency>
	<groupId>com.google.gdata</groupId>
	<artifactId>core</artifactId>
	<version>1.47.1</version>
</dependency>
```

Important Notes
====================

* Class in com.google.gdata.data.apt was deleted due to compilation error
* libs and debs are entirely excluded
* ant scripts are excluded
* Manifest is excluded

This jar contains only the plain sources of the gdata-java-client within revision 509. 
