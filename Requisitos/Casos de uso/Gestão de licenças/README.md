# Gestão de licenças

Este diretório contém os casos de uso para solicitar, aprovar e validar licenças de feirantes.

## Diagrama de Casos de Uso

```mermaid
graph TB
    subgraph Atores
        Feirante["Feirante"]
        Fiscal["Fiscal"]
    end

    subgraph Casos
        SolicitarLicenca["Solicitar licença (TPU)"]
        AprovarReprovar["Aprovar/Reprovar licença"]
        ValidarAutorizacao["Validar feirante autorizado"]
    end

    Feirante --> SolicitarLicenca
    Fiscal --> AprovarReprovar
    Fiscal --> ValidarAutorizacao
```

## Casos de Uso

- `Solicitar licença (TPU)` 
- `Aprovar/Reprovar licença`
- `Validar feirante autorizado`
