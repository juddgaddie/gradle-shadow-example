In order to create an uber jar with sources, I attempt to use the 
ArtifactResolutionQuery api. However it does not resolve sources for project dependencies. 

`$ ./gradlew`

expected: `source artifact resolved for TopLevelModule`  
found: `Top level Module not found in resolved artifacts`


