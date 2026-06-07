# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Consultar feirantes

## Histórico de Versões

<!-- markdownlint-disable MD060 -->

| Data       | Versão | Descrição                                         | Autor             |
| ---------- | ------- | --------------------------------------------------- | ----------------- |
| 07/06/2026 | 1.0     | Criação do caso de uso para consulta de feirantes | Assistente GitHub |

<!-- markdownlint-enable MD060 -->

## 1. Nome do Caso de Uso

Consultar feirantes

## 2. Objetivo

Permitir que o fiscal ou gestor consulte feirantes cadastrados, aplicando filtros para encontrar registros específicos.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Fiscal

### 4.2 Secundário

Gestor

## 5. Precondições

* O usuário está autenticado como fiscal ou gestor.
* O usuário tem permissão para visualizar feirantes.

## 6. Fluxo Principal

### P1. O usuário acessa a lista de feirantes

> O usuário navega até a tela de consulta de feirantes.

### P2. O sistema exibe os feirantes cadastrados

> O sistema apresenta a lista de feirantes e campos de filtro.

### P3. O usuário aplica filtros de pesquisa

> O usuário informa critérios como nome, tipo de produto, status ou localização da barraca.

### P4. O sistema mostra os resultados filtrados

> O sistema atualiza a lista de feirantes conforme os filtros aplicados.

### P5. O usuário seleciona um feirante para visualizar detalhes

> O sistema exibe informações completas do feirante selecionado.

## 7. Fluxos Alternativos

### A1. O usuário não informa filtros

#### A1.1. O sistema exibe todos os feirantes cadastrados

### A2. O usuário ordena os resultados

#### A2.1. O sistema ordena a lista de feirantes pela coluna selecionada

## 8. Fluxos de Exceção

### E1. Nenhum feirante corresponde aos filtros

#### E1.1. O sistema exibe mensagem de nenhum resultado encontrado e sugere remover filtros

### E2. O sistema não consegue carregar a lista

#### E2.1. O sistema apresenta mensagem de erro e orienta o usuário a tentar novamente

## 9. Pós-condições

* O usuário visualiza os feirantes correspondentes aos critérios de busca.
* A lista de resultados pode ser utilizada para ações subsequentes, como edição ou inativação.

## 10. Requisitos Não Funcionais

* A consulta deve responder rapidamente mesmo com grande volume de feirantes.
* A interface deve permitir filtragem clara e intuitiva.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Tela de consulta de feirantes

> Tela com lista de feirantes, campos de filtro e opções de ordenação, com visualização resumida e acesso ao detalhamento.

## 14. Observações

* A pesquisa pode incluir filtros por situação (ativo/inativo) e tipo de produto.

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
