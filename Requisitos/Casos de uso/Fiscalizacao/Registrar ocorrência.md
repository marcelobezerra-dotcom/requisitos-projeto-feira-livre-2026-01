# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Registrar ocorrência

## Histórico de Versões

| Data       | Versão | Descrição                               | Autor             |
| ---------- | ------ | --------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para registrar ocorrências | Assistente GitHub |

## 1. Nome do Caso de Uso

Registrar ocorrência

## 2. Objetivo

Permitir que o fiscal registre irregularidades ou ocorrências durante a fiscalização.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Fiscal

### 4.2 Secundário

Sistema, Gestor

## 5. Precondições

* Fiscal autenticado e autorizado.

## 6. Fluxo Principal

### P1. Fiscal inicia registro de ocorrência

> Seleciona feirante e descreve a ocorrência.

### P2. Fiscal anexa evidências

> Fotos ou documentos são anexados.

### P3. Fiscal salva ocorrência

> Sistema grava e notifica gestor quando aplicável.

## 7. Fluxos Alternativos

### A1. Ocorrência cancelada

#### A1.1. Sistema descarta o registro em andamento

## 8. Fluxos de Exceção

### E1. Falha no upload de evidências

#### E1.1. Sistema grava texto e tenta reenviar arquivos

## 9. Pós-condições

* Ocorrência registrada para análise e ação posterior.

## 10. Requisitos Não Funcionais

* Permitir operação em campo com conectividade intermitente.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Média

## 13. Interface Visual

### IV1. Formulário de ocorrência

> Campo de texto, opção de anexar fotos e gravar localização.

## 14. Observações

* Registro deve suportar confidencialidade quando necessário.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
