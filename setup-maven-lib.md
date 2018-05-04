# set up mvn library for amazon

## To Start the import library

- Import pom.xml into IDE
 - `mvn install:install-file -Dfile=/path-to-file/cloudhsm-1.0.jar -DgroupId=com.cloudhsmaws \
 -DartifactId=hamcrest -Dversion=1.0 \ - Dpackaging=jar-DlocalRepositoryPath=/Users/carllin/.m2/repository/`
 - `mvn install:install-file -Dfile=/path-to-file/hamcrestaws-1.3.jar -DgroupId=com.hamcrestaws \
 -DartifactId=hamcrest -Dversion=1.3 \ - Dpackaging=jar-DlocalRepositoryPath=/Users/carllin/.m2/repository/`
