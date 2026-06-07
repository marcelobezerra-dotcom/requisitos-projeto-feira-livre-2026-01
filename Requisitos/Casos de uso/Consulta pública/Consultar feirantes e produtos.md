# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Consultar feirantes e produtos

## Histórico de Versões

| Data       | Versão | Descrição                               | Autor             |
| ---------- | ------ | --------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para consulta pública de feirantes e produtos | Assistente GitHub |

## 1. Nome do Caso de Uso

Consultar feirantes e produtos

## 2. Objetivo

Permitir que cidadãos visualizem feirantes e os produtos comercializados nas feiras.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Cidadão

### 4.2 Secundário

Sistema

## 5. Precondições

* Dados públicos de feirantes e produtos disponíveis.

## 6. Fluxo Principal

### P1. Usuário pesquisa por feirante ou produto

> Sistema retorna correspondências com local e feira.

### P2. Usuário visualiza detalhes do produto

> Exibe informações básicas sem dados sensíveis.

## 7. Fluxos Alternativos

### A1. Buscar por categoria de produto

#### A1.1. Sistema lista feirantes que vendem a categoria

## 8. Fluxos de Exceção

### E1. Informação desatualizada

#### E1.1. Sistema apresenta aviso e data da última atualização

## 9. Pós-condições

* Cidadão encontra feirantes e produtos de seu interesse.

## 10. Requisitos Não Funcionais

* Pesquisa deve ser tolerante a erros de digitação.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Média

## 13. Interface Visual

### IV1. Página de consulta de feirantes e produtos

> Campo de pesquisa, filtros por categoria e lista de resultados.

## 14. Observações

* Evitar exposição de dados pessoais sensíveis.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
