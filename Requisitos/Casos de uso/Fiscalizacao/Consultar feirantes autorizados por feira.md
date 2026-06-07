# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Consultar feirantes autorizados por feira

## Histórico de Versões

| Data       | Versão | Descrição                               | Autor             |
| ---------- | ------ | --------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para consulta de feirantes autorizados | Assistente GitHub |

## 1. Nome do Caso de Uso

Consultar feirantes autorizados por feira

## 2. Objetivo

Permitir que o fiscal acesse a lista de feirantes autorizados por feira para fiscalização.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Fiscal

### 4.2 Secundário

Gestor

## 5. Precondições

* Feira com lista de feirantes vinculados.

## 6. Fluxo Principal

### P1. Fiscal seleciona a feira

> Sistema apresenta lista de feirantes autorizados.

### P2. Fiscal verifica regularidade

> Sistema indica licença e situação de pagamento.

## 7. Fluxos Alternativos

### A1. Lista extensa

#### A1.1. Sistema permite filtrar por tipo de produto ou nome

## 8. Fluxos de Exceção

### E1. Dados desatualizados

#### E1.1. Sistema indica necessidade de sincronização

## 9. Pós-condições

* Fiscal obtém informações para ação de fiscalização.

## 10. Requisitos Não Funcionais

* Consulta deve ser possível em dispositivos móveis offline por curto período.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Tela de feirantes por feira

> Lista com indicadores de situação e link para ações.

## 14. Observações

* Deve permitir impressão de lista para uso em campo.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
