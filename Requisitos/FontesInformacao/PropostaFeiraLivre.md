# Contexto do Projeto

A **Prefeitura de Fortaleza** pretende modernizar o processo de gestão das  **feiras livres municipais** , que ocorrem semanalmente em diversos bairros da cidade.

Atualmente, o controle de feirantes, a organização das barracas, a autorização de funcionamento e o pagamento de taxas são realizados de forma manual ou em planilhas, o que dificulta o controle administrativo e a fiscalização.

Para melhorar a gestão dessas atividades, a prefeitura pretende contratar uma empresa de software para desenvolver um  **Sistema de Gestão das Feiras Livres de Fortaleza** .

Esse sistema deverá apoiar a Secretaria responsável na organização das feiras, cadastro de feirantes, controle das barracas, pagamento de taxas e geração de relatórios administrativos.

A seguir apresenta-se um  **trecho da solicitação enviada a empresas de software para elaboração de proposta técnica e orçamentária** .

---

# Solicitação de Desenvolvimento de Sistema

Prezada empresa,

A Prefeitura de Fortaleza solicita uma proposta para desenvolvimento de um  **Sistema de Gestão das Feiras Livres Municipais** , que permita melhorar o controle administrativo e apoiar o trabalho dos fiscais municipais.

Durante reuniões iniciais foram identificadas as seguintes necessidades e condições do sistema:

1. O sistema deve permitir o  **cadastro de feirantes** , contendo nome, CPF, tipo de produto vendido e telefone.
2. O sistema deve permitir o  **registro das feiras realizadas em cada bairro da cidade** .
3. O sistema deve permitir que  **fiscais consultem a lista de feirantes autorizados em uma feira específica** .
4. O sistema deve permitir o  **registro do pagamento das taxas municipais associadas aos feirantes** .
5. O sistema deverá  **gerar relatórios mensais de arrecadação das taxas das feiras** .
6. O sistema deverá permitir que  **administradores atualizem ou removam o cadastro de feirantes** .
7. O sistema deverá  **funcionar em navegadores web modernos** .
8. O tempo de resposta das consultas  **não deve ultrapassar 3 segundos** .
9. O sistema deverá  **garantir autenticação de usuários da prefeitura para acesso às funcionalidades administrativas** .
10. O sistema deverá  **registrar histórico de alterações nos cadastros de feirantes** .
11. O sistema deverá ser desenvolvido  **utilizando banco de dados relacional** .
12. O prazo máximo estimado para desenvolvimento do sistema é de  **6 meses após a contratação** .
13. Considera-se que a  **Prefeitura de Fortaleza já possui servidores disponíveis para hospedagem do sistema** .
14. Apenas  **feirantes com licença válida emitida pela prefeitura poderão participar das feiras** .
15. Cada  **feirante poderá possuir apenas uma barraca registrada por feira** .
16. As  **taxas cobradas dos feirantes seguem os valores definidos pela legislação municipal vigente** .
17. As feiras livres ocorrem  **em dias e horários definidos pela Secretaria Municipal responsável** .
18. O sistema deverá  **estar em conformidade com a legislação municipal que regulamenta o funcionamento das feiras livres** .


# Situação Atual

Para desenvolver um sistema de cadastro de feiras em Fortaleza, é fundamental entender que, atualmente, o processo ainda é predominantemente presencial e descentralizado, ocorrendo nas sedes das Secretarias Executivas Regionais ou em centrais de atendimento específicas.

Aqui está o fluxo atual de como o cadastro é realizado:

## 1. Onde ocorre o cadastro

* Secretarias Regionais: Cada feirante deve procurar a Regional responsável pelo bairro onde a feira está instalada.
* Central de Acolhimento: O atendimento inicial geralmente ocorre na Central de Acolhimento da Secretaria Regional escolhida.
* SDE (Secretaria do Desenvolvimento Econômico): Para programas específicos como as "Feiras de Pequenos Negócios" (artesanato e economia criativa), o contato inicial pode ser feito pelo telefone 0800 081 4141. [1, 2, 3, 4, 5, 6]

## 2. Documentação e Requisitos (Fluxo de Entrada de Dados)

Para o seu sistema, esses seriam os campos obrigatórios de cadastro:

* Dados Pessoais: RG, CPF e comprovante de residência atualizado.
* Dados do Negócio: Tipo de produto comercializado (setorização) e amostra do produto (para artesãos).
* Equipamento: Foto e medidas exatas da barraca/equipamento para garantir a padronização.
* Localização: Indicação do local exato (rua/ponto de referência) e horários de funcionamento pretendidos.
* Substitutos: Em muitos editais, é permitido cadastrar até dois substitutos (apresentando RG e CPF destes). [3, 4, 5, 7, 8, 9, 10]

