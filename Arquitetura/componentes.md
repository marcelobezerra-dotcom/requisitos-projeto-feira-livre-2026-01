# Arquitetura de Componentes - Sistema de Gestão de Feiras Livres

## Diagrama em Mermaid

```mermaid
flowchart TB

%% =======================
%% FRONTEND
%% =======================
subgraph Frontend
    PortalGestor["Portal Gestor"]
    InterfaceFiscal["Interface Fiscal"]
    PortalCidadao["Portal Cidadão"]
    AppFeirante["App Feirante (Futuro)"]
end

%% =======================
%% BACKEND
%% =======================
subgraph Backend
    APIRest["API REST"]

    subgraph Modulos
        ModAutenticacao["Autenticação"]
        ModFeirantes["Feirantes"]
        ModFeiras["Feiras"]
        ModBarracas["Barracas"]
        ModLicencas["Licenças/TPU"]
        ModTaxas["Taxas"]
        ModFiscalizacao["Fiscalização"]
        ModRelatorios["Relatórios"]
    end
end

%% =======================
%% DATABASE
%% =======================
subgraph Database
    BD["Banco de Dados Relacional"]

    subgraph Tabelas
        TblFeirantes["Feirantes"]
        TblFeiras["Feiras"]
        TblBarracas["Barracas"]
        TblLicencas["Licenças"]
        TblPagamentos["Pagamentos"]
        TblUsuarios["Usuários"]
        TblHistorico["Histórico"]
    end
end

%% =======================
%% EXTERNAL
%% =======================
subgraph External
    SistemasPrefeitura["Sistemas Prefeitura"]
    PortalSPU["Portal SPU Digital"]
end

%% =======================
%% CONEXÕES
%% =======================
PortalGestor -->|HTTP/HTTPS| APIRest
InterfaceFiscal -->|HTTP/HTTPS| APIRest
PortalCidadao -->|HTTP/HTTPS| APIRest
AppFeirante -->|HTTP/HTTPS| APIRest

APIRest --> ModAutenticacao
APIRest --> ModFeirantes
APIRest --> ModFeiras
APIRest --> ModBarracas
APIRest --> ModLicencas
APIRest --> ModTaxas
APIRest --> ModFiscalizacao
APIRest --> ModRelatorios

APIRest -->|SQL| BD

BD --> TblFeirantes
BD --> TblFeiras
BD --> TblBarracas
BD --> TblLicencas
BD --> TblPagamentos
BD --> TblUsuarios
BD --> TblHistorico

APIRest -.->|Futuro| SistemasPrefeitura
APIRest -.->|Futuro| PortalSPU
```

## Descrição da Arquitetura

### Camada de Apresentação (Frontend)

- **Portal Gestor**: Gestão completa das feiras, feirantes e licenças
- **Interface Fiscal**: Consultas e fiscalização em campo
- **Portal Cidadão**: Consulta pública de feiras e feirantes
- **App Feirante**: Futura aplicação para feirantes acompanharem suas licenças

### Camada de Negócio (Backend)

Uma **API REST** organizada em **8 módulos** principais:

1. **Autenticação**: Segurança e controle de acesso
2. **Feirantes**: Gestão de cadastros e dados pessoais
3. **Feiras**: Gestão de feiras por bairro e horário
4. **Barracas**: Registro e alocação de barracas
5. **Licenças/TPU**: Solicitação e aprovação de autorizações
6. **Taxas**: Controle de pagamentos e débitos
7. **Fiscalização**: Ferramentas para fiscais
8. **Relatórios**: Geração de relatórios administrativos

### Camada de Persistência (Banco de Dados)

Banco de dados relacional com **7 tabelas principais**:

- Feirantes, Feiras, Barracas, Licenças, Pagamentos, Usuários, Histórico

### Integrações Futuras

- Sistemas da Prefeitura de Fortaleza
- Portal SPU Digital para gestão de patrimônio público
