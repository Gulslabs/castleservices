**CastleServices** is a sample project that demonstrates setting up Spring Cloud Config Server with local folders. The folder structure `castleconfigrepo` demonstrates on such setup. 

Once **castle-core-service** is started the properties can be accessed via URL.  eg:
[http://localhost:9999/castle-core-service/dev/develop](http://localhost:9999/castle-core-service/dev/develop) - i.e. {application}/{profile}/{label} 

**NOTE**: Login User Name is `user` and password is in the logs of startup under  "Using default security password". 
    