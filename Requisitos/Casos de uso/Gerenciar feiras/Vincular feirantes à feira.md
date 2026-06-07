# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Vincular feirantes à feira

## Histórico de Versões

| Data       | Versão | Descrição                                   | Autor             |
| ---------- | ------ | ------------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para vinculação de feirantes | Assistente GitHub |

## 1. Nome do Caso de Uso

Vincular feirantes à feira

## 2. Objetivo

Permitir que o gestor associe feirantes autorizados a uma feira específica.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Gestor

### 4.2 Secundário

Sistema

## 5. Precondições

* Feira e feirante cadastrados e autorizados.

## 6. Fluxo Principal

### P1. O gestor seleciona a feira

> Sistema lista feirantes elegíveis.

### P2. O gestor vincula feirantes

> Seleciona e confirma vinculações.

### P3. O sistema atualiza a lista de participantes

> Registra as vinculações para a data/feira.

## 7. Fluxos Alternativos

### A1. Feirante com débito

#### A1.1. Sistema indica pendências e sugere regularização

## 8. Fluxos de Exceção

### E1. Conflito de vagas ou horários

#### E1.1. Sistema apresenta conflito e solicita ajuste

## 9. Pós-condições

* Feirantes vinculados à feira para a data indicada.

## 10. Requisitos Não Funcionais

* Operação em lote para vincular múltiplos feirantes.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Tela de vinculação de feirantes

> Lista com filtros por tipo de produto e situação financeira.

## 14. Observações

* Deve respeitar regras de prioridade e cotas por tipo de produto.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
