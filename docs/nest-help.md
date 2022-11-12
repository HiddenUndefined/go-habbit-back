<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

## Commands

```bash
# Generate Nest application.
$ new|n [options] [name]

# Build Nest application.
$ build [options] [app]

# Run Nest application.
$ start [options] [app]

# Display Nest project details.
$ info|i

# Adds support for an external library to your project.
$ add [options] <library>

# Generate a Nest element.
$ generate|g [options] <schematic> [name] [path]
```

## Schematics available on @nestjs/schematics collection:
| name             | alias           | description                                         |
|------------------|-----------------|-----------------------------------------------------|
| application      | application     | Generate a new application workspace                |
| class            | cl              | Generate a new class                                |
| configuration    | config          | Generate a CLI configuration file                   |
| controller       | co              | Generate a controller declaration                   |
| decorator        | d               | Generate a custom decorator                         |
| filter           | f               | Generate a filter declaration                       |
| gateway          | ga              | Generate a gateway declaration                      |
| guard            | gu              | Generate a guard declaration                        |
| interceptor      | itc             | Generate an interceptor declaration                 |
| interface        | itf             | Generate an interface                               |
| middleware       | mi              | Generate a middleware declaration                   |
| module           | mo              | Generate a module declaration                       |
| pipe             | pi              | Generate a pipe declaration                         |
| provider         | pr              | Generate a provider declaration                     |
| resolver         | r               | Generate a GraphQL resolver declaration             |
| service          | s               | Generate a service declaration                      |
| library          | lib             | Generate a new library within a monorepo            |
| sub-app          | app             | Generate a new application within a monorepo        |
| resource         | res             | Generate a new CRUD resource                        |
