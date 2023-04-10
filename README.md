# Primeiros passos com stackspot

Para a criação de uma stack, foi utilizado o comando:
```shell
$ stk create stack hands-on-kotlin-stack
```

Em seguida foi criada um template chamada **base-template**, a partir do comando:
```shell
$ stk create template base-template
```
Essa a primeira template que será trabalhada no capítulo 1.

## 1. Template de Kotlin + Spring + Gradle

Se o usuário for utilizar essa template para um **test-app** (como exemplo), ele terá que refenciar a **stack** e a **template** como no comando a seguir.
```shell
$ stk create app test-app --template-path hands-on-kotlin-stack/base-template
```

Onde estão minhas configurações do Jinja?

- [project_name] settings.gradle.kts / README.md
- [project_groupid] build.gradle.kts
- [project_version] build.gradle.kts
- [project_description] README.md