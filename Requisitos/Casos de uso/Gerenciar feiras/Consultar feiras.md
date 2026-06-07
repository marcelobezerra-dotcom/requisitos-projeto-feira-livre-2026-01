# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Consultar feiras

## Histórico de Versões

| Data       | Versão | Descrição                               | Autor             |
| ---------- | ------ | --------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para consulta de feiras | Assistente GitHub |

## 1. Nome do Caso de Uso

Consultar feiras

## 2. Objetivo

Permitir que cidadãos e fiscais consultem feiras disponíveis por bairro, dia e horário.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Cidadão / Fiscal

### 4.2 Secundário

Gestor

## 5. Precondições

* Usuário autenticado quando necessário (fiscal/gestor).

## 6. Fluxo Principal

### P1. Usuário abre a tela de consulta de feiras

> Sistema exibe filtros por bairro, dia e horário.

### P2. Usuário aplica filtros

> Sistema apresenta feiras correspondentes.

### P3. Usuário visualiza detalhes

> Visualiza local, horário e feirantes vinculados.

## 7. Fluxos Alternativos

### A1. Sem filtros

#### A1.1. Sistema exibe todas as feiras

## 8. Fluxos de Exceção

### E1. Falha no carregamento de dados

#### E1.1. Sistema exibe mensagem de erro

## 9. Pós-condições

* Usuário obtém informação sobre feiras para planejamento ou fiscalização.

## 10. Requisitos Não Funcionais

* Consulta rápida e responsiva para usuários móveis.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Tela de consulta de feiras

> Lista de feiras com filtros e mapa opcional.

## 14. Observações

* Pode integrar com mapa para direção.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
