# swagger-codegen-example
Spring swagger codegen

## Getting startedorg.spring

#### Setup maven properties:
 - `swagger.codegen.version` - swagger codegen version (default *2.3.0*)
 - `swagger.specification.path` - path to swagger specification file 
 (default: *${project.basedir}/src/main/resources/swagger.yaml*)
 - `swagger.model.package` - generated models package name (default: *io.swagger.models*)
 - `swagger.controller.package` - generated controllers package name (default: *io.swagger.controllers*)

#### Required settings:
 - Setup parent or groupId in pom.xml file. For successful build your parent must have
 *spring-boot-starter-web* dependecy or you can setup this in this project POM file
 
 