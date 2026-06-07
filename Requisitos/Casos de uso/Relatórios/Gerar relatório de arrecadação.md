# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Gerar relatório de arrecadação

## Histórico de Versões

| Data       | Versão | Descrição                               | Autor             |
| ---------- | ------ | --------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para relatório de arrecadação | Assistente GitHub |

## 1. Nome do Caso de Uso

Gerar relatório de arrecadação

## 2. Objetivo

Gerar relatório mensal das taxas arrecadadas para análise contábil.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Gestor

### 4.2 Secundário

Sistema, Setor Financeiro

## 5. Precondições

* Dados de pagamento atualizados.

## 6. Fluxo Principal

### P1. Gestor solicita geração de relatório

> Define período e filtros.

### P2. Sistema processa e gera relatório

> Relatório em PDF/CSV disponível para download.

## 7. Fluxos Alternativos

### A1. Relatório grande

#### A1.1. Sistema gera em background e notifica quando pronto

## 8. Fluxos de Exceção

### E1. Falha na geração

#### E1.1. Sistema registra erro e notifica administrador

## 9. Pós-condições

* Relatório disponível para análises e exportação.

## 10. Requisitos Não Funcionais

* Relatórios devem ser gerados com tolerância a grandes volumes.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Mensal

## 13. Interface Visual

### IV1. Tela de geração de relatórios

> Seleção de período, formato e campos a incluir.

## 14. Observações

* Exportar para sistemas contábeis quando necessário.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
