# geoserver-maven
# download the repo and copy into .m2 of artifact repository
# GeoServer uses Apache Maven for a build system. To build the application run maven from the src directory.
# % mvn clean installSome of you may be behind proxy and unable to build Geoserver using maven. We use Nexus here for external packages (node,maven, nuget etc). I was unable to find most of the jars so I posted m2 that was built successfully for GEOTOOLS, GEOWEBCACHE, GEOSERVER. I posted my m2 repository to github which will be very handy if anyone interested. GEOTOOLS 17-SNAPSHOT, GeoServer 2.10 https://github.com/sgavathe/geoserver-maven
