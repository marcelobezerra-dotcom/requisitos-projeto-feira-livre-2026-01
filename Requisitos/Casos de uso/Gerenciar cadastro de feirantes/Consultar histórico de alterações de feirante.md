# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Consultar histórico de alterações de feirante

## Histórico de Versões

<!-- markdownlint-disable MD060 -->

| Data       | Versão | Descrição                                                                      | Autor             |
| ---------- | ------- | -------------------------------------------------------------------------------- | ----------------- |
| 07/06/2026 | 1.0     | Criação do caso de uso para consulta de histórico de alterações de feirante | Assistente GitHub |

<!-- markdownlint-enable MD060 -->

## 1. Nome do Caso de Uso

Consultar histórico de alterações de feirante

## 2. Objetivo

Permitir que o gestor da secretaria visualize o histórico de alterações realizadas em cadastros de feirantes.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Gestor da Secretaria

### 4.2 Secundário

Sistema

## 5. Precondições

* O gestor da secretaria está autenticado no sistema.
* O feirante possui histórico de alterações registrado.
* O gestor possui permissão para consultar o histórico de feirantes.

## 6. Fluxo Principal

### P1. O gestor localiza o feirante

> O gestor seleciona o feirante cujo histórico de alterações deseja consultar.

### P2. O gestor acessa a opção de histórico de alterações

> O gestor abre a seção de histórico do cadastro.

### P3. O sistema exibe o histórico de alterações

> O sistema apresenta a lista de eventos de alteração com data, usuário e mudanças efetuadas.

### P4. O gestor revisa as alterações registradas

> O gestor analisa os eventos para conferir o histórico do cadastro.

## 7. Fluxos Alternativos

### A1. O gestor filtra o histórico por data ou tipo de alteração

#### A1.1. O sistema atualiza a lista de eventos conforme os filtros aplicados

### A2. O gestor seleciona um evento para ver detalhes

#### A2.1. O sistema apresenta as informações completas da alteração selecionada

## 8. Fluxos de Exceção

### E1. Não há histórico para o feirante selecionado

#### E1.1. O sistema exibe mensagem indicando que não há alterações registradas

### E2. O sistema não consegue carregar o histórico

#### E2.1. O sistema apresenta mensagem de erro e orienta o gestor a tentar novamente

## 9. Pós-condições

* O gestor visualiza o histórico de alterações do feirante.
* O histórico de alterações pode ser usado para auditoria e conferência de dados.

## 10. Requisitos Não Funcionais

* A consulta de histórico deve ser eficiente para garantir resposta rápida.
* A interface deve permitir filtrar e ordenar os registros de alteração.
* O histórico de alterações não deve ser editável pelo usuário.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Tela de histórico de alterações de feirante

> Tela ou aba que lista eventos de alteração com filtros de data, usuário e tipo de alteração.

## 14. Observações

* A consulta de histórico deve ser usada para auditoria e controle de alterações.

## 15. Referências

* Visão de demanda do módulo de feirantes.

## 16. Checklist de Validação do Artefato (CDU)

### 16.1 Estrutura mínima

* [X] Nome do caso de uso iniciado com verbo no infinitivo.
* [X] Objetivo claro, direto e com foco em um objetivo principal.
* [X] Tipo do caso de uso informado (concreto/abstrato), quando aplicável.
* [X] Atores primário e secundários identificados corretamente.
* [X] Precondições registradas (ou seção marcada como "Não se aplica").
* [X] Fluxo principal completo e coerente com o objetivo.
* [X] Fluxos alternativos e de exceção definidos quando necessários.
* [X] Pós-condições registradas (ou seção marcada como "Não se aplica").
* [X] Requisitos não funcionais específicos do CDU registrados, quando existirem.
* [X] Pontos de extensão identificados corretamente, quando existirem.
* [X] Frequência de utilização estimada.

### 16.2 Qualidade da especificação

* [X] Passos escritos com linguagem simples e objetiva.
* [X] Ações descritas com verbos no presente do indicativo (3ª pessoa).
* [X] Alternância entre ação do ator e ação da solução está clara.
* [X] Não há ambiguidade (termos vagos sem detalhe técnico).
* [X] Regras de negócio e mensagens estão referenciadas quando necessário.

### 16.3 Consistência e rastreabilidade

* [X] Pontos de entrada e saída dos fluxos alternativos estão explícitos.
* [X] Fluxos de exceção estão vinculados aos passos corretos da solução.
* [X] Referências internas entre passos (retorna/segue para) estão corretas.
* [X] Interface visual (IV1 etc.) está coerente com o fluxo descrito.
* [X] Referências para visão da demanda, glossário e RNF estão atualizadas.

### 16.4 Revisão final

* [X] Não há contradições entre seções do artefato.
* [X] Links internos e externos foram validados.
* [X] Documento revisado por pares.
* [X] Artefato pronto para uso em desenvolvimento e testes.
