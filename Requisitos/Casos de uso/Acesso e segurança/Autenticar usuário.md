# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Autenticar usuário

## Histórico de Versões

| Data       | Versão | Descrição                               | Autor             |
| ---------- | ------ | --------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para autenticação | Assistente GitHub |

## 1. Nome do Caso de Uso

Autenticar usuário

## 2. Objetivo

Permitir login e autenticação de usuários do sistema (gestor, fiscal, feirante quando aplicável).

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Usuário (Gestor/Fiscal/Feirante)

### 4.2 Secundário

Sistema

## 5. Precondições

* Usuário possui credenciais ou processo de recuperação disponível.

## 6. Fluxo Principal

### P1. Usuário acessa tela de login

> Fornece credenciais.

### P2. Sistema valida credenciais

> Concede acesso e cria sessão.

## 7. Fluxos Alternativos

### A1. Recuperação de senha

#### A1.1. Usuário solicita recuperação e segue etapas por e-mail/SMS

## 8. Fluxos de Exceção

### E1. Credenciais inválidas

#### E1.1. Sistema informa erro e bloqueia após tentativas

## 9. Pós-condições

* Sessão autenticada iniciada e auditoria de login registrada.

## 10. Requisitos Não Funcionais

* Suporte a autenticação multifator e políticas de senha.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Tela de login

> Campos para usuário, senha e recuperação de acesso.

## 14. Observações

* Integrar com diretórios corporativos quando aplicável.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
