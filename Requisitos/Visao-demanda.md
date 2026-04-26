# Visão da Demanda (VD)

## Histórico de Versões

| Data       | Versão | Descrição                                                      | Autor        |
| ---------- | ------- | ---------------------------------------------------------------- | ------------ |
| 18/04/2026 | 1.0     | Criação do documento de visão e adição do log               | Prof Bezerra |
| 20/04/2026 | 1.1     | Adição da parte interessada para tratar o domínio de negócio | Prof Bezerra |
| 26/04/2026 | 1.2     | Definição das funcionalidades e arquietura proposta            | Prof Bezerra |

## 1. Objetivo

<img src="image/Visao-demanda/1776555009224.png" alt="1776555009224" width="20%">

Definir a proposta de valor e o escopo do Sistema de Gestão das Feiras Livres de Fortaleza, detalhando as necessidades da Secretaria Municipal, dos [feirantes](./Glossario.md) e dos fiscais.

## 2. Proposta de Valor

O sistema permitirá modernizar e digitalizar o controle das feiras livres municipais, facilitando o cadastro de feirantes, organização das barracas, controle de taxas e fiscalização. Espera-se maior transparência, agilidade administrativa e redução de erros e fraudes.

## 3. Descrição da Demanda

O sistema apoiará a Secretaria na **organização das feiras:**

