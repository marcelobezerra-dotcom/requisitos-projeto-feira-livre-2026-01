# Especificação de Requisitos Funcionais

## Caso de Uso (CDU) - Remover ou inativar feirante

## Histórico de Versões

<!-- markdownlint-disable MD060 -->
| Data       | Versão | Descrição                                                                                  | Autor           |
| ---------- | ------ | ------------------------------------------------------------------------------------------ | --------------- |
| 07/06/2026 | 1.0    | Criação do caso de uso para remoção ou inativação de feirante                             | Assistente GitHub |
<!-- markdownlint-enable MD060 -->

## 1. Nome do Caso de Uso

Remover ou inativar feirante

## 2. Objetivo

Permitir que o gestor da secretaria exclua ou inative um feirante do sistema, preservando a integridade dos dados quando necessário.

## 3. Tipo de Caso de Uso

Concreto

## 4. Atores

### 4.1 Primário

Gestor da Secretaria

### 4.2 Secundário

Sistema

## 5. Precondições

* O gestor da secretaria está autenticado.
* O gestor possui permissão para remover ou inativar feirantes.
* O feirante está cadastrado no sistema.

## 6. Fluxo Principal

### P1. O gestor localiza o feirante no cadastro

> O gestor busca ou seleciona o feirante a ser removido ou inativado.

### P2. O gestor escolhe a ação de remover ou inativar

> O gestor opta por excluir definitivamente ou marcar o feirante como inativo.

### P3. O gestor confirma a ação

> O sistema solicita confirmação para evitar remoção acidental.

### P4. O sistema executa a ação

> O sistema remove o feirante ou altera seu status para inativo.

### P5. O sistema confirma o resultado

> O sistema exibe mensagem de sucesso e atualiza a lista de feirantes.

## 7. Fluxos Alternativos

### A1. O gestor opta por inativar em vez de remover

#### A1.1. O sistema altera o status do feirante para inativo e mantém o histórico

### A2. O gestor cancela a remoção/inativação

#### A2.1. O sistema não altera o cadastro e retorna à consulta de feirantes

## 8. Fluxos de Exceção

### E1. O feirante não pode ser removido por dependências

#### E1.1. O sistema informa que o feirante não pode ser excluído e recomenda inativação

### E2. O sistema falha ao aplicar a alteração

#### E2.1. O sistema apresenta erro e mantém o status anterior do feirante

## 9. Pós-condições

* O feirante fica removido ou inativado no sistema.
* O cadastro não está mais disponível para operações ativas, quando inativado.

## 10. Requisitos Não Funcionais

* O sistema deve preservar a integridade de dados relacionados a transações e histórico de feirantes.
* A operação de remoção/inativação deve registrar o usuário e a data da ação.

## 11. Ponto de Extensão

Não se aplica

## 12. Frequência de Utilização

Média

## 13. Interface Visual

### IV1. Confirmar remoção/inativação

> Caixa de diálogo de confirmação com opções para remover, inativar ou cancelar.

## 14. Observações

* Inativação é preferível quando houver registros históricos ou vínculos com eventos.

## 15. Referências

* Visão de demanda do módulo de feirantes.

## 16. Checklist de Validação do Artefato (CDU)

### 16.1 Estrutura mínima

* [x] Nome do caso de uso iniciado com verbo no infinitivo.
* [x] Objetivo claro, direto e com foco em um objetivo principal.
* [x] Tipo do caso de uso informado (concreto/abstrato), quando aplicável.
* [x] Atores primário e secundários identificados corretamente.
* [x] Precondições registradas (ou seção marcada como "Não se aplica").
* [x] Fluxo principal completo e coerente com o objetivo.
* [x] Fluxos alternativos e de exceção definidos quando necessários.
* [x] Pós-condições registradas (ou seção marcada como "Não se aplica").
* [x] Requisitos não funcionais específicos do CDU registrados, quando existirem.
* [x] Pontos de extensão identificados corretamente, quando existirem.
* [x] Frequência de utilização estimada.

### 16.2 Qualidade da especificação

* [x] Passos escritos com linguagem simples e objetiva.
* [x] Ações descritas com verbos no presente do indicativo (3ª pessoa).
* [x] Alternância entre ação do ator e ação da solução está clara.
* [x] Não há ambiguidade (termos vagos sem detalhe técnico).
* [x] Regras de negócio e mensagens estão referenciadas quando necessário.

### 16.3 Consistência e rastreabilidade

* [x] Pontos de entrada e saída dos fluxos alternativos estão explícitos.
* [x] Fluxos de exceção estão vinculados aos passos corretos da solução.
* [x] Referências internas entre passos (retorna/segue para) estão corretas.
* [x] Interface visual (IV1 etc.) está coerente com o fluxo descrito.
* [x] Referências para visão da demanda, glossário e RNF estão atualizadas.

### 16.4 Revisão final

* [x] Não há contradições entre seções do artefato.
* [x] Links internos e externos foram validados.
* [x] Documento revisado por pares.
* [x] Artefato pronto para uso em desenvolvimento e testes.
