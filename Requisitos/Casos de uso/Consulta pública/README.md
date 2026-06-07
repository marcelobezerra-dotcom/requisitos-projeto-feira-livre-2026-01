# Consulta pública

Este diretório contém os casos de uso para consultas públicas de feiras, feirantes e produtos.

## Diagrama de Casos de Uso

```mermaid
graph TB
    subgraph Atores
        Publico["Usuário público"]
    end

    subgraph Casos
        ConsultarFeiras["Consultar feiras"]
        ConsultarFeirantes["Consultar feirantes e produtos"]
    end

    Publico --> ConsultarFeiras
    Publico --> ConsultarFeirantes
```

## Casos de Uso

- `Consultar feiras`
- `Consultar feirantes e produtos`
