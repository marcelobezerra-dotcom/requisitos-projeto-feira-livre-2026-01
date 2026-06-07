# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Registrar pagamento de taxa

## Histórico de Versões

| Data       | Versão | Descrição                               | Autor             |
| ---------- | ------ | --------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para registro de pagamento | Assistente GitHub |

## 1. Nome do Caso de Uso

Registrar pagamento de taxa

## 2. Objetivo

Permitir que o gestor registre pagamentos realizados pelos feirantes.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Gestor

### 4.2 Secundário

Feirante, Sistema

## 5. Precondições

* Existe um registro de taxa ou cobrança.

## 6. Fluxo Principal

### P1. O gestor seleciona o feirante e registra o pagamento

> Informa valor, data e comprovante.

### P2. O sistema atualiza o saldo e gera recibo

> Registro vinculando pagamento ao feirante.

## 7. Fluxos Alternativos

### A1. Pagamento parcial

#### A1.1. Sistema registra parcela e atualiza saldo

## 8. Fluxos de Exceção

### E1. Falha na gravação do pagamento

#### E1.1. Sistema informa erro e registra tentativa

## 9. Pós-condições

* Débito atualizado e comprovante disponível.

## 10. Requisitos Não Funcionais

* Integração com sistema de arrecadação pode ser necessária.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Tela de registro de pagamento

> Campos de valor, data, forma de pagamento e upload de comprovante.

## 14. Observações

* Deve manter histórico de recibos para auditoria.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
