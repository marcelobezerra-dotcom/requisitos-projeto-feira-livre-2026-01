# Relatórios

Este diretório contém os casos de uso para geração de relatórios de arrecadação e de feirantes ativos.

## Diagrama de Casos de Uso

```mermaid
graph TB
    subgraph Atores
        Gestor["Gestor"]
        Fiscal["Fiscal"]
    end

    subgraph Casos
        Arrecadacao["Gerar relatório de arrecadação"]
        FeirantesAtivos["Gerar relatório de feirantes ativos"]
    end

    Gestor --> Arrecadacao
    Fiscal --> Arrecadacao
    Gestor --> FeirantesAtivos
    Fiscal --> FeirantesAtivos
```

## Casos de Uso

- `Gerar relatório de arrecadação`
- `Gerar relatório de feirantes ativos`
