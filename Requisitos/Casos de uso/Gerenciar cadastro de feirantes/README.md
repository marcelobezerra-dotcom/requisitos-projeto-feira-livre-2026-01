# Gerenciar cadastro de feirantes

Este diretório contém os casos de uso relacionados ao gerenciamento de feirantes, incluindo cadastro, atualização, remoção/inativação, consulta e histórico de alterações.

## Diagrama de Casos de Uso

```mermaid
graph TB
    subgraph Atores
        Gestor["Gestor"]
        Fiscal["Fiscal"]
    end

    subgraph Casos
        Cadastrar["Cadastrar feirante"]
        Atualizar["Atualizar cadastro de feirante"]
        Remover["Remover ou inativar feirante"]
        Consultar["Consultar feirantes"]
        Registrar["Registrar histórico de alterações de feirante"]
        ConsultarHist["Consultar histórico de alterações de feirante"]
    end

    Gestor --> Cadastrar
    Gestor --> Atualizar
    Gestor --> Remover
    Gestor --> Consultar
    Gestor --> Registrar
    Gestor --> ConsultarHist
    Fiscal --> Consultar

    Atualizar --> Registrar
    Remover --> Registrar
```

## Casos de Uso Incluídos

- `Cadastrar feirante`
- `Atualizar cadastro de feirante`
- `Remover ou inativar feirante`
- `Consultar feirantes`
- `Registrar histórico de alterações de feirante`
- `Consultar histórico de alterações de feirante`