## 3. O Processo de Aprovação

1. Abertura de Processo: O feirante preenche um formulário físico e entrega as cópias dos documentos.
2. Análise Técnica: O processo é encaminhado para a Célula de Gestão de Serviços Urbanos para verificar a disponibilidade de vagas e se o local não obstrui a acessibilidade.
3. Termo de Permissão de Uso (TPU): Caso aprovado, o feirante recebe o termo que oficializa sua atividade. [3, 10, 11, 12]

## 4. Digitalização Existente (Referências para o seu sistema)

Embora o cadastro de feirantes de rua ainda seja físico, você pode se basear em plataformas digitais da prefeitura que já funcionam para outros serviços:

* [Fortaleza Online (SEUMA)](https://portal.seuma.fortaleza.ce.gov.br/fortalezaonline/portal/agendamento.jsf): Usado para licenciamentos ambientais e alvarás de funcionamento.
* SPU Digital: Sistema para gestão de patrimônio e uso do espaço público. [13, 14, 15]

Oportunidade para o seu sistema: Hoje falta uma interface unificada onde o feirante possa anexar documentos digitalmente (PDF/Fotos) e acompanhar o status da sua "vaga" em tempo real sem precisar ir à Regional.

Você pretende focar o sistema na gestão da prefeitura (back-office) ou em um aplicativo para o feirante acompanhar a licença?

[1] [https://www.fortaleza.ce.gov.br](https://www.fortaleza.ce.gov.br/noticias/regional-v-cadastra-permissionarios-de-feiras-livres)

[2] [https://www.fortaleza.ce.gov.br](https://www.fortaleza.ce.gov.br/noticias/prefeitura-cadastra-feirantes-interessados-em-trabalhar-na-praca-do-iprede)

[3] [https://www.vilavelhafortaleza.com.br](https://www.vilavelhafortaleza.com.br/2023/06/como-tornar-permissionario-pracas-fortaleza.html)

[4] [https://www.fortaleza.ce.gov.br](https://www.fortaleza.ce.gov.br/noticias/prefeitura-recadastra-os-feirantes-do-planalto-ayrton-senna-e-santa-cecilia)

[5] [https://www.cmfor.ce.gov.br](https://www.cmfor.ce.gov.br/comunicacao/noticias/saiba-como-expor-seus-produtos-nas-feiras-de-pequenos-negocios)

[6] [https://www.cmfor.ce.gov.br](https://www.cmfor.ce.gov.br/comunicacao/noticias/saiba-como-expor-seus-produtos-nas-feiras-de-pequenos-negocios)

[7] [https://g1.globo.com](https://g1.globo.com/ce/ceara/noticia/2026/01/13/carnaval-2026-em-fortaleza-inscricoes-para-ambulantes-estao-abertas-veja-como-se-inscrever.ghtml)

[8] [https://g1.globo.com](https://g1.globo.com/ce/ceara/noticia/2026/01/13/carnaval-2026-em-fortaleza-inscricoes-para-ambulantes-estao-abertas-veja-como-se-inscrever.ghtml)

[9] [https://www.cmfor.ce.gov.br](https://www.cmfor.ce.gov.br/comunicacao/noticias/saiba-como-expor-seus-produtos-nas-feiras-de-pequenos-negocios)

[10] [https://www.vilavelhafortaleza.com.br](https://www.vilavelhafortaleza.com.br/2023/06/como-tornar-permissionario-pracas-fortaleza.html)

[11] [https://www.fortaleza.ce.gov.br](https://www.fortaleza.ce.gov.br/noticias/prefeitura-de-fortaleza-entrega-mais-de-200-termos-de-permissao-para-a-feira-do-palmares)

[12] [https://www.fortaleza.ce.gov.br](https://www.fortaleza.ce.gov.br/noticias/secretaria-executiva-regional-1-entrega-30-permissoes-para-feirantes-do-vila-velha-nesta-terca-feira-29-08)

[13] [https://portal.seuma.fortaleza.ce.gov.br](https://portal.seuma.fortaleza.ce.gov.br/fortalezaonline/portal/agendamento.jsf)

[14] [https://hom-portal.seuma.fortaleza.ce.gov.br](https://hom-portal.seuma.fortaleza.ce.gov.br/fortalezaonline/portal/checklist/CHECKLIST_AUTORIZACAO_DE_EVENTO_ONLINE_02_12_2020.pdf)

[15] [https://planejamento.fortaleza.ce.gov.br](https://planejamento.fortaleza.ce.gov.br/images/PDF/2025/MANUAL_SPU_DIGITAL.pdf#:~:text=O%20acesso%20ao%20SPU%20Digital%20Cidad%C3%A3o%20pode,com%20seu%20CPF%20e%20senha%20j%C3%A1%20cadastrados.)
