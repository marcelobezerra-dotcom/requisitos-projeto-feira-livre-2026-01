# Gestão de taxas

Este diretório contém os casos de uso para consulta e pagamento de taxas, além da validação de participação.

## Diagrama de Casos de Uso

```mermaid
graph TB
    subgraph Atores
        Feirante["Feirante"]
        Gestor["Gestor"]
    end

    subgraph Casos
        ConsultarDebitos["Consultar débitos"]
        RegistrarPagamento["Registrar pagamento de taxa"]
        ValidarPagamento["Validar pagamento para participação"]
    end

    Feirante --> ConsultarDebitos
    Feirante --> RegistrarPagamento
    Gestor --> ValidarPagamento
```

## Casos de Uso

- `Consultar débitos`
- `Registrar pagamento de taxa`
- `Validar pagamento para participação`
