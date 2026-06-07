# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Registrar barraca

## Histórico de Versões

| Data       | Versão | Descrição                              | Autor             |
| ---------- | ------ | -------------------------------------- | ----------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para registro de barraca | Assistente GitHub |

## 1. Nome do Caso de Uso

Registrar barraca

## 2. Objetivo

Permitir vincular uma barraca ao feirante e à feira, com localização e dimensões.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Gestor

### 4.2 Secundário

Sistema

## 5. Precondições

* Feirante e feira já cadastrados.

## 6. Fluxo Principal

### P1. O gestor abre o registro de barraca

> Informa dados da barraca: posição, tamanho e identificação.

### P2. O gestor confirma o registro

> O sistema valida e grava o registro.

## 7. Fluxos Alternativos

### A1. Local ocupado

#### A1.1. Sistema sugere locais alternativos

## 8. Fluxos de Exceção

### E1. Falha ao salvar barraca

#### E1.1. Sistema informa erro e registra tentativa

## 9. Pós-condições

* Barraca registrada e associada ao feirante/feira.

## 10. Requisitos Não Funcionais

* Interface deve permitir mapa simples para posicionamento.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Tela de registro de barraca

> Formulário com posição no mapa e campos técnicos.

## 14. Observações

* Considerar normas de ocupação e acessibilidade.

## 15. Referências

* Visão de demanda

## 16. Checklist de Validação do Artefato (CDU)

- [x] Estrutura mínima preenchida
