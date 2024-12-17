## 3. Tabelas e Códigos Utilizados no Faturamento

Nesta seção, serão apresentadas as principais **tabelas e códigos** utilizados no **processo de faturamento** do Sistema Único de Saúde (SUS). O correto entendimento e utilização desses instrumentos são fundamentais para garantir a **precisão e qualidade** das informações registradas, bem como para viabilizar o **pagamento adequado** dos serviços prestados.

As tabelas e códigos desempenham um papel essencial no **registro, processamento e validação** das informações de produção ambulatorial e hospitalar. Elas permitem a padronização dos procedimentos, medicamentos, órteses, próteses e materiais especiais, garantindo que os serviços realizados sejam registrados de forma **uniforme e transparente** em todo o território nacional.

### 3.1 Tabela SIGTAP

---------------IMAGEM SIGTAP-----------------------

O **Sistema de Gerenciamento da Tabela de Procedimentos, Medicamentos, Órteses, Próteses e Materiais Especiais do SUS (SIGTAP)** é um ambiente virtual que permite a **consulta da Tabela de Procedimentos, Medicamentos e OPM** do SUS. Gerenciado pela **CGSI/DRAC/SAS/MS**, o SIGTAP disponibiliza a tabela com todos os seus atributos para os estabelecimentos de saúde credenciados ao SUS.

A **instituição da Tabela de Procedimentos** foi publicada pela **Portaria GM nº 321, de fevereiro de 2007**, e regulamentada pela **Portaria GM nº 2848, de novembro de 2007**, estando atualmente sob a **Portaria de Consolidação nº 1, de 28 de setembro de 2017**. Este instrumento de gestão possibilita:

- **Acesso à Tabela de Procedimentos**;
- **Acompanhamento das alterações** realizadas a cada competência;
- **Detalhamento das características** dos procedimentos, incluindo compatibilidades e relacionamentos.

#### Características dos Procedimentos no SIGTAP

O SIGTAP fornece informações detalhadas sobre cada procedimento, tais como:

- **Tipo de financiamento**;
- **Instrumento de registro**;
- **Valor**;
- **CBO** (Classificação Brasileira de Ocupações);
- **CID** (Classificação Internacional de Doenças);
- **Serviço/classificação**;
- **Habilitações**;
- **Incrementos financeiros**;
- **Complexidade**.

#### Estrutura da Tabela SIGTAP

A **Tabela de Procedimentos do SUS** é organizada em uma estrutura hierárquica, permitindo a consulta dos procedimentos conforme os seguintes elementos:

- **Grupos**;
- **Subgrupos**;
- **Forma de Organização**;
- **Origem**;
- **Documento de publicação**;
- **Competência**.

De acordo com o **DATASUS**:

1. O **Grupo** agrega os **procedimentos, medicamentos e OPMs** conforme a **área de atuação** e a **finalidade** das atividades realizadas.
2. O **Subgrupo** organiza os itens com base no **tipo da área de atuação**.
3. A **Forma de Organização** considera aspectos como **especialidade, tipos de OPM, tipos de exames e tipos de cirurgias**.

Cada procedimento é identificado por um **código específico**, em que:

- Os últimos dígitos correspondem aos **números sequenciais** na forma de organização.
- O **último dígito** representa o **dígito verificador**.

#### Importância do SIGTAP

O SIGTAP é uma ferramenta essencial para o **faturamento do SUS** e para a **auditoria em saúde**, pois traz todas as informações necessárias para o registro padronizado dos procedimentos. Ele organiza e facilita a identificação correta dos itens, garantindo a **transparência**, a **qualidade dos registros** e a **gestão eficiente** dos serviços prestados.

Portanto, ao buscar um procedimento, medicamento ou OPM, o SIGTAP organiza as informações conforme o **grupo, subgrupo e forma de organização**, permitindo uma consulta **precisa e estruturada**.

Veja o exemplo ao buscar o Tratamento de Diabetes Mellitus na tabela: 

