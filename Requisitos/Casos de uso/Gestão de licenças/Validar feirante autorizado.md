# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Validar feirante autorizado

## Histórico de Versões

| Data       | Versão | Descrição                               | Autor             |
| ---------- | ------ | --------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para validação de autorização | Assistente GitHub |

## 1. Nome do Caso de Uso

Validar feirante autorizado

## 2. Objetivo

Permitir que o fiscal verifique se um feirante possui licença válida para atuar.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Fiscal

### 4.2 Secundário

Sistema

## 5. Precondições

* Feirante com cadastro e possível licença registrada.

## 6. Fluxo Principal

### P1. O fiscal pesquisa o feirante

> Localiza por nome ou identificação.

### P2. O sistema retorna status da licença

> Indica se está vigente, expirada ou com pendências.

### P3. O fiscal registra observação se necessário

> Sistema grava a verificação para auditoria.

## 7. Fluxos Alternativos

### A1. Não há licença registrada

#### A1.1. Sistema orienta procedimentos para regularização

## 8. Fluxos de Exceção

### E1. Falha na consulta ao sistema de licenças

#### E1.1. Sistema informa erro e tenta nova consulta

## 9. Pós-condições

* Verificação registrada; ação follow-up possível.

## 10. Requisitos Não Funcionais

* Consulta rápida para uso em campo (dispositivos móveis).

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Tela de validação de licença

> Resultado com status, validade e histórico de pagamentos.

## 14. Observações

* Pode integrar com serviços de pagamento para verificar quitações.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
