`gradle dockerBuildImage ` - to build docker image  
`gradle dockerBuildImage -DSkipTests -Dorg.gradle.java.home=/usr/lib/jvm/java-11-oracle/` -to build on machine where default java is 1.8   
`dockerCreateDockerfile` `dockerPushImage` - useful