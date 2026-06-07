# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Consultar débitos

## Histórico de Versões

| Data       | Versão | Descrição                               | Autor             |
| ---------- | ------ | --------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para consulta de débitos | Assistente GitHub |

## 1. Nome do Caso de Uso

Consultar débitos

## 2. Objetivo

Permitir que gestor e feirante verifiquem taxas pendentes.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Gestor / Feirante

### 4.2 Secundário

Sistema

## 5. Precondições

* Histórico de cobranças disponível.

## 6. Fluxo Principal

### P1. Usuário solicita consulta de débitos

> Sistema retorna lista de pendências e valores.

### P2. Usuário visualiza opções de pagamento

> Sistema indica formas e links para quitar débitos.

## 7. Fluxos Alternativos

### A1. Nenhum débito encontrado

#### A1.1. Sistema exibe mensagem de sem pendências

## 8. Fluxos de Exceção

### E1. Falha ao recuperar dados financeiros

#### E1.1. Sistema informa erro e orienta tentativa posterior

## 9. Pós-condições

* Usuário informado sobre situação financeira.

## 10. Requisitos Não Funcionais

* Dados financeiros devem ser exibidos com segurança e privacidade.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Tela de consulta de débitos

> Lista de débitos com filtros por período.

## 14. Observações

* Possibilidade de exportar histórico para efeitos fiscais.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