--------------IMAGEM DIABETE MELITUS---------------------

Confira a codificação na imagem a seguir:

--------------IMAGEM CODIFICAÇÃO DIABETE MELITUS---------------------

#### Acesso e Funcionalidades do SIGTAP

O sistema **SIGTAP** está disponível em duas versões:

- **Versão Web**: Acessada diretamente pela internet.
- **Versão Desktop**: Disponível para **download**, permitindo o uso sem conexão com a rede.

Para acessar a **versão online**, visite o [site do SIGTAP no DATASUS](http://sigtap.datasus.gov.br) e clique em **“Acessar Tabela Unificada”**.

Para baixar a **versão Desktop**, acesse o mesmo endereço eletrônico e clique em **“Download”** no menu superior direito.

#### Funcionalidades da Tabela SIGTAP

A **Tabela do Sistema de Gerenciamento da Tabela de Procedimentos, Medicamentos, Órteses, Próteses e Materiais Especiais do SUS (SIGTAP)** é uma ferramenta que permite:

- **Acessar** a tabela de procedimentos do SUS;
- **Acompanhar** as alterações realizadas em cada recurso;
- **Detalhar** as características, compatibilidade e relação dos procedimentos;
- **Gerar relatórios**;
- **Obter Notas Técnicas** mensais;
- **Importar** a versão da Tabela de Procedimentos para os sistemas de captação e processamento.

Porém, uma questão relevante da tabela é a **defasagem dos valores praticados**, que **não são reajustados há mais de 15 anos**.

No contexto do **faturamento**, além de fornecer dados relativos a cada procedimento, o SIGTAP permite:

- Realizar estudos de **impacto financeiro** decorrentes da unificação das tabelas **SIA e SIH**;
- Gerar **relatórios variados**, adaptados às necessidades do usuário.

#### Características Estruturais dos Procedimentos no SIGTAP

Os procedimentos registrados no SIGTAP possuem uma estrutura padronizada, composta pelos seguintes elementos:

**Código**

O **identificador numérico** de **10 dígitos** é gerado a partir da estrutura da tabela de procedimentos, obedecendo o formato: **GR.SB.FO.PPP.D**.

- **GR**: Grupo a que pertence o procedimento;
- **SB**: Subgrupo do procedimento no grupo onde está inserido;
- **FO**: Forma de Organização no subgrupo;
- **PPP**: Ordem sequencial do procedimento na Forma de Organização;
- **D**: Dígito verificador (calculado pelo **Módulo 11**).

**Nome**
Denominação do procedimento.

**Descrição**
Definição ou detalhamento das características e orientações de uso do procedimento.

**Vigência**
Indica a **competência/mês** de **validade inicial** e **final** do procedimento.

**Código de Origem**
Identifica os códigos que deram origem aos procedimentos registrados na tabela SIGTAP. Pode ser dividido em:

- **Origem SIA e SIH**: Procedimentos que deram origem à **Tabela Unificada** instituída em **janeiro/2008**.
- **Origem SIGTAP**: Códigos de 10 dígitos que originam novos procedimentos na tabela SIGTAP.

**Modalidade de Atendimento**

Especifica o **regime de atendimento** no qual o procedimento pode ser realizado. 

As modalidades de atendimento no SIGTAP incluem **códigos, nomes** e suas respectivas **vigências inicial e final**.



| **Código** | **Nome**                   | **Vigência inicial** | **Vigência final** |
|------------|---------------------------|----------------------|--------------------|
| 1          | Ambulatorial              | jan/08               | -                  |
| 2          | Hospitalar                | jan/08               | -                  |
| 3          | Hospital Dia              | jan/08               | -                  |
| 4          | Internação Domiciliar     | jan/08               | jun/12             |
| 5          | Assistência Domiciliar    | jan/08               | mar/12             |
| 6          | Atenção Domiciliar        | abr/12               | -                  |

