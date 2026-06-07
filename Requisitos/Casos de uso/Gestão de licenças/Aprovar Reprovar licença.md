# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Aprovar/Reprovar licença

## Histórico de Versões

| Data       | Versão | Descrição                               | Autor             |
| ---------- | ------ | --------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para análise de licença | Assistente GitHub |

## 1. Nome do Caso de Uso

Aprovar/Reprovar licença

## 2. Objetivo

Permitir que o gestor analise solicitações de licença e aprove ou reprove conforme regras.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Gestor

### 4.2 Secundário

Sistema, Feirante

## 5. Precondições

* Solicitação registrada e documentos disponíveis.

## 6. Fluxo Principal

### P1. O gestor revisa a solicitação

> Analisa dados e documentos anexados.

### P2. O gestor aprova ou reprova

> Registra decisão e motivações; notifica o feirante.

## 7. Fluxos Alternativos

### A1. Solicitação pendente de informação

#### A1.1. Gestor solicita complementação e solicita aguardando resposta

## 8. Fluxos de Exceção

### E1. Sistema falha ao notificar

#### E1.1. Sistema registra tentativa e aguarda reenvio

## 9. Pós-condições

* Decisão registrada; status da solicitação atualizado.

## 10. Requisitos Não Funcionais

* Auditoria das decisões deve ser preservada.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Tela de análise de solicitações

> Lista de solicitações com opção de visualizar documentos e registrar decisão.

## 14. Observações

* Deve suportar lista de pendências e filtros por urgência.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
