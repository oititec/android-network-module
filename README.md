## android-network-module

#### Instalação via Gradle

No arquivo `settings.gradle` do projeto, adicione o repositório:

```gradle
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        maven { url "https://raw.githubusercontent.com/oititec/android-network-module/master" }
    }
}
```

No arquivo  `build.gradle` do módulo/app, adicione a dependência:

```gradle
dependencies {
    implementation 'br.com.oiti:network:1.0'
}
```
