# Gerenciar feiras

Este diretório contém os casos de uso para criação, consulta e vinculação de feirantes às feiras.

## Diagrama de Casos de Uso

```mermaid
graph TB
    subgraph Atores
        Gestor["Gestor"]
    end

    subgraph Casos
        CadastrarFeira["Cadastrar feira"]
        ConsultarFeiras["Consultar feiras"]
        VincularFeirantes["Vincular feirantes à feira"]
    end

    Gestor --> CadastrarFeira
    Gestor --> ConsultarFeiras
    Gestor --> VincularFeirantes
```

## Casos de Uso

- `Cadastrar feira`
- `Consultar feiras`
- `Vincular feirantes à feira`