* cadastro e controle de [feirantes](./Glossario.md#feirante);
* registro de [barracas](./Glossario.md#barraca);
* cadastro de tipos de produtos;
* pagamento de taxas;
* geração de relatórios;
* e consulta por fiscais.

Todo o processo será digital, com autenticação de usuários e histórico de alterações.

Permitirá também o cidadão consultar as feiras livres de Fortaleza, bem como o cadastro de feirantes e produtos.

Não está no escopo dessa demanda a venda de produtos.

## 4. Partes Interessadas

| Nome                                    | Papel                 | Responsabilidades                                       | Representante   |
| --------------------------------------- | --------------------- | ------------------------------------------------------- | --------------- |
| Secretaria Municipal                    | Cliente               | Gerenciar feiras, aprovar cadastros, emitir licenças   | Liliane Mdeiros |
| Feirante                                | Usuário final        | Solicitar licença, pagar taxas, participar das feiras  | Humberto        |
| Fiscal Municipal                        | Stakeholder           | Consultar feirantes autorizados, fiscalizar barracas    | José Silva     |
| Equipe de TI                            | Desenvolvimento       | Implementar e manter o sistema                          | Equipe Lapis    |
| Cidadão                                | Comprador             | Cidadão que vai a feira livre para comprar mercadorias | Joana Darc      |
| Setor Jurídico da Secretaria Municipal | Consultor de Negócio | Verificar a legislação sobre feiras livres            | Raimundo Nonato |

## 5. Personas

### 5.1. Feirante

- **Descrição:** Trabalhador autônomo que comercializa produtos nas feiras municipais.
- **Objetivo:** Conseguir licença, pagar taxas e participar das feiras de forma regularizada.

### 5.2. Fiscal Municipal

- **Descrição:** Servidor responsável por fiscalizar o funcionamento das feiras e a regularidade dos feirantes.
- **Objetivo:** Consultar rapidamente a lista de feirantes autorizados e registrar ocorrências.

### 5.3. Gestor da Secretaria Municipal

- **Descrição:** Servidor responsável por gerenciar feiras, aprovar cadastros, emitir licenças.
- **Objetivo:** Realizar os cadastros básicos do sistema e fazer as aprovações dos Cadastros.

### 5.4. Cidadão

- **Descrição:** Contribuinte que busca onde encontrar as feiras livres, feirantes e produtos.
- **Objetivo:** Consultar rapidamente a lista de feiras, feirantes e produtos.

## 6. Necessidades e Funcionalidades

### Necessidade 1: Gerenciar cadastro de feirantes

#### F1.1 Cadastro de feirante

* **Descrição:** Permite cadastrar feirantes com dados pessoais, tipo de produto e informações da barraca.
* **Incluída**
* **Atores:** Gestor da Secretaria
* **Frequência:** Alta
* **Valor:** Alto

#### F1.2 Atualizar cadastro de feirante

* **Descrição:** Permite editar informações cadastrais dos feirantes.
* **Incluída**
* **Atores:** Gestor da Secretaria
* **Frequência:** Alta
* **Valor:** Alto

#### F1.3 Remover/Inativar feirante

* **Descrição:** Permite excluir ou inativar feirantes do sistema.
* **Incluída**
* **Atores:** Gestor da Secretaria
* **Frequência:** Média
* **Valor:** Médio

#### F1.4 Consultar feirantes

* **Descrição:** Permite consultar feirantes cadastrados com filtros.
* **Incluída**
* **Atores:** Fiscal, Gestor
* **Frequência:** Alta
* **Valor:** Alto

#### F1.5 Histórico de alterações

* **Descrição:** Registra alterações realizadas no cadastro de feirantes.
* **Incluída**
* **Atores:** Sistema / Gestor
* **Frequência:** Alta
* **Valor:** Alto

---

### Necessidade 2: Gerenciar feiras livres

#### F2.1 Cadastro de feiras

* **Descrição:** Permite cadastrar feiras com bairro, dia e horário.
* **Incluída**
* **Atores:** Gestor
* **Frequência:** Média
* **Valor:** Alto

#### F2.2 Consultar feiras

* **Descrição:** Permite consultar feiras disponíveis na cidade.
* **Incluída**
* **Atores:** Cidadão, Fiscal
* **Frequência:** Alta
* **Valor:** Alto

#### F2.3 Vincular feirantes à feira

* **Descrição:** Permite associar feirantes autorizados a uma feira específica.
* **Incluída**
* **Atores:** Gestor
* **Frequência:** Alta
* **Valor:** Alto

---

### Necessidade 3: Controle de barracas

#### F3.1 Registro de barraca

* **Descrição:** Permite cadastrar barraca vinculada ao feirante e à feira.
* **Incluída**
* **Atores:** Gestor
* **Frequência:** Alta
* **Valor:** Alto

---

### Necessidade 4: Gestão de licenças

#### F4.1 Solicitar licença (TPU)

* **Descrição:** Permite ao feirante solicitar autorização para atuar em feira.
* **Incluída**
* **Atores:** Feirante
* **Frequência:** Média
* **Valor:** Alto

#### F4.2 Aprovar/Reprovar licença

* **Descrição:** Permite análise e aprovação do cadastro conforme regras da prefeitura.
* **Incluída**
* **Atores:** Gestor
* **Frequência:** Alta
* **Valor:** Alto

#### F4.3 Validar feirante autorizado

* **Descrição:** Permite verificar se o feirante possui licença válida.
* **Incluída**
* **Atores:** Fiscal
* **Frequência:** Alta
* **Valor:** Alto

---

### Necessidade 5: Gestão de taxas

#### F5.1 Registrar pagamento de taxa

* **Descrição:** Permite registrar pagamentos realizados pelos feirantes.
* **Incluída**
* **Atores:** Gestor
* **Frequência:** Alta
* **Valor:** Alto

#### F5.2 Consultar débitos

* **Descrição:** Permite verificar taxas pendentes por feirante.
* **Incluída**
* **Atores:** Gestor, Feirante
* **Frequência:** Alta
* **Valor:** Alto

#### F5.3 Validar pagamento para participação

* **Descrição:** Permite verificar se o feirante está apto a participar da feira.
* **Incluída**
* **Atores:** Sistema / Fiscal
* **Frequência:** Alta
* **Valor:** Alto

---

### Necessidade 6: Fiscalização

#### F6.1 Consultar feirantes autorizados por feira

* **Descrição:** Permite ao fiscal acessar lista de feirantes autorizados.
* **Incluída**
* **Atores:** Fiscal
* **Frequência:** Alta
* **Valor:** Alto

#### F6.2 Registrar ocorrência

* **Descrição:** Permite registrar irregularidades durante fiscalização.
* **Incluída**
* **Atores:** Fiscal
* **Frequência:** Média
* **Valor:** Alto

---

### Necessidade 7: Relatórios

#### F7.1 Relatório de arrecadação

* **Descrição:** Gera relatório mensal das taxas arrecadadas.
* **Incluída**
* **Atores:** Gestor
* **Frequência:** Mensal
* **Valor:** Alto

#### F7.2 Relatório de feirantes ativos

* **Descrição:** Lista feirantes ativos por feira ou período.
* **Incluída**
* **Atores:** Gestor
* **Frequência:** Alta
* **Valor:** Médio

---

### Necessidade 8: Acesso e segurança

#### F8.1 Autenticação de usuários

* **Descrição:** Permite login de usuários da prefeitura.
* **Incluída**
* **Atores:** Gestor, Fiscal
* **Frequência:** Alta
* **Valor:** Alto

#### F8.2 Controle de perfis de acesso

* **Descrição:** Define permissões conforme tipo de usuário.
* **Incluída**
* **Atores:** Sistema
* **Frequência:** Alta
* **Valor:** Alto

---

### Necessidade 9: Consulta pública

#### F9.1 Consultar feiras

* **Descrição:** Permite ao cidadão visualizar feiras disponíveis.
* **Incluída**
* **Atores:** Cidadão
* **Frequência:** Alta
* **Valor:** Médio

#### F9.2 Consultar feirantes e produtos

* **Descrição:** Permite visualizar feirantes e produtos comercializados.
* **Incluída**
* **Atores:** Cidadão
* **Frequência:** Média
* **Valor:** Médio

---

## 7. Arquitetura da Demanda

### Descrição da Arquitetura

O sistema será uma aplicação web composta por três camadas principais:

#### 1. Frontend (Interface Web)

* Acesso via navegador
* Interfaces para:
* Gestor da Secretaria
* Fiscal
* Feirante (opcional futuro)
* Cidadão (consulta pública)

---

#### 2. Backend (API)

Responsável pela lógica de negócio e regras do sistema:

* Módulo de Cadastro de Feirantes
* Módulo de Gestão de Feiras
* Módulo de Licenciamento
* Módulo de Taxas
* Módulo de Fiscalização
* Módulo de Relatórios
* Módulo de Autenticação e Controle de Acesso

---

#### 3. Banco de Dados Relacional

Armazena informações como:

* Feirantes
* Feiras
* Barracas
* Licenças
* Pagamentos
* Usuários
* Histórico de alterações

---

### Integrações

* Possível integração futura com sistemas da prefeitura (ex: licenciamento e arrecadação)
* Uso de API REST para comunicação entre frontend e backend

## Checklist de Validação do Documento de Visão

- [X] O objetivo está claro e alinhado ao problema/necessidade?
- [X] A proposta de valor é mensurável e relevante?
- [X] Todas as partes interessadas estão listadas com papéis definidos?
- [X] Existem pelo menos duas personas descritas?
- [X] Todas as necessidades e funcionalidades estão relacionadas a atores?
- [X] Há indicação de valor e frequência para cada funcionalidade?
- [ ] A arquitetura está ilustrada (mesmo que de forma simples)?
- [ ] O documento está escrito em linguagem clara e objetiva?

---

> Consulte exemplos e dicas em: [Guia de Elaboração da Visão](../../../Elicitacao/VisaoDemanda.md)
