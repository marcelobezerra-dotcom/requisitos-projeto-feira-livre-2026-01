# Acesso e segurança

Este diretório contém os casos de uso relacionados à autenticação de usuários e ao gerenciamento de perfis de acesso.

## Diagrama de Casos de Uso

```mermaid
graph TB
    subgraph Atores
        Gestor["Gestor"]
        Fiscal["Fiscal"]
        Feirante["Feirante"]
    end

    subgraph Casos
        Autenticar["Autenticar usuário"]
        GerenciarPerfis["Gerenciar perfis de acesso"]
    end

    Gestor --> Autenticar
    Fiscal --> Autenticar
    Feirante --> Autenticar
    Gestor --> GerenciarPerfis
    Fiscal --> GerenciarPerfis
```

## Casos de Uso

- `Autenticar usuário`
- `Gerenciar perfis de acesso`
