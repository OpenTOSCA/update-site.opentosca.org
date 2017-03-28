# OpenTOSCA Update Site

> Update site for 3rd party dependencies used by OpenTOSCA Eclipse/OSGi projects.

The update site will be generated using Maven's dependency plugin and Tycho's plugins to generate a P2 repository.

---

### Build the repository

```shell
mvn clean package
```

### Serve the repository locally 

```shell
mvn jetty:run
```

Go to http://localhost:9000/repository.
