# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Gerenciar perfis de acesso

## Histórico de Versões

| Data       | Versão | Descrição                               | Autor             |
| ---------- | ------ | --------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para controle de perfis | Assistente GitHub |

## 1. Nome do Caso de Uso

Gerenciar perfis de acesso

## 2. Objetivo

Definir e gerenciar permissões conforme tipo de usuário (gestor, fiscal, feirante).

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Gestor (administrador)

### 4.2 Secundário

Sistema, Usuários

## 5. Precondições

* Usuário administrador autenticado.

## 6. Fluxo Principal

### P1. Administrador acessa painel de perfis

> Cria/edita papéis e atribui permissões.

### P2. Sistema aplica permissões

> Atualiza controles de acesso e auditoria.

## 7. Fluxos Alternativos

### A1. Exceção de permissão

#### A1.1. Sistema revoga ou concede acesso temporário

## 8. Fluxos de Exceção

### E1. Falha ao atualizar permissões

#### E1.1. Sistema registra erro e mantém estado anterior

## 9. Pós-condições

* Permissões atualizadas e auditáveis.

## 10. Requisitos Não Funcionais

* Registro de auditoria e segregação de responsabilidades.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Painel de administração de perfis

> Lista de papéis, permissões e histórico de alterações.

## 14. Observações

* Políticas de senha e MFA devem ser configuráveis.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
