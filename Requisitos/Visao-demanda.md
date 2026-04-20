# Visão da Demanda (VD)

## Histórico de Versões

| Data       | Versão | Descrição                                                      | Autor        |
| ---------- | ------- | ---------------------------------------------------------------- | ------------ |
| 18/04/2026 | 1.0     | Criação do documento de visão e adição do log               | Prof Bezerra |
| 20/04/2026 | 1.1     | Adição da parte interessada para tratar o domínio de negócio | Prof Bezerra |
|            |         |                                                                  |              |

## 1. Objetivo

<img src="image/Visao-demanda/1776555009224.png" alt="1776555009224" width="20%">

Definir a proposta de valor e o escopo do Sistema de Gestão das Feiras Livres de Fortaleza, detalhando as necessidades da Secretaria Municipal, dos [feirantes](./Glossario.md) e dos fiscais.

## 2. Proposta de Valor

O sistema permitirá modernizar e digitalizar o controle das feiras livres municipais, facilitando o cadastro de feirantes, organização das barracas, controle de taxas e fiscalização. Espera-se maior transparência, agilidade administrativa e redução de erros e fraudes.

## 3. Descrição da Demanda

O sistema apoiará a Secretaria na organização das feiras, cadastro e controle de [feirantes](./Glossario.md#feirante), registro de [barracas](./Glossario.md#barraca), pagamento de taxas, geração de relatórios e consulta por fiscais. Todo o processo será digital, com autenticação de usuários e histórico de alterações.

Permitirá também o cidadão consultar as feiras livres de Fortaleza, bem como o cadastro de feirantes e produtos.

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

- **Descrição:** Servidor responsável por gerenciar feiras, aprovar cadastros, emitir licençass.
- **Objetivo:** Realizar os cadastro básicos do sistema e fazer as aprovações do Cadastro.

### 5.4. Cidadão

- **Descrição:** Contribuinte que busca onde encontrar as feiras livres, feirantes e produtos.
- **Objetivo:** Consultar rapidamente a lista de feiras, feirantes e produtos..

## 6. Necessidades e Funcionalidades

Relacione as necessidades e funcionalidades, detalhando para cada uma os atores, frequência e valor.

**Exemplo:**

### Necessidade 1: Solicitar estágio

#### F1.1 Cadastro de solicitação de estágio

- **Descrição:** Permite ao aluno cadastrar uma nova solicitação de estágio.
- **Incluída**
- **Atores:** Aluno
- **Frequência:** Alta
- **Valor:** Alto

### Necessidade 2: Aprovar relatório

#### F2.1 Aprovação de relatório de estágio

- **Descrição:** Permite ao professor aprovar ou rejeitar relatórios enviados.
- **Incluída**
- **Atores:** Professor Orientador
- **Frequência:** Média
- **Valor:** Alto

## 7. Arquitetura da Demanda

Inclua um diagrama simples (pode ser desenhado à mão e digitalizado, ou feito em ferramenta online) mostrando os principais componentes e integrações.

**Exemplo:**

> O sistema será composto por três módulos principais: Portal do Aluno, Portal do Professor e Módulo Administrativo. Integração com sistema acadêmico via API REST.

Sugestão: utilize mapas de histórias ou diagramas de caso de uso (UML) para ilustrar.

---

## Checklist de Validação do Documento de Visão

- [X] O objetivo está claro e alinhado ao problema/necessidade?
- [X] A proposta de valor é mensurável e relevante?
- [X] Todas as partes interessadas estão listadas com papéis definidos?
- [X] Existem pelo menos duas personas descritas?
- [ ] Todas as necessidades e funcionalidades estão relacionadas a atores?
- [ ] Há indicação de valor e frequência para cada funcionalidade?
- [ ] A arquitetura está ilustrada (mesmo que de forma simples)?
- [ ] O documento está escrito em linguagem clara e objetiva?

---

> Consulte exemplos e dicas em: [Guia de Elaboração da Visão](../../../Elicitacao/VisaoDemanda.md)
