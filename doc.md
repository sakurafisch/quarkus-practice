# 开始使用 Quarkus

## 运行

```cmd
.\mvnw.cmd compile quarkus:dev # win
./mvnw compile quarkus:dev # zsh
```

## Dev UI

请访问: [http://localhost:8080/q/dev](http:://localhost:8080/q/dev)

## 本项目的创建命令

### 对 Linux 用户
```zsh
mvn io.quarkus.platform:quarkus-maven-plugin:2.1.4.Final:create \
    -DprojectGroupId=org.acme \
    -DprojectArtifactId=getting-started \
    -DclassName="org.acme.getting.started.GreetingResource" \
    -Dpath="/hello"
```

### 对 WIN 用户

#### cmd
```cmd
mvn io.quarkus.platform:quarkus-maven-plugin:2.1.4.Final:create -DprojectGroupId=org.acme -DprojectArtifactId=getting-started -DclassName="org.acme.getting.started.GreetingResource" -Dpath="/hello"
```

#### Powershell
```powershell
mvn io.quarkus.platform:quarkus-maven-plugin:2.1.4.Final:create "-DprojectGroupId=org.acme" "-DprojectArtifactId=getting-started" "-DclassName=org.acme.getting.started.GreetingResource" "-Dpath=/hello"
```

## Mvn 使用

[Maven in 5 Minutes](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html)

```zsh
mvn package
java -cp target/my-app-1.0-SNAPSHOT.jar com.mycompany.app.App

mvn compile
mvn test
mvn site

mvn install # Install .JAR to location repository.
```

## WIN 10 排错指北

]quarkus 2.1.4 - mvnw quarkus:dev not working on windows 10](https://stackoverflow.com/questions/68958241/quarkus-2-1-4-mvnw-quarkusdev-not-working-on-windows-10)
