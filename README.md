
repo using mvn install like below

```
mvn install:install-file -Dfile=non-maven-proj.jar -DgroupId=some.group -DartifactId=non-maven-proj -Dversion=1 -Dclassifier=x86 -Dpackaging=jar -DcreateChecksum=true -DlocalRepositoryPath=.
```


