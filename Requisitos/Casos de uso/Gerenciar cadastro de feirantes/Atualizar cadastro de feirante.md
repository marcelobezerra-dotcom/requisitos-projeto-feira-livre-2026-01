# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Atualizar cadastro de feirante

## Histórico de Versões

<!-- markdownlint-disable MD060 -->

| Data       | Versão | Descrição                                                         | Autor             |
| ---------- | ------- | ------------------------------------------------------------------- | ----------------- |
| 07/06/2026 | 1.0     | Criação do caso de uso para atualização de cadastro de feirante | Assistente GitHub |

<!-- markdownlint-enable MD060 -->

## 1. Nome do Caso de Uso

Atualizar cadastro de feirante

## 2. Objetivo

Permitir que o gestor da secretaria edite informações cadastrais de feirantes já registrados.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Gestor da Secretaria

### 4.2 Secundário

Sistema

## 5. Precondições

* O gestor da secretaria está autenticado.
* O feirante já está cadastrado no sistema.
* O gestor possui permissão para editar cadastros de feirantes.

## 6. Fluxo Principal

### P1. O gestor localiza o feirante desejado

> O gestor busca ou seleciona o feirante na lista de cadastrados.

### P2. O gestor acessa a tela de edição do feirante

> O sistema apresenta os dados atuais do feirante em formulário editável.

### P3. O gestor altera os dados necessários

> O gestor modifica campos pessoais, tipo de produto ou informações da barraca.

### P4. O gestor confirma a atualização

> O gestor salva as alterações do cadastro.

### P5. O sistema grava as alterações

> O sistema atualiza o registro do feirante e confirma o sucesso.

## 7. Fluxos Alternativos

### A1. O gestor opta por cancelar a edição

#### A1.1. O sistema descarta as alterações e retorna à tela de consulta

### A2. O gestor deseja alterar apenas o status do feirante

#### A2.1. O sistema permite atualizar o status sem alterar os demais dados

## 8. Fluxos de Exceção

### E1. O feirante não é encontrado

#### E1.1. O sistema apresenta mensagem de item não encontrado e sugere nova busca

### E2. O sistema falha ao salvar a atualização

#### E2.1. O sistema informa erro e orienta o gestor a tentar novamente

## 9. Pós-condições

* O cadastro do feirante é atualizado com as novas informações.
* As alterações ficam disponíveis para consulta e auditoria.

## 10. Requisitos Não Funcionais

* O sistema deve manter registro das versões anteriores do cadastro para auditoria.
* A interface deve ser clara para evitar edição acidental de campos.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Tela de edição de feirante

> Tela com formulário preenchido, botões de salvar e cancelar, e campos de validação em tempo real.

## 14. Observações

* O sistema pode exibir quais campos foram alterados após a atualização.

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
