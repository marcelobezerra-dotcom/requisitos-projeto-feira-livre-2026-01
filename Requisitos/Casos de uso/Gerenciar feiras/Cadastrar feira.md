# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Cadastrar feira

## Histórico de Versões

| Data       | Versão | Descrição                                 | Autor             |
| ---------- | ------ | ----------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para cadastro de feiras | Assistente GitHub |

## 1. Nome do Caso de Uso

Cadastrar feira

## 2. Objetivo

Permitir que o gestor registre uma nova feira com bairro, dia e horário.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Gestor

### 4.2 Secundário

Sistema

## 5. Precondições

* Gestor autenticado e autorizado.

## 6. Fluxo Principal

### P1. O gestor acessa a funcionalidade de cadastro de feira

> Seleciona a opção para cadastrar nova feira.

### P2. O gestor informa os dados da feira

> Preenche bairro, dia da semana e horário.

### P3. O gestor confirma o cadastro

> Salva os dados e o sistema registra a feira.

## 7. Fluxos Alternativos

### A1. Dados inválidos ou faltantes

#### A1.1. O sistema apresenta validações e solicita correção

## 8. Fluxos de Exceção

### E1. Falha ao persistir a feira

#### E1.1. O sistema exibe erro e sugere tentativa posterior

## 9. Pós-condições

* Feira cadastrada disponível para vinculação de feirantes.

## 10. Requisitos Não Funcionais

* Cadastro deve validar conflitos de horário e localização.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Média

## 13. Interface Visual

### IV1. Formulário de cadastro de feira

> Campos: bairro, dia, horário, observações.

## 14. Observações

* Deve considerar restrições legais e sanitárias.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
