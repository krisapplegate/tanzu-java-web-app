# Accelerator Log

## Options
```json
{
  "projectName" : "tanzu-java-web-app",
  "javaVersion" : "21",
  "buildTool" : "maven",
  "nativeBuild" : false,
  "includeBuildToolWrapper" : true,
  "includeDevContainer" : false
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Exclude, GeneratorValidationTransform, UniquePath)
┃ ┏ engine.transformations[0] (Exclude)
┃ ┃  Info Will exclude [accelerator.yaml, accelerator.axl]
┃ ┃ Debug .tanzuignore didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug LICENSE didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug README-native.md didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug README.md didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug Tiltfile didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug Tiltfile_gradle_intellij didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug Tiltfile_gradle_vscode didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug accelerator.axl matched [accelerator.yaml, accelerator.axl] -> excluded
┃ ┃ Debug accelerator.yaml matched [accelerator.yaml, accelerator.axl] -> excluded
┃ ┃ Debug build.gradle.kts didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug pom.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug settings.gradle didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug catalog/catalog-info.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug config/workload-native.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug config/workload.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/application.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┗ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┏ ┏ engine.transformations[1].validated (Chain)
┃ ┃ ┃  Info Running Chain(IfElse, IfElse, ApplyTo, IfElse, Merge, UniquePath, Merge, UniquePath, Merge, UniquePath, Provenance)
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[0] (IfElse)
┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[0].then (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Exclude, InvokeFragment)
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[0].then.sources[0] (Exclude)
┃ ┃ ┃ ┃ ┃  Info Will exclude [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij]
┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> included
┃ ┃ ┃ ┃ ┃ Debug README-native.md didn't match [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> included
┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> included
┃ ┃ ┃ ┃ ┃ Debug Tiltfile_gradle_intellij matched [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> excluded
┃ ┃ ┃ ┃ ┃ Debug Tiltfile_gradle_vscode matched [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> excluded
┃ ┃ ┃ ┃ ┃ Debug build.gradle.kts matched [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> included
┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> included
┃ ┃ ┃ ┃ ┃ Debug config/workload-native.yaml didn't match [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> included
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> included
┃ ┃ ┃ ┃ ┗ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [*gradle*, Tiltfile_gradle_vscode, Tiltfile_gradle_intellij] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[0].then.sources[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[0].then.sources[1].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[0].then.sources[1].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[0].then.sources[1].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[0].then.sources[1].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeBuildToolWrapper) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[0].then.sources[1].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [mvnw, mvnw.cmd, .mvn/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README-native.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile_gradle_intellij didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile_gradle_vscode didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle.kts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload-native.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug .mvn/wrapper/maven-wrapper.properties matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┗ ┗ ┗ ╺ engine.transformations[1].validated.transformations[0].then.sources[1].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1] (IfElse)
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[2].apply (ReplaceText)
┃ ┃ ┃ ┗  Info Will replace [tanzu-java-web-app->tanzu-java-web-app]
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[3] (IfElse)
┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[3].otherwise (Exclude)
┃ ┃ ┃ ┃  Info Will exclude [config/workload-native.yaml, README-native.md]
┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┃ Debug README-native.md matched [config/workload-native.yaml, README-native.md] -> excluded
┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┃ Debug config/workload-native.yaml matched [config/workload-native.yaml, README-native.md] -> excluded
┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┃ Debug mvnw didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┃ Debug Tiltfile didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┗ Debug config/workload.yaml didn't match [config/workload-native.yaml, README-native.md] -> included
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Include, InvokeFragment)
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┗ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Let
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate (Let)
┃ ┃ ┃ ┃ ┃ ┃ Debug Adding symbol workloadJavaVersion with value '21'
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[0].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[0].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [pom.xml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [pom.xml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [pom.xml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[0].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace regex '<java.version>.*<' with '<java.version>21<'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [build.gradle]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [build.gradle] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[1].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace regex 'sourceCompatibility = .*' with 'sourceCompatibility ...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [build.gradle.kts]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [build.gradle.kts] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[2].delegate.transformations[1] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗  Info Will replace regex '(?<unmodified>JavaVersion\.VERSION_)(\d+)' with '${unmodified}21'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[3].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/workload.yaml, config/workload-native.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/workload.yaml, config/workload-native.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [config/workload.yaml, config/workload-native.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ╺ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[3].delegate.transformations[1] (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[4].delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, Exclude, ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[4].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [config/*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [config/*.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md didn't match [config/*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[4].delegate.transformations[1] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [config/workload*.yaml]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug config/workload.yaml matched [config/workload*.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[0].sources[4].delegate.transformations[2] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗  Info Will replace regex '(?<unmodified>image: bellsoft/liberica-openjdk-\w*:)(\d+)' with '${unmodified}21'
┃ ┃ ┃ ┗ ┗ ┗ ┗ ╺ engine.transformations[1].validated.transformations[4].sources[1].validated.delegate.in.transformations[1] (UniquePath)
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[5] (UniquePath)
┃ ┃ ┃ ┃ Debug Multiple representations for path 'pom.xml', will use the one appearing last 
┃ ┃ ┃ ┗ Debug Multiple representations for path 'config/workload.yaml', will use the one appearing last 
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[6] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Include, InvokeFragment)
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[6].sources[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┗ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[6].sources[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[6].sources[1].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeDevContainer) evaluated to false
┃ ┃ ┃ ┗ ┗ ┗ null ()
┃ ┃ ┃ ╺ engine.transformations[1].validated.transformations[7] (UniquePath)
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[8] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Include, InvokeFragment)
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[8].sources[0] (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [**]
┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug Tiltfile matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug .tanzuignore matched [**] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE matched [**] -> included
┃ ┃ ┃ ┃ ┗ Debug src/main/resources/application.yml matched [**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[8].sources[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[8].sources[1].validated (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Exclude, IfElse)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[8].sources[1].validated.transformations[0] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [README.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/springboot/HelloControllerTest.java didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/HelloController.java didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/springboot/Application.java didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/workload.yaml didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug Tiltfile didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzuignore didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md matched [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[8].sources[1].validated.transformations[1] (IfElse)
┃ ┃ ┃ ┗ ┗ ┗ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[9] (UniquePath)
┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/test/java/com/example/springboot/HelloControllerTest.java', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'mvnw', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/springboot/HelloController.java', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'mvnw.cmd', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'pom.xml', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'catalog/catalog-info.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path '.mvn/wrapper/maven-wrapper.properties', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/springboot/Application.java', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'config/workload.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'Tiltfile', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path '.tanzuignore', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'LICENSE', will use the one appearing last 
┃ ┃ ┃ ┗ Debug Multiple representations for path 'src/main/resources/application.yml', will use the one appearing last 
┃ ┗ ┗ ╺ engine.transformations[1].validated.transformations[10] (Provenance)
┗ ╺ engine.transformations[2] (UniquePath)
```
