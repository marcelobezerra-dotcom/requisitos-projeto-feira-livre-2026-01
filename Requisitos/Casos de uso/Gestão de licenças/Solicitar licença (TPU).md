# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Solicitar licença (TPU)

## Histórico de Versões

| Data       | Versão | Descrição                               | Autor             |
| ---------- | ------ | --------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para solicitar licença | Assistente GitHub |

## 1. Nome do Caso de Uso

Solicitar licença (TPU)

## 2. Objetivo

Permitir que o feirante solicite autorização para atuar em uma feira.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Feirante

### 4.2 Secundário

Gestor, Sistema

## 5. Precondições

* Feirante cadastrado.

## 6. Fluxo Principal

### P1. O feirante abre formulário de solicitação

> Preenche dados necessários e anexa documentos.

### P2. O feirante envia solicitação

> Sistema registra pedido e notifica o gestor.

## 7. Fluxos Alternativos

### A1. Documentos incompletos

#### A1.1. Sistema solicita complementação de documentação

## 8. Fluxos de Exceção

### E1. Falha no envio

#### E1.1. Sistema informa erro e permite reenvio

## 9. Pós-condições

* Solicitação criada e disponível para análise.

## 10. Requisitos Não Funcionais

* Upload de documentos deve aceitar formatos comuns e ter limite de tamanho.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Média

## 13. Interface Visual

### IV1. Formulário de solicitação de licença

> Campos para dados, anexos e botão enviar.

## 14. Observações

* Integrar com fluxo de análise e pagamento quando aplicável.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
