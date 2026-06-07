# Fiscalização

Este diretório contém os casos de uso para fiscalização, verificação de autorizações e registro de ocorrências.

## Diagrama de Casos de Uso

```mermaid
graph TB
    subgraph Atores
        Fiscal["Fiscal"]
        Gestor["Gestor"]
    end

    subgraph Casos
        ConsultarAutorizados["Consultar feirantes autorizados por feira"]
        RegistrarOcorrencia["Registrar ocorrência"]
    end

    Fiscal --> ConsultarAutorizados
    Fiscal --> RegistrarOcorrencia
    Gestor --> ConsultarAutorizados
```

## Casos de Uso

- `Consultar feirantes autorizados por feira`
- `Registrar ocorrência`
