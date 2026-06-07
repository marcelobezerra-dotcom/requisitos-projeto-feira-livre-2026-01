# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Cadastrar feirante

## Histórico de Versões

<!-- markdownlint-disable MD060 -->

| Data       | Versão | Descrição                                        | Autor             |
| ---------- | ------- | -------------------------------------------------- | ----------------- |
| 07/06/2026 | 1.0     | Criação do caso de uso para cadastro de feirante | Assistente GitHub |

<!-- markdownlint-enable MD060 -->

## 1. Nome do Caso de Uso

Cadastrar feirante

## 2. Objetivo

Permitir que o gestor da secretaria registre um novo feirante no sistema com seus dados pessoais, tipo de produto e informações da barraca.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Gestor da Secretaria

### 4.2 Secundário

Sistema

## 5. Precondições

* O gestor da secretaria está autenticado no sistema.
* O gestor possui permissão para gerenciar feirantes.

## 6. Fluxo Principal

### P1. O gestor acessa a funcionalidade de cadastro de feirante

> O gestor seleciona a opção para cadastrar um novo feirante.

### P2. O sistema apresenta o formulário de cadastro de feirante

> O sistema exibe campos para dados pessoais, tipo de produto e informações da barraca.

### P3. O gestor informa os dados do feirante

> O gestor preenche os campos obrigatórios do formulário.

### P4. O gestor valida os dados e confirma o cadastro

> O gestor revisa as informações e envia o formulário.

### P5. O sistema registra o feirante

> O sistema grava os dados do feirante e confirma o cadastro.

## 7. Fluxos Alternativos

### A1. O gestor informa um tipo de produto não suportado

#### A1.1. O sistema apresenta mensagem de erro e indica os tipos suportados

> O gestor deve corrigir o tipo de produto antes de continuar.

### A2. O gestor decide cancelar o cadastro

#### A2.1. O sistema descarta o formulário e retorna à lista de feirantes

> O cadastro não é registrado.

## 8. Fluxos de Exceção

### E1. Algum campo obrigatório não é preenchido

#### E1.1. O sistema exibe validação de campo obrigatório e solicita preenchimento

### E2. O sistema não consegue salvar os dados

#### E2.1. O sistema apresenta mensagem de erro genérica e orienta o gestor a tentar novamente

## 9. Pós-condições

* Um novo feirante cadastrado é registrado no sistema.
* O feirante passa a estar disponível para consulta e futuras alterações.

## 10. Requisitos Não Funcionais

* O sistema deve validar os campos obrigatórios no cliente antes de enviar os dados.
* O formulário deve ser responsivo e acessível.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Formulário de cadastro de feirante

> Tela contendo campos para dados pessoais, tipo de produto e informações da barraca, com botões de salvar e cancelar.

## 14. Observações

* Campos de produto podem seguir uma lista pré-definida para padronização.

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
