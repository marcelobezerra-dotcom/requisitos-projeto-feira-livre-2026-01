# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Registrar histórico de alterações de feirante

## Histórico de Versões

<!-- markdownlint-disable MD060 -->

| Data       | Versão | Descrição                                                                      | Autor             |
| ---------- | ------- | -------------------------------------------------------------------------------- | ----------------- |
| 07/06/2026 | 1.0     | Criação do caso de uso para registro de histórico de alterações de feirante | Assistente GitHub |

<!-- markdownlint-enable MD060 -->

## 1. Nome do Caso de Uso

Registrar histórico de alterações de feirante

## 2. Objetivo

Garantir que o sistema registre as alterações realizadas nos cadastros de feirantes para auditoria e rastreabilidade.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Sistema

### 4.2 Secundário

Gestor da Secretaria

## 5. Precondições

* O cadastro do feirante existe no sistema.
* O gestor da secretaria realiza alteração no cadastro de feirante.
* O sistema está disponível para gravação do histórico.

## 6. Fluxo Principal

### P1. O gestor altera o cadastro de feirante

> O gestor realiza uma modificação nos dados do feirante.

### P2. O sistema detecta a alteração

> O sistema identifica os campos alterados no cadastro.

### P3. O sistema grava o evento no histórico

> O sistema registra data, hora, usuário responsável e detalhes da alteração.

### P4. O sistema confirma o registro do histórico

> O sistema preserva o evento de alteração para consulta futura.

## 7. Fluxos Alternativos

### A1. O gestor altera múltiplos campos

#### A1.1. O sistema registra todas as alterações no mesmo evento de histórico.

### A2. O sistema aplica regras de validação durante a alteração

#### A2.1. Se a alteração for válida, o histórico é registrado. Caso contrário, o sistema impede a gravação até correção.

## 8. Fluxos de Exceção

### E1. O sistema falha ao gravar o histórico

#### E1.1. O sistema exibe mensagem de erro e tenta nova gravação ou registra a falha para análise.

### E2. O sistema não identifica corretamente a alteração

#### E2.1. O sistema alerta sobre inconsistência e solicita nova validação pelo gestor.

## 9. Pós-condições

* O evento de alteração fica registrado no histórico do cadastro do feirante.
* O histórico fica disponível para consulta posterior.

## 10. Requisitos Não Funcionais

* O registro de histórico deve ser persistido de modo confiável e seguro.
* A gravação do histórico não deve impactar a velocidade percebida pelo usuário.
* O histórico deve ser protegido contra edição manual.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Alta

## 13. Interface Visual

### IV1. Registro de histórico de alterações

> Processo interno do sistema que armazena os eventos de alteração enquanto o gestor edita o cadastro.

## 14. Observações

* O histórico pode incluir tanto valores anteriores quanto valores novos para cada campo alterado.

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
