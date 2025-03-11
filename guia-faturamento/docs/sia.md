![Image](./imagens/logo.png)
# Sistema de Informação Ambulatorial do SUS (SIA/SUS)

O **Sistema de Informação Ambulatorial (SIA)** surgiu da necessidade do **Ministério da Saúde** de criar um sistema de informação que permitisse o **registro padronizado** dos atendimentos ambulatoriais em **nível nacional**. O objetivo principal era gerar informações que facilitassem o **planejamento, controle, avaliação e auditoria** dos serviços prestados, principalmente com a **descentralização da gestão** do Sistema Único de Saúde (SUS).

O **SIA** foi implantado em **1995** em todo o território nacional. Inicialmente, entrou em funcionamento com o **Boletim de Produção Ambulatorial Consolidado (BPA-C)**, que registrava apenas o procedimento realizado e a quantidade, sem a identificação do paciente.

Em **1996**, foi instituída a **Autorização de Procedimentos Ambulatoriais de Alta Complexidade/Custo (APAC)**. Esse novo instrumento do SIA foi criado para contemplar os procedimentos ambulatoriais de **alta complexidade/custo**, incluindo informações detalhadas como:

- **Identificação do usuário atendido**;
- **Identificação do profissional executante**;
- **Diagnóstico do paciente**.

Com a instituição da **Tabela de Procedimentos, Medicamentos, Órteses/Próteses e Materiais Especiais (OPM) do SUS**, pela **Portaria GM/MS nº 321, de 8 de fevereiro de 2007**, as tabelas de procedimentos do **SIA** e do **SIH** foram **unificadas**.

O **SIA** é o sistema responsável por **gerir informações ambulatoriais do SUS** e subsidiar os gestores estaduais e municipais nos processos de:

- **Planejamento**;
- **Programação**;
- **Regulação**;
- **Avaliação**;
- **Controle**;
- **Auditoria** dos serviços de saúde.

As **principais finalidades** do SIA incluem:

- Registrar os atendimentos ambulatoriais do SUS de forma **padronizada**;
- Gerar dados e informações **estratégicas** para a gestão da saúde;
- Auxiliar no **planejamento, controle, avaliação e auditoria**;
- Viabilizar o **faturamento ambulatorial** dos serviços prestados.

O **SIA** permite o processamento das informações de atendimentos registrados nos **aplicativos de captação** utilizados pelos **prestadores públicos e privados contratados/conveniados pelo SUS**:
  
    
#### Componentes do SIA/SUS

Os componentes do sistema envolvem **sistemas de base**, **aplicativos de captação**, **aplicativos intermediários** e **tabelas**:

1. **Sistemas de Base**:
   - **Cadastro Nacional dos Estabelecimentos de Saúde (CNES)**;
   - **Sistema de Gerenciamento da Tabela de Procedimentos do SUS (SIGTAP)**.

2. **Aplicativos de Captação**:
   - **Boletim de Produção Ambulatorial (BPA)**:
     - **BPA-C** (Consolidado): Registra apenas a quantidade de procedimentos, sem identificação do paciente.
     - **BPA-I** (Individualizado): Registra informações detalhadas, incluindo a identificação do paciente.
   - **Autorização de Procedimentos Ambulatoriais (APAC)**:
     - Utilizada para registrar procedimentos de **alta complexidade** (AC) e alguns de **média complexidade** (MC), que exigem **autorização prévia** do gestor local.
   - **Registro de Ações Ambulatoriais de Saúde (RAAS)**:
     - Utilizado para registrar **procedimentos de atenção psicossocial**, financiados por meio de incentivos da **Rede de Atenção Psicossocial (RAPS)**.

3. **Aplicativos Intermediários**:
   - **Ficha de Programação Orçamentária (FPO)**:
     - Permite o registro da **programação física-orçamentária** dos estabelecimentos de saúde, coerente com o planejamento anual e contratos SUS.
   - **Transmissor**:
     - Facilita o **envio dos arquivos** do banco de dados local para o **Banco de Dados Nacional**, garantindo a integração das informações.

4. **Tabelas**:
   - **Banco de Dados do Sistema de Informação Ambulatorial (BDSIA)**:
     - Contém todos os **procedimentos, atributos e regras** vigentes na competência de processamento, conforme definidos no **SIGTAP**.
     - Disponibilizado mensalmente para **download** no portal do SIA, garantindo a **atualização** dos sistemas.

O **SIA/SUS** é, portanto, um **instrumento essencial** para a gestão da produção ambulatorial do SUS, contribuindo para a melhoria da qualidade das informações e para a otimização dos processos de planejamento e controle dos serviços de saúde.

#### Boletim de Produção Ambulatorial (BPA)

O **Boletim de Produção Ambulatorial (BPA)** é um instrumento utilizado para **registrar os atendimentos ambulatoriais** que **não exigem autorização prévia** do gestor. O registro pode ser feito de duas formas:

1. **BPA-C (Consolidado)**: Não especifica o paciente atendido, registrando apenas a quantidade de procedimentos realizados.
2. **BPA-I (Individualizado)**: Identifica o paciente atendido e inclui informações detalhadas sobre os procedimentos realizados.

A **Tabela de Procedimentos, Órteses, Próteses e Materiais Especiais do SUS** define qual tipo de registro deve ser utilizado para cada procedimento. 

É importante destacar que **todos os procedimentos registrados no BPA-C também podem ser registrados no BPA-I**. Recomenda-se que as unidades de saúde utilizem preferencialmente o **BPA-I**, pois ele garante **maior qualidade das informações** e permite a identificação individualizada dos atendimentos.

Substituição pelo CMD

O **BPA** será gradualmente substituído pelo **Conjunto Mínimo de Dados da Atenção à Saúde (CMD)**, um sistema no qual **todos os atendimentos precisarão ser registrados individualmente**. A implantação do CMD será incremental e substituirá um total de **nove sistemas de informação atualmente utilizados**, que são:

1. **Boletim de Produção Ambulatorial (BPA)**;
2. **Autorização de Procedimento Ambulatorial (APAC)**;
3. **Registro das Ações Ambulatoriais de Saúde (RAAS)**;
4. **Autorização de Internação Hospitalar (SISAIH01)**;
5. **Coleta da Comunicação de Informação Hospitalar e Ambulatorial (CIHA01)**;
6. **Sistema de Informação Ambulatorial (SIA)**;
7. **Sistema de Informação Hospitalar (SIH)**;
8. **Processamento da Comunicação de Informação Hospitalar e Ambulatorial (CIHA02)**;
9. **Sistema de Regulação, Controle e Avaliação (SISRCA)**.

O processo de substituição visa a **unificação e individualização dos registros**, promovendo maior **precisão e qualidade das informações** no **SUS**.

# Faturamento Ambulatorial
## **Fluxo dos atendimentos ambulatoriais eletivos do SUS:**  

•   Atendimento na Atenção Básica: O paciente busca atendimento em uma Unidade Básica de Saúde (UBS) ou outro serviço de atenção primária.  
•   Avaliação Médica: O profissional de saúde verifica a necessidade de encaminhamento para uma especialidade.  
•   Encaminhamento: Caso necessário, é emitido um encaminhamento para consulta em unidade especializada.  
•   Regulação e Agendamento: O encaminhamento passa pela regulação (geralmente via Sistema de Regulação - SISREG), que distribui as vagas conforme critérios de prioridade e disponibilidade.  
•   Consulta Especializada: O paciente é atendido na unidade especializada da FHEMIG ou em outra unidade de referência.  
•   Conduta Pós-Consulta: Dependendo do caso, pode haver retorno à atenção básica com orientações, exames complementares ou até encaminhamento para procedimentos mais complexos.    
  
---
## **Fluxo nas unidades da FHEMIG.**  
Estrutura organizada para garantir um atendimento eficiente e seguro, conforme descrito abaixo:
    1. O paciente chega à unidade da FHEMIG por meio de encaminhamento da atenção primária ou de outra unidade de saúde, ou da própria unidade ou da  FHEMIG.  
    2. Em casos de urgência/emergência, pode ser admitido diretamente pelo Pronto Atendimento.  
    3. Admissão no Guichê de Atendimento: O paciente deve apresentar documentos necessários para sua identificação e registro no sistema (como Cartão SUS, RG e encaminhamento).  
    4. Equipe administrativa: Realiza a triagem administrativa, confirmando dados e registrando o atendimento conforme registros no CADWEB  e  sistema da unidade (Tasy, ou SIGH).  

Encaminhamento para Atendimento: Dependendo da necessidade do paciente, ele pode ser direcionado para:  
•	Consulta Ambulatorial: Se for atendimento eletivo em especialidades médicas.  
•	Pronto Atendimento/Emergência: Caso necessite de assistência imediata.  
•   Atendimento Médico e Registro no Sistema: O paciente é atendido pela equipe multiprofissional e o atendimento é registrado no prontuário eletrônico.  
•   Se necessário, são solicitados exames, procedimentos ou internação.  
•   Alta ou Encaminhamento - O paciente pode receber alta com orientações para continuidade do cuidado.  
•   Caso precise de acompanhamento contínuo, pode ser encaminhado para retorno ambulatorial ou para outra unidade de referência.  
•    Procedimentos que são faturados BPA-C e BPA – Ambulatorial 

---
##	**Procedimentos Ambulatoriais Contratualizados na FHEMIG**  
A FHEMIG possui uma série de procedimentos ambulatoriais contratualizados, organizados por grupo e subgrupo, seguindo as diretrizes do SIGTAP (Sistema de Gerenciamento da Tabela de Procedimentos do SUS). Cada procedimento deve ser registrado corretamente nos Boletins de Produção Ambulatorial (BPA-C e BPA-I) para garantir que as ações executadas sejam corretamente computadas e faturadas.  

---
## **Procedimentos  faturados BPA-C e BPA – Ambulatorial**  
Todos os procedimentos realizados devem ser compatíveis com o SIGTAP, observando as exigências de cadastro no CNES de habilitação serviço e classificação para realizar e seguindo as regras de faturamento, respeitando os atributos de cada procedimento, como quantidade máxima permitida por paciente, requisitos de complexidade do serviço prestado.  
Os Procedimentos individualizados (BPA-I), necessitam de identificação nominal do paciente.  
Os Procedimentos consolidados (BPA-C), são utilizados para registros coletivos sem identificação nominal, quando aplicável.  
No valor dos procedimentos estão incluídos todos os atos, atividades e materiais necessários à realização dos exames, até a entrega dos resultados.  
Para a realização desses procedimentos, a unidade deve observar o cadastro no CNES o Serviço e classificação exigida.  
Para a realização desses procedimentos, a unidade deve observar o cadastro no CNES o Serviço e classificação exigida.  
A seguir serão detalhados os procedimentos ambulatoriais realizados na FHEMIG  

---
## **Procedimentos com Finalidade Diagnóstica Grupo 02**
Os Procedimentos com finalidade diagnóstica pertencem ao Grupo 02 do SIGTAP e abrangem todas as ações realizadas para identificar, confirmar ou monitorar doenças e condições de saúde por meio de exames e testes clínicos. Esses procedimentos incluem a coleta de materiais biológicos, exames laboratoriais, exames de imagem e testes funcionais, sendo fundamentais para o direcionamento terapêutico e a tomada de decisões médicas.  

---
### Principais Categorias dentro dos Procedimentos Diagnósticos
**(Subgrupo 02.01) - Coleta de Material para Diagnóstico**  
Inclui procedimentos para obtenção de amostras biológicas por meio de punção, biópsia ou outros métodos de coleta.  
Exemplos:  
•	Punção aspirativa por agulha fina (PAAF)  
•	Biópsia de pele, mucosa ou órgãos  
•	Punção lombar para coleta de líquor  
•	Coleta de sangue, urina, secreções e tecidos para exames  

---
**(Subgrupo 02.02) - Diagnóstico em Laboratório Clínico**  
Engloba exames laboratoriais para avaliação bioquímica, hematológica, imunológica e microbiológica.  
Exemplos:  
•	Hemograma completo  
•	Testes de função renal e hepática  
•	Sorologias e testes imunológicos  
•	Cultura microbiológica de secreções  

---
**(Subgrupo 02.03) - Diagnóstico por Imagem**  
Compreende exames que utilizam tecnologias de imagem para avaliação interna do organismo.  
Exemplos:  
•	Ultrassonografia  
•	Tomografia Computadorizada  
•	Ressonância Magnética  
•	Radiografia  

---
**Diagnóstico por Anatomia Patológica e Citopatologia**  
Engloba procedimentos voltados para a análise microscópica de células e tecidos com o objetivo de diagnosticar doenças, incluindo lesões pré-malignas e câncer.  
Esses exames são financiados com recursos do MAC (Média e Alta Complexidade) e possuem registro obrigatório nos sistemas de informação do câncer, conforme a patologia avaliada (SISCOLO, SISMAMA e/ou SISCAN), de acordo com o SIGTAP.  
Principais Procedimentos:  
•	Exames Citopatológicos :Os exames citopatológicos analisam células isoladas coletadas por raspado ou aspiração, permitindo a detecção precoce de alterações celulares sugestivas de infecções, inflamações ou câncer.  
•	Exame Citopatológico Cérvico-Vaginal e/ou Microflora:Detecta alterações celulares no colo do útero, incluindo lesões precursoras do câncer.  
•	Utilizado na triagem do câncer de colo uterino (Papanicolau): Inclui análise da microbiota vaginal.  
•	Exame Citopatológico de Mama: Realizado a partir de amostras obtidas por punção aspirativa.  
•	Controle de Qualidade do Exame Citopatológico Cérvico-Vaginal :rocedimento voltado para revisão e conferência da qualidade das análises citológicas.  
•	Citopatológico Cérvico-Vaginal/Microflora : Rastreamento  utilizado especificamente para rastreamento populacional do câncer de colo do útero.  

---
**Exames Anatomopatológicos:**  
Os exames anatomopatológicos analisam amostras de tecidos extraídos por biópsia ou cirurgia, permitindo a identificação precisa de doenças, especialmente neoplasias malignas.  
•	Exame Anatomopatológico do Colo Uterino : Peça CirúrgicaRealizado em tecidos removidos cirurgicamente do colo uterino para diagnóstico definitivo.  
•	Exame Anatomopatológico de Mama : Biópsia, analisa fragmentos de tecido mamário retirados por biópsia para avaliação de lesões suspeitas.  
•	Exame Anatomopatológico de Mama : Peça Cirúrgica , avaliação de tecido mamário removido cirurgicamente para diagnóstico e estadiamento do câncer de mama.  
•	Exame Anatomopatológico do Colo Uterino : Biópsia Realizado em fragmentos de tecido do colo uterino retirados por biópsia, auxiliando no diagnóstico de neoplasias e lesões pré-malignas.  

---
**(Subgrupo 02.04) - Testes Funcionais e Diagnóstico Especializado:**
Inclui exames que avaliam a função fisiológica de órgãos e sistemas.  
Exemplos:  
•	Eletrocardiograma (ECG)  
•	Espirometria (avaliação da função pulmonar)  
•	Endoscopia digestiva e broncoscopia   
•	Polissonografia  

---
**(Subgrupo 02.05) – Diagnóstico por Ultrassonografia:**
Engloba exames de imagem que utilizam ondas sonoras de alta frequência para gerar imagens em tempo real de órgãos e estruturas internas do corpo. Esses exames são fundamentais para avaliação diagnóstica, monitoramento de condições clínicas e orientação de procedimentos invasivos.  
Principais Procedimentos:  
•	Ultrassonografia Geral - Realiza avaliação de órgãos internos para detecção de anomalias estruturais, inflamações e tumores.  
Exemplos:  
•	Ultrassonografia abdominal total – Avaliação do fígado, vesícula, pâncreas, rins, baço e bexiga.  
•	Ultrassonografia pélvica – Investigação de útero, ovários e bexiga.  
•	Ultrassonografia renal – Diagnóstico de cálculos, cistos e anomalias renais.  
•	Ultrassonografia Obstétrica e Ginecológica - Essencial para o pré-natal e para investigação de doenças ginecológicas.  
 Exemplos:  
•	Ultrassonografia obstétrica – Acompanhamento do desenvolvimento fetal.  
•	Ultrassonografia morfológica – Detecção de anomalias fetais.  
•	Ultrassonografia transvaginal – Avaliação detalhada de útero e ovários.  
•	Ultrassonografia Musculoesquelética - Exame utilizado para diagnóstico de lesões musculares, tendíneas e articulares.  

Exemplos:  
•	Ultrassonografia de ombro – Avaliação de tendinites e rupturas do manguito rotador.  
•	Ultrassonografia de joelho – Identificação de derrames articulares e lesões ligamentares.  
•	Ultrassonografia Doppler - Exame que avalia fluxo sanguíneo em artérias e veias, auxiliando no diagnóstico de doenças vasculares.  

Exemplos:  
•	Doppler das artérias carótidas – Investigação de estenoses e risco de AVC.  
•	Doppler venoso de membros inferiores – Detecção de trombose venosa profunda.  

---
**(Subgrupo 02.06) – Diagnóstico por Tomografia Computadorizada (TC):**  
Refere-se aos exames de imagem realizados por meio de tomografia computadorizada (TC), que utiliza radiação ionizante para gerar imagens detalhadas e transversais (cortes) de órgãos e estruturas internas do corpo humano. Esse tipo de exame é fundamental para avaliar condições complexas, como lesões internas, tumores e distúrbios vasculares, além de ser útil no planejamento de tratamentos e monitoramento de doenças.  
Principais Aplicações da Tomografia computadorizada:  
Diagnóstico de Tumores e Lesões.  
•	Exame de escolha para avaliação de tumores cerebrais, pulmonares, abdominais e outros órgãos.  
•	Cortes multiplanares ajudam a detectar neoplasias, identificar tamanho e localização do tumor, além de ajudar a planejar biópsias ou ressecções cirúrgicas.   
•	Avaliação de Doenças Vascularizadas e Hemorragias  
Avaliação de Doenças Cardíacas e Pulmonares  
•	Tomografia Cardíaca: Identificação de calcificação nas artérias coronárias e planejamento de intervenções cardíacas.  
•	Tomografia Pulmonar: Auxilia no diagnóstico de doenças pulmonares, como embolia pulmonar, pneumonia e fibrose pulmonar.  
Diagnóstico de Doenças Abdominais e Pélvicas  
•	Avaliação de útero, ovários, fígado, rins, pâncreas e baço.  
•	Tomografia abdominal é amplamente usada para avaliar cálculos renais, tumores hepáticos e doenças inflamatórias intestinais.  
Traumatismos e Emergências  
•	Fundamental no diagnóstico de traumas cranianos, fracturas e lesões internas em situações de emergência.Permite visualizar hemorragias internas e fraturas complexas, como fraturas da coluna vertebral.  

---
**(Subgrupo 02.07) – Diagnóstico por Ressonância Magnética (RM):**  
refere-se à categoria que abrange a realização de exames de diagnóstico utilizando a tecnologia de Ressonância Magnética (RM) em diferentes contextos clínicos. A RM é um método de imagem altamente detalhado, não invasivo, usado para visualizar órgãos e estruturas internas do corpo humano.  
Esses exames são realizados em clínicas e hospitais que possuem equipamentos especializados e são indicados conforme a necessidade clínica do paciente.  

---
**(Subgrupo 02.09) – Diagnóstico por Endoscopia:**  
Refere-se a exames realizados com o uso de instrumentos chamados endoscópios, que permitem a visualização direta do interior de cavidades e órgãos do corpo humano, com o objetivo de diagnóstico e, em alguns casos, tratamento de condições patológicas. A endoscopia é uma ferramenta valiosa na medicina, principalmente para o diagnóstico precoce de doenças.  
Modalidade: Existem diferentes tipos de endoscopia, dependendo da área do corpo a ser examinada:  
•	Gastroscopia: Para visualizar o esôfago, estômago e duodeno.  
•	Colonoscopia: Para examinar o cólon e reto.  
•	Broncoscopia: Para visualizar as vias aéreas e os pulmões.  
•	Cistoscopia: Para examinar a bexiga urinária.  
•	Artróscopia: Para visualizar articulações.  
•	Laparoscopia: Para visualização da cavidade abdominal.  

---
**(Subgrupo 02.10) – Diagnóstico por Radiologia Intervencionista:**  
Refere-se ao uso de técnicas de imagem, como raios-X, tomografia computadorizada (TC), ultrassonografia e ressonância magnética (RM), para guiar procedimentos minimamente invasivos no diagnóstico e no tratamento de diversas condições médicas. A radiologia intervencionista combina a precisão das imagens com procedimentos terapêuticos, sem a necessidade de grandes cortes ou intervenções cirúrgicas.  
Variedade de Aplicações:  
•	Embolização: Para bloquear o fluxo sanguíneo em áreas específicas, como em casos de hemorragias ou tumores.  
•	Biópsias: Coleta de amostras de tecidos para análise, utilizando agulhas finas guiadas por imagens.  
•	Drenagens: Colocação de drenos em cavidades internas (como abscessos) para drenagem de líquidos.  
•	Angioplastia: Dilatação de vasos sanguíneos estreitados ou bloqueados, usando balões ou stents.  

---
**(Subgrupo 02.11) – Diagnóstico Ginecologia-Obstetrícia:**  
Envolve exames diagnósticos específicos para as áreas de ginecologia e obstetrícia, que são ramos da medicina dedicados à saúde da mulher, incluindo questões relacionadas ao sistema reprodutor feminino e à gestação. Esses exames são essenciais para o monitoramento da saúde das mulheres, tanto em situações clínicas de rotina quanto em condições patológicas.  
As principais características desse subgrupo incluem:  
Exames Ginecológicos de Rotina:  
•	Papanicolau (Pap Smear): Exame de rastreamento para detectar alterações celulares no colo do útero, que podem ser precoces sinais de câncer cervical.  
•	Colposcopia: Exame visual detalhado do colo do útero, vagina e vulva, utilizado para investigar anomalias detectadas no Papanicolau ou para diagnóstico de lesões pré-cancerígenas.  
•	Ultrassonografia Ginecológica: Avaliação dos órgãos pélvicos femininos (útero, ovários, trompas) para detectar cistos, miomas, endometriose, entre outras condições.  
•	Histeroscopia: Exame visual do interior do útero utilizando um endoscópio, utilizado para diagnóstico de problemas como pólipos, miomas e malformações uterinas.
Exames Obstétricos:  
•	Ultrassonografia Obstétrica: Fundamental para o acompanhamento da gestação, incluindo a verificação do desenvolvimento fetal, posição, quantidade de líquido amniótico e outros parâmetros importantes.  
•	Monitoramento Cardiotocográfico (CTG): Utilizado para monitorar os batimentos cardíacos do feto e as contrações uterinas durante a gestação e o trabalho de parto.  
•	Exame de Doppler Obstétrico: Avalia o fluxo sanguíneo nas artérias uterinas e nas veias do feto, ajudando a identificar problemas circulatórios que podem afetar a saúde fetal.  
•	Triagem para Anomalias Genéticas: Exames como o teste de translucência nucal, exames de sangue e amniocentese podem ser realizados para avaliar o risco de anomalias genéticas, como a síndrome de Down, no feto.  
Diagnóstico de Infecções e Outras Condições:  
•	Exame de Culturas: Usado para detectar infecções no trato genital feminino, como vaginoses, infecções por fungos (candidíase), clamídia e gonorreia.  
•	Dosagens Hormonais: Exames laboratoriais para avaliar os níveis de hormônios como progesterona, estrogênio, FSH e LH, úteis para investigação de infertilidade ou distúrbios menstruais.  
•	Avaliação de Distúrbios Menstruais e Endócrinos: Exames para investigar causas de irregularidades menstruais, como ultrassonografia para miomas, pólipos endometriais ou distúrbios hormonais que afetam a função ovariana e uterina.  
•	Assistência à Fertilidade: Exames diagnósticos para investigar a causa da infertilidade feminina, que podem incluir a avaliação do útero (histerosalpingografia) e dos ovários (ultrassonografia, exames hormonais, entre outros).  
•	Exame Pré-Natal: Conjunto de exames realizados para garantir a saúde da gestante e do bebê durante a gravidez, incluindo exames laboratoriais, de imagem e monitoramento fetal. Isso pode incluir exames para detectar condições como diabetes gestacional, hipertensão, infecções e complicações no parto.  
•	Acompanhamento Pós-Parto: Exames realizados para avaliar a recuperação da mulher após o parto, detectar complicações como infecções ou problemas hormonais e garantir a saúde geral da mãe e do bebê.  
•	Exames para Diagnóstico de Cânceres Ginecológicos: Além do Papanicolau, exames de imagem como ultrassonografia, ressonância magnética ou tomografia podem ser utilizados para investigar cânceres ginecológicos, como os de ovário, útero e vulva.  

---
**(Subgrupo 02.11) – Forma de Organização 02.11.07 – Diagnóstico em Otorrinolaringologia e/ou Fonoaudiologia:**  
Refere à organização de exames diagnósticos voltados para as especialidades de otorrinolaringologia e fonoaudiologia, que tratam de doenças relacionadas aos ouvidos, nariz, garganta, voz, fala e audição.  
As principais características dessa forma de organização incluem:  
•	Otorrinolaringologia (ORL) – Diagnóstico.  
•	Avaliação de Distúrbios Auditivos:Audiometria: Exame para avaliar a acuidade auditiva, identificando perda auditiva e suas causas, seja condutiva ou neurossensorial.  
•	Timpanometria: Avaliação da função da membrana timpânica e da mobilidade dos ossículos, auxiliando no diagnóstico de problemas como otite média e outras condições do ouvido médio.  
•	Exame de Impedância Acústica: Avalia a pressão no ouvido médio e é útil no diagnóstico de disfunções da trompa de Eustáquio e otites.  
•	Emissões Otoacústicas (EOAs): Teste de triagem para detecção precoce de perdas auditivas em recém-nascidos e crianças.  
Diagnóstico de Distúrbios nas Vias Aéreas Superiores:  
•	Endoscopia Nasal e Laringoscopia: Exames endoscópicos para examinar a cavidade nasal, seios paranasais, laringe e faringe, detectando condições como pólipos nasais, tumores, inflamações ou obstruções nas vias respiratórias.  
•	Exame de Nasofibroscopia: Utilizado para avaliação mais detalhada das vias aéreas superiores, incluindo as fossas nasais e faringe.
•	Tomografia Computadorizada (TC) e Ressonância Magnética (RM): Exames de imagem para avaliar estruturas internas mais profundas, como os seios paranasais, a base do crânio e o ouvido interno.  
Exames para Distúrbios da Deglutição e Fala:  
•	Avaliação da deglutição e possíveis dificuldades associadas a doenças como refluxo gastroesofágico, AVC ou distúrbios neurológicos que afetam os músculos responsáveis pelo ato de engolir.  
•	Fonoaudiologia – Diagnóstico  
Avaliação da Fala e Linguagem:  
•	Testes de Linguagem e Fala: Utilizados para identificar dificuldades na aquisição e compreensão da linguagem, distúrbios na articulação, problemas de fluência (como gagueira), entre outros.  
•	Exame de Voz: Avaliação da qualidade vocal, tom, intensidade e pitch (altura) da voz, ajudando a diagnosticar disfonias e outras alterações vocais.  
Avaliação da Audição e Processamento Auditivo:  
Testes de Processamento Auditivo Central (TPAC): Avaliação de como o cérebro processa sons, importante no diagnóstico de dificuldades de compreensão auditiva, mesmo quando a acuidade auditiva está preservada.  
•	Exame de Reflexo Acústico: Avaliação da resposta auditiva reflexa ao som, auxiliando no diagnóstico de condições auditivas.  
Tratamento de Distúrbios de Comunicação:  
A fonoaudiologia não se limita ao diagnóstico, também realiza intervenções terapêuticas para tratar distúrbios de fala, linguagem, voz e audição. A combinação do diagnóstico com a intervenção é importante no acompanhamento de distúrbios como a afasia, disartria, alterações na voz ou dificuldades de articulação.  
Avaliação do Balanço e Vestibular:  
•	Exame Vestibular: Avaliação do equilíbrio e do sistema vestibular,frequentemente usada para diagnosticar distúrbios como vertigem, labirintite ou problemas relacionados ao equilíbrio.  
Avaliação em Neonatologia:  
•	Realização de testes de triagem auditiva em recém-nascidos, para detectar precocemente possíveis perdas auditivas, garantindo um diagnóstico e acompanhamento precoce.  

---
**(Subgrupo 02.11) – Forma de Organização 02.11.08 – Diagnóstico em Pneumologia:**  
Refere à organização e realização de exames diagnósticos voltados para o sistema respiratório, com foco em condições que afetam os pulmões, brônquios, pleura e demais estruturas respiratórias. A pneumologia abrange uma série de patologias, desde doenças pulmonares crônicas e infecciosas até condições pulmonares mais graves, como o câncer de pulmão.

---
**(Subgrupo 02.12) – Diagnóstico e Procedimentos Especiais em Hemoterapia:**  
Refere-se aos procedimentos e exames específicos voltados para a avaliação, diagnóstico e tratamento relacionados ao sangue e seus componentes, com ênfase na hemoterapia, que envolve a transfusão de sangue, seus componentes (como plaquetas, plasma e hemácias) e a gestão de terapias relacionadas ao sistema sanguíneo.  
A hemoterapia é uma área da medicina que lida com a administração de sangue ou seus componentes para tratar diversas condições, como anemia grave, sangramentos, distúrbios de coagulação e doenças hematológicas. Além disso, inclui o diagnóstico de doenças relacionadas ao sangue e a realização de procedimentos para tratamento de condições como leucemias, hemofilias, entre outras.  

---
**(Subgrupo 02.14) – Diagnóstico por Teste Rápido:**  
Refere-se a uma categoria de exames que fornecem resultados de diagnóstico em um curto período de tempo, normalmente em minutos ou algumas horas, ao contrário dos testes tradicionais que podem exigir mais tempo para obter resultados. Esses testes rápidos são utilizados em diversas áreas da saúde para facilitar o diagnóstico imediato, permitindo um tratamento mais ágil e eficaz, especialmente em situações de emergência ou quando a disponibilidade de recursos laboratoriais é limitada.  

Os testes rápidos podem ser realizados em diversos ambientes, como consultórios médicos, unidades de saúde, hospitais e até mesmo em campo (por exemplo, em locais de triagem). Eles são utilizados para detectar uma variedade de condições, desde infecções até problemas metabólicos ou imunológicos.  

Principais procedimentos – Diagnóstico por Teste Rápido.  
Tipos de Testes Rápidos:  
Testes Rápidos para Infecções:  
•	Testes para COVID-19: Testes rápidos como os antígenos e anticorpos são usados para detectar a infecção pelo SARS-CoV-2, o vírus causador da COVID-19. Esses testes são populares devido à sua velocidade e facilidade de uso, sendo realizados com amostras de saliva ou secreção nasal.  
•	Teste Rápido para HIV: Usados para detectar a presença de anticorpos contra o HIV, esses testes são realizados com uma gota de sangue e fornecem resultados em poucos minutos.
•	Testes Rápidos para Hepatites Virais: Testes para detectar infecção pelos vírus da hepatite B e C, usando amostras de sangue, com resultados rápidos.  
•	Testes para Malária: Diagnóstico rápido para infecção por Plasmodium (causador da malária), normalmente realizado com amostras de sangue.  
•	Testes Rápidos para Dengue, Zika e Chikungunya: São usados para detectar infecção por esses vírus transmitidos por mosquitos, com amostras de sangue ou soro.  
Testes Rápidos para Doenças Respiratórias:  
•	Testes para Gripe (Influenza): Testes rápidos para detectar infecção pelo vírus influenza, com resultados rápidos para distinguir entre a gripe comum e outras condições respiratórias.  
•	Testes Rápidos para Estreptococos (faringite estreptocócica): Usados para identificar infecções por estreptococos do grupo A, causadores de faringite (garganta inflamada), proporcionando diagnóstico imediato.  

Testes Rápidos para Doenças Sexualmente Transmissíveis (DSTs):  
•	Teste Rápido para Sífilis: Detecta anticorpos contra o Treponema pallidum, causador da sífilis, com amostras de sangue ou fluido corporal.  
•	Teste Rápido para Gonorreia e Clamídia: Usado para detectar essas infecções bacterianas com amostras de urina ou secreção, com resultados rápidos.  
Testes Rápidos para Glucose e Perfil Metabólico:  
•	Teste de Glicemia: Utilizado para verificar níveis de glicose no sangue de maneira rápida, sendo essencial para o diagnóstico e monitoramento do diabetes mellitus.  
•	Teste Rápido para Cetoacidose: Mede os níveis de cetonas no sangue ou urina, um indicativo de cetoacidose diabética.  

Testes Rápidos para Exames Imunológicos:  
•	Teste Rápido para Anticorpos: Detecta a presença de anticorpos específicos para doenças como o HIV, hepatite, dengue e outras infecções virais. Geralmente, utiliza-se uma amostra de sangue ou fluido corporal e fornece resultados em minutos.  
•	Testes Rápidos para Antígenos: Utilizados para detectar proteínas específicas do patógeno, como no caso do teste rápido para COVID-19, HIV ou gripe.  
Testes Rápidos para Coagulopatias:  
•	Teste Rápido de INR (International Normalized Ratio): Utilizado para monitorar pacientes em uso de anticoagulantes, como a varfarina, permitindo avaliar a coagulação sanguínea rapidamente.  

Exemplos de Testes Rápidos Comuns:  
•	Teste Rápido de Antígeno para COVID-19;  
•	Teste Rápido de Glicose;  
•	Teste Rápido para HIV;  
•	Teste Rápido para Hepatite B e C;  
•	Teste Rápido para Influenza;  
•	Teste Rápido de Gripe (A e B).  

---

**Procedimentos Clínicos Grupo 03:**  
Os Procedimentos Clínicos abrangem diversas formas de organização relacionadas à consulta médica, atendimento especializado, atenção domiciliar, urgências e outros serviços prestados aos pacientes. Abaixo, são detalhadas as formas de organização com base nos procedimentos mencionados, conforme os códigos do SIGTAP:  

**Consultas Médicas e/ou Outros Profissionais de Nível Superior:**  
Esses procedimentos são financiados com recursos do MAC (Média e Alta Complexidade), sendo relacionados a consultas e atendimentos realizados por médicos e outros profissionais de nível superior. Os códigos principais incluem:  
•	Consulta de Profissionais de Nível Superior na Atenção Especializada – Código 03.01.01.004-8.  
Relacionado a consultas realizadas por profissionais de saúde de nível superior, exceto médicos.  

•	Consulta Médica em Saúde do Trabalhador – Código 03.01.01.005-6.    
Consultas médicas específicas para a área de saúde ocupacional e do trabalhador.  

•	Consulta Médica em Atenção Especializada – Código 03.01.01.007-2.  
Consultas realizadas por médicos dentro da atenção especializada, fora do contexto de saúde pública geral.  

•	Consulta e/ou Atendimento Domiciliar na Atenção Especializada – Código 03.01.01.016-1
Consultas realizadas no domicílio do paciente, quando ele não pode se deslocar até a unidade de saúde.  

•	Atendimento de Urgência em Atenção Especializada – Código 03.01.06.006-1.  
Para situações de emergência hospitalar, onde o atendimento especializado de urgência é necessário.  

•	Administração de Medicamentos na Atenção Especializada – Código 03.01.10.001-2
Procedimentos relacionados à administração de medicamentos, realizados no contexto da atenção especializada.  

!!! warning "Observações Importantes:"
    Os resultados de exames auxiliares decorrentes de consultas não devem ser cobrados como uma nova consulta.  
    O atendimento de urgência em hospitais deve ser cobrado como Atendimento de Urgência em Atenção Especializada (Código 03.01.06.006-1).  
   
---
**Forma de Organização 03.01.05 – Atenção Domiciliar:**  
A atenção domiciliar é voltada para cuidados prestados aos pacientes em suas residências e é um tipo de atendimento financiado com recursos do MAC. Alguns procedimentos incluem:  
•	Assistência Domiciliar por Equipe Multiprofissional – Código 03.01.05.002-3.  
Inclui o atendimento multidisciplinar, realizado por uma equipe composta por médicos, enfermeiros, fisioterapeutas, entre outros.  

•	Assistência Domiciliar por Profissional de Nível Médio – Código 03.01.05.005-8.  
Atendimentos realizados por profissionais de nível médio, como técnicos de enfermagem.  

•	Antibioticoterapia Parenteral – Código 03.01.05.008-2.  
Administração de antibióticos via intravenosa ou intramuscular no domicílio.  

•	Atendimento Médico com Finalidade de Atestar Óbito – Código 03.01.05.009-0.  
Procedimento médico realizado para certificar o óbito do paciente.  

•	Visita Domiciliar Pós-Óbito – Código 03.01.05.010-4.  
Visitas realizadas por profissionais de saúde após o falecimento do paciente, com o objetivo de garantir o cumprimento de normas sanitárias ou outros procedimentos.  

•	Administração de Imunoderivados (Oral e/ou Parenteral) – Código 03.01.05.011-2.  
Administração de medicamentos imunológicos no domicílio, seja por via oral ou intravenosa.  

•	Terapia de Reidratação Parenteral – Código 03.01.05.012-0.  
Reidratação intravenosa para pacientes com desidratação severa.  

•	Busca Ativa – Código 03.01.05.013-9.  
Procedimento para buscar ativamente pacientes com doenças crônicas ou graves que necessitam de acompanhamento contínuo.  

•	Visita Domiciliar por Profissional de Nível Superior – Código 03.01.05.014-7.  
Visitas realizadas por médicos ou outros profissionais de saúde de nível superior ao domicílio do paciente.  

04.3 Forma de Organização 03.01.06 – Consulta e/ou Atendimento às Urgências (em geral).  
Estes procedimentos são voltados para o atendimento de urgências médicas e são financiados com recursos do MAC.  

Alguns dos códigos mais importantes incluem:  
•	Atendimento de Urgência com Observação até 24 horas em Atenção Especializada – Código 03.01.06.002-9.  
Atendimento de urgência, com observação do paciente por até 24 horas.  

•	Atendimento de Urgência em Atenção Especializada – Código 03.01.06.006-1.  
Procedimento de urgência, em que o atendimento especializado é necessário sem a necessidade de observação.  

•	Atendimento Ortopédico com Imobilização Provisória – Código 03.01.06.010-0.  
Inclui a consulta médica ortopédica com imobilização provisória, como no caso de fraturas, e a realização de exames radiológicos, que devem ser cobrados separadamente.  

---
**Forma de Organização 08 – Atendimento e/ou Acompanhamento Psicossocial.**  
Essa forma de organização está voltada para procedimentos de atendimento psicossocial financiados com recursos do MAC, como acompanhamento psicológico e psicoterápico, embora os detalhes específicos não sejam descritos aqui.  

---
**Forma de Organização 10 – Atendimentos de Enfermagem (em geral):**  
Esses procedimentos envolvem o atendimento realizado por enfermeiros e técnicos de enfermagem e são financiados com recursos do MAC. Alguns dos principais códigos incluem:  
•	Administração de Medicamentos na Atenção Especializada – Código 03.01.10.001-2.  
Administração de medicamentos, incluindo cuidados com a medicação em unidades de atenção especializada.  

•	Cuidados com Estomas – Código 03.01.10.006-3.  
Cuidados relacionados ao manejo de estomas (aberturas criadas para desviar secreções do corpo, como no caso de colostomias).  

•	Cuidados com Traqueostomia – Código 03.01.10.007-1.  
Cuidados específicos para pacientes com traqueostomia, incluindo higiene e manutenção.  

•	Determinação de Pressão Venosa Central (PVC) – Código 03.01.10.008-0.  
Monitoramento da pressão venosa central, utilizado em pacientes críticos.  

•	ENEMA – Código 03.01.10.009-8.  
Procedimento de administração de líquidos ou medicamentos no reto.  

•	Irrigação Vesical – Código 03.01.10.011-0.  
Irrigação da bexiga para tratar condições como infecções urinárias ou obstruções.  

O procedimento Administração de Medicamentos na Atenção Especializada – código 03.01.10.001.  
•   Consiste no ato de administrar medicamentos por paciente, independentemente da quantidade de medicação administrada, prescritos nas consultas/atendimentos, incluindo as consultas/atendimentos realizadas no domicílio.  

---
**Forma de Organização 03.01.07 – Atendimento e/ou Acompanhamento emReabilitação Física, Mental, Visual e Múltiplas Deficiências:**  
Refere aos procedimentos ambulatoriais voltados para a reabilitação de pacientes com diferentes tipos de deficiência.  

Principais Características:  
Abrange múltiplas deficiências: Física, mental, visual ou uma combinação delas.  

Objetivo: Atendimento especializado para promover a reabilitação e melhorar a qualidade de vida do paciente.
Serviços ofertados:  
•	Terapia ocupacional;  
•	Fisioterapia;  
•	Fonoaudiologia;  
•	Psicologia;  
•	Avaliação e adaptação de órteses e próteses.

Público-alvo: Pacientes com deficiências temporárias ou permanentes, encaminhados por profissionais de saúde.  
Execução: Realizado por equipes multiprofissionais em unidades de reabilitação credenciadas pelo SUS.  

---
**Forma de Organização 10 – Atendimentos de Enfermagem (em geral):**  
A Forma de Organização 10 corresponde aos atendimentos realizados por profissionais de enfermagem no contexto ambulatorial, incluindo ações de prevenção, promoção da saúde, assistência e acompanhamento de pacientes em diversas condições clínicas.  

Principais Características:  
Objetivo: Prestar cuidados de enfermagem em diferentes níveis de atenção à saúde.  

Público-alvo: Pacientes de todas as faixas etárias que necessitam de assistência de enfermagem em ambiente ambulatorial.  

Serviços ofertados:  
•	Consulta de enfermagem (avaliação e orientação);
•	Administração de medicamentos e imunobiológicos;
•	Curativos simples e complexos;
•	Retirada de pontos, troca de curativos e cuidados com feridas;
•	Coleta de exames laboratoriais;
•	Monitoramento de sinais vitais e acompanhamento de condições crônicas;
•	Ordenha Mamária;
•	Cateterismo Vesical de Alívio;
•	Sondagem Gástrica;
•	Terapia de Reidratação Oral;

---
**Forma de Organização 11 – Atendimento e/ou Acompanhamento de Queimados:**  
Refere-se aos serviços ambulatoriais especializados no atendimento e acompanhamento de pacientes vítimas de queimaduras, visando à reabilitação e prevenção de complicações.  
Principais Características:  
Objetivo: Prestar assistência especializada a pacientes com queimaduras, promovendo recuperação funcional e estética.  
Público-alvo: Indivíduos com queimaduras de qualquer grau, em fase aguda ou em acompanhamento pós-alta.  

Serviços ofertados:  
•	Avaliação clínica e curativos especializados.  
•	Controle da dor e prevenção de infecções.  
•	Tratamento de cicatrizes e sequelas, incluindo fisioterapia e terapia ocupacional.  
•	Encaminhamento para cirurgias reparadoras quando necessário.  
•	Apoio psicológico para pacientes e familiares.  

Locais de realização:  
•	Centros de referência para queimados.  
•	Serviços ambulatoriais especializados.  

---
**Forma de Organização 14 – Cuidados Paliativos:**  
Refere-se aos atendimentos voltados para pacientes que necessitam de cuidados paliativos, com o objetivo de melhorar a qualidade de vida diante de doenças graves e progressivas, controlando sintomas e oferecendo suporte multidisciplinar.  

Principais Características:  
Objetivo: Proporcionar alívio da dor e outros sintomas, promovendo conforto e suporte psicossocial para pacientes e familiares.  
Público-alvo: Pacientes com doenças crônicas avançadas, progressivas e sem possibilidade de cura, como câncer, doenças neurodegenerativas, insuficiências orgânicas e outras condições graves.  

Serviços ofertados:  
•	Atendimento médico e de enfermagem para controle de sintomas.  
•	Suporte psicológico e social para o paciente e sua família.  
•	Administração de medicamentos e terapias de suporte.  
•	Cuidados multidisciplinares, incluindo fisioterapia, nutrição e assistência social.  
•	Acompanhamento domiciliar, quando necessário.  

Locais de realização:  
Serviços de Atenção Domiciliar cadastrados no SUS.  
Ambulatórios e hospitais com equipes de cuidados paliativos.  

Registro e faturamento:  
•	O procedimento "Atendimento de Paciente em Cuidados Paliativos" (código 03.01.14.001-4) é financiado com recursos do Piso da Atenção Básica (PAB).  

---
**Forma de Organização 01 – Tratamento de Doenças Infecciosas e Parasitárias:**  
(Grupo 03 – Procedimentos Clínicos | Subgrupo 03 – Tratamentos Clínicos em Outras Especialidades).  
Abrange procedimentos ambulatoriais destinados ao diagnóstico, tratamento e acompanhamento de doenças infecciosas e parasitárias, contribuindo para o controle epidemiológico e a redução da morbimortalidade associada a essas enfermidades.  

Principais Características:  
Objetivo: Diagnóstico precoce, tratamento e acompanhamento clínico de pacientes com doenças infecciosas e parasitárias, reduzindo a transmissão e prevenindo complicações.  

Público-alvo: Pacientes diagnosticados ou com suspeita de doenças infecciosas e parasitárias, como:  
•	Tuberculose;
•	Hanseníase;
•	HIV/AIDS e Infecções Sexualmente Transmissíveis (ISTs);
•	Hepatites virais;
•	Dengue, chikungunya e outras arboviroses;
•	Leishmaniose, esquistossomose e outras parasitoses endêmicas;

Serviços ofertados:  
•	Consultas médicas e de enfermagem especializadas.  
•	Exames laboratoriais e de imagem para diagnóstico e monitoramento.  
•	Administração de medicamentos e terapias específicas.  
•	Acompanhamento de adesão ao tratamento.  
•   Notificação e vigilância epidemiológica em conformidade com o SUS.  

---
**Forma de Organização 08 – Tratamento de Doenças da Pele e do Tecido Subcutâneo:**  
Refere aos procedimentos ambulatoriais relacionados ao diagnóstico, tratamento e acompanhamento de doenças que afetam a pele e o tecido subcutâneo, abordando uma ampla gama de condições dermatológicas.  

Principais Características:  
Objetivo: Diagnóstico e tratamento de doenças que envolvem a pele e o tecido subcutâneo, com foco no controle, alívio dos sintomas e prevenção de complicações.  

Público-alvo: Pacientes com doenças dermatológicas de diversas naturezas, como:  
•	Dermatoses inflamatórias (psoríase, eczema, dermatite).  
•	Doenças infecciosas da pele (bactérias, fungos, vírus).  
•	Acne, rosácea e outras condições crônicas.  
•	Doenças autoimunes (lúpus eritematoso, dermatite herpetiforme).  
•	Câncer de pele (melanoma, carcinoma basocelular e espinocelular).  
•	Doenças parasitárias e alérgicas que afetam a pele (escabiose, urticária, etc.).  

Serviços ofertados:  
•	Consultas dermatológicas para diagnóstico e acompanhamento.  
•	Exames laboratoriais (como raspado de pele, biópsias).  
•	Tratamentos tópicos (cremes, pomadas, loções) e sistêmicos (medicações orais, injeções).  
•	Procedimentos cirúrgicos menores (remoção de lesões cutâneas benignas, biópsias).  
•	Tratamentos para doenças específicas, como fototerapia para psoríase ou tratamento cirúrgico para câncer de pele.  

---
**Forma de Organização 13 – Tratamento de Pacientes sob Cuidados Prolongados:**  
Abrange os cuidados médicos voltados para pacientes que necessitam de tratamento contínuo e prolongado devido a condições crônicas, complexas ou com sequela de doenças graves. Estes cuidados podem envolver a gestão de doenças em estágio avançado ou recuperação prolongada.  

Principais Características:  
Objetivo: Proporcionar o tratamento contínuo e adequado para pacientes com necessidades de cuidados prolongados, visando a melhora ou manutenção da qualidade de vida.  

Público-alvo: Pacientes com condições de saúde que requerem acompanhamento e cuidados a longo prazo, incluindo:  
•	Doenças crônicas complexas (insuficiência renal crônica, insuficiência cardíaca, doença pulmonar obstrutiva crônica - DPOC, diabetes tipo 2 com complicações).  
•	Recuperação de grandes cirurgias ou traumas.  
•	Pacientes com condições neurológicas progressivas (acidente vascular cerebral - AVC, esclerose múltipla, paralisia).  
•	Pacientes com distúrbios metabólicos ou endócrinos crônicos.  
•	Pacientes que necessitam de reabilitação prolongada (pós-acidente, reabilitação pulmonar, etc.).  

Serviços ofertados:  
•	Consultas médicas periódicas e acompanhamento especializado.  
•	Monitoramento de sinais vitais e ajuste de terapias.  
•	Terapias de reabilitação (fisioterapia, terapia ocupacional, fonoaudiologia).  
•	Cuidados de enfermagem, incluindo administração de medicamentos e monitoramento de complicações.  
•	Apoio psicológico e social, quando necessário.  

---
**Forma de Organização 18 – Tratamento HIV/AIDS:**  
Destinada ao tratamento de pacientes com HIV/AIDS, oferecendo cuidados médicos especializados para a prevenção da progressão para a AIDS e para a promoção da qualidade de vida dos pacientes. Esta forma de organização envolve o diagnóstico precoce, o manejo clínico, a terapia antirretroviral e o acompanhamento integral do paciente.  

Principais Características:  
Objetivo: Proporcionar o diagnóstico, tratamento e acompanhamento de pacientes com HIV/AIDS, com o objetivo de:  
•	Prevenir a progressão da infecção para AIDS.  
•	Melhorar a qualidade de vida do paciente.  
•	Promover a adesão ao tratamento antirretroviral.  
•	Reduzir a carga viral e aumentar a imunidade do paciente.  

Público-alvo:  
•	Pacientes diagnosticados com HIV, seja no estágio inicial ou em qualquer fase da infecção.  
•	Pacientes com AIDS, independentemente da gravidade.  
•	Pessoas em risco de infecção pelo HIV (para programas de prevenção, como profilaxia pós-exposição).  
Serviços ofertados:  
•	Diagnóstico: Testes de HIV, exames laboratoriais para monitoramento viral, contagem de CD4, exames de função hepática e renal.  
•	Tratamento antirretroviral (TAR): Início e acompanhamento do tratamento com medicamentos antirretrovirais, visando à supressão viral e aumento da imunidade.  
•	Acompanhamento clínico: Consultas regulares para monitoramento da resposta ao tratamento e manejo de comorbidades associadas.  
•	Prevenção de infecções oportunistas: Cuidados para prevenir e tratar doenças relacionadas à imunossupressão, como tuberculose, candidíase, pneumonias, entre outras.  
•	Aconselhamento: Apoio psicológico e psicossocial, orientações sobre adesão ao tratamento e redução do estigma.  
•	Educação em saúde: Programas educativos sobre prevenção, cuidados com a saúde e questões relacionadas ao HIV/AIDS.  

---
**Forma de Organização 19 – Tratamento de Reabilitação:**  
Destinada ao Tratamento de Reabilitação, que visa a recuperação da funcionalidade de pacientes que sofreram lesões, cirurgias, doenças ou condições que afetam suas habilidades físicas, mentais ou sociais. A reabilitação envolve um conjunto de intervenções que buscam recuperar a capacidade de o paciente realizar atividades do cotidiano e, quando possível, voltar a uma vida ativa e independente.  

Principais Características:  
Objetivo: Proporcionar a reabilitação dos pacientes que necessitam de cuidados contínuos para recuperar ou melhorar suas funções físicas, mentais ou sociais.  
  
Recuperação física: Após cirurgias, lesões traumáticas, doenças crônicas ou condições que afetam a mobilidade.  
Recuperação mental e cognitiva: Após lesões cerebrais, acidente vascular cerebral (AVC), ou condições que afetam a cognição.  
Recuperação social e ocupacional: Ajudar os pacientes a reintegrarem-se ao trabalho e à vida social.  

Público-alvo:  
•	Pacientes com sequelas de traumas ortopédicos (fraturas, lesões na coluna vertebral, etc.).  
•	Pacientes pós-cirúrgicos, como os que passaram por cirurgias cardíacas, neurológicas ou oncológicas.  
•	Pacientes com acidente vascular cerebral (AVC) ou outras condições neurológicas.  
•	Pacientes com distúrbios musculoesqueléticos crônicos, como artrite, esclerose múltipla, entre outros.  
•	Pacientes com condições que afetam habilidades sociais ou cognitivas (exemplo: distúrbios do desenvolvimento, demência, etc.).  

Serviços ofertados:  
•	Fisioterapia: Para recuperação de mobilidade, força muscular e funcionalidade. Inclui terapia manual, exercícios terapêuticos, treino de equilíbrio e propriocepção.  
•	Terapia ocupacional: Auxílio na adaptação de atividades da vida diária, como vestir-se, cozinhar, usar tecnologias e retornar ao trabalho.  
•	Fonoaudiologia: Para pacientes com dificuldades na fala, deglutição ou comunicação, especialmente após acidentes, AVC ou condições neurológicas.  
•	Psicoterapia ou neuropsicologia: Apoio psicológico para ajudar pacientes a lidarem com os aspectos emocionais da reabilitação, bem como o tratamento de déficits cognitivos.  
•	Terapia social: Envolvimento em atividades que promovem a reintegração social e ocupacional, como programas de reintegração no trabalho ou grupos de apoio.  
•	Atendimento interdisciplinar: A abordagem envolve vários profissionais de saúde, como médicos, enfermeiros, fisioterapeutas, terapeutas ocupacionais, psicólogos, nutricionistas e assistentes sociais.  

---
**Resumo do Faturamento Ambulatorial do SUS:**  
O faturamento ambulatorial do SUS segue um fluxo estruturado que envolve a entrada de dados, processamento, geração de relatórios e disseminação das informações.  

**Entradas:**  
Os dados iniciais são coletados de três sistemas principais:  
•	SIGTAP: Contém a tabela de procedimentos e valores do SUS.  
•	SCNES: Registra informações dos estabelecimentos de saúde.  
•	FPO-Mag: Permite ao gestor local definir a programação orçamentária, limites financeiros e ajustes de valores.  

**Processamento:**  
O Sistema de Informações Ambulatoriais (SIA) processa os dados de produção importados (BPA), validando-os com base em:  
•	Cadastro dos estabelecimentos (SCNES).  
•	Programação orçamentária (FPO-Mag).  
•	Regras definidas pelo Ministério da Saúde.  

O sistema calcula o valor bruto da produção e gera os Boletins de Diferença de Pagamento (BDP) quando há necessidade de ajustes financeiros.  

**Saídas:**  
Após a validação, o SIA gera relatórios essenciais para gestão e controle:  
•	Programação Orçamentária: Para acompanhamento do orçamento.  
•	Produção Ambulatorial: Indica atendimentos aprovados e rejeitados.  
•	Financeiro/Pagamento: Aponta valores brutos da produção aprovada.  

**Disseminação:**  
Os dados são enviados ao DATASUS, que valida e disponibiliza as informações por meio de:  
•	TABNET: Ferramenta online para consultas.  
•	TABWIN: Aplicativo para análise de dados no Windows.  

# Faturamento APAC

O módulo “APAC” (Autorização para Procedimento de Alta Complexidade) tem como objetivo o preenchimento, acompanhamento, gestão e atendimento das solicitações para procedimentos de alta complexidade.  

É um instrumento de registro das ações prestadas ao paciente, são procedimentos ambulatoriais que necessitam de autorização prévia. Além disso, identificar o paciente e possibilitar rastrear o tratamento, permitindo, assim, obter informações gerenciais, como dados para monitoramento, controle e auditoria.  

---
## **Fluxo do Atendimento que Exige Autorização:**  

O fluxo de atendimento dos usuários do SUS, começa com a procura por um estabelecimento de saúde com referência ao serviço APAC, que esteja devidamente cadastrado no SCNES para prestar atendimento APAC ao SUS.  
A definição do fluxo depende do procedimento a ser executado:  
•	O profissional responsável emite o Laudo de Solicitação/Autorização de Procedimentos Ambulatoriais;   
•	O usuário é encaminhado ao órgão autorizador, juntamente com as duas vias do Laudo, solicitando o número da autorização. O órgão autorizador verifica se o Laudo está corretamente preenchido e se a solicitação procede;  
•	Após a autorização do procedimento, o autorizador registra o número do laudo autorizado, a data de validade e o nome do estabelecimento de saúde onde o atendimento será realizado;  
•	A unidade presta o devido atendimento ao paciente e todos os procedimentos realizados são registrados no prontuário do paciente;  

---
## **Preenchimento dos Campos do Laudo de APAC:**  
O laudo é o documento utilizado para solicitação/autorização de procedimentos ambulatoriais em estabelecimentos de saúde com atendimento ambulatorial (públicos, federais, estaduais, municipais, privados com ou sem fins lucrativos) integrantes do SUS. O laudo contém informações essenciais, como:  
•	Identificação do estabelecimento;  
•	Dados do paciente;  
•	Exame físico, exames complementares; 
•	Técnica utilizada para o exame;  
•	Descrição detalhada do exame;  
•	Hipótese / impressão diagnóstica;  
•	Justificativas da solicitação;  
•	Dados de identificação do profissional solicitante e do autorizador;  
•	Códigos dos procedimentos de acordo com a Tabela de Procedimentos, Medicamentos e OPM do SUS e CID.  

Para assegurar a correta autorização do procedimento, todos os campos do laudo devem ser corretamente preenchidos, com letra legível e, após ser autorizado, deve ter o arquivamento de via no prontuário do usuário, a disposição de setores de regulação/avaliação, cabendo aos gestores editar normas referentes à necessidade de vias complementares.  
O laudo médico tem validade de 90 dias a contar da data de sua assinatura e a solicitação de um novo laudo somente deverá ser realizada após 75 dias a contar da data de emissão do último laudo solicitado.  

## **Principais tipos de APAC:**  
APAC Inicial/Continuidade:  
•	APAC Inicial: Emitida na primeira competência, com validade de três meses a partir da data de autorização.  
•	APAC 1ª de Continuidade: Apresentada na segunda competência, dando seguimento ao tratamento.  
•	APAC 2ª de Continuidade: Apresentada na terceira competência, finalizando o ciclo de três meses.  

APAC única:  
•	Possui validade de uma a três competências a partir da data de autorização, porém é apresentada apenas uma vez.  

APAC que admitem tratamento contínuo:  
Conforme descrição abaixo, os procedimentos que admitem tratamento contínuo, cujo período de validade da APAC é de 03 (três) competências, a partir do início da data da autorização, deverão ser registrados, utilizando-se o código 1 ou 2, da seguinte forma:  
 
Procedimentos que não admitem tratamento contínuo, cujo período de validade da autorização pode ser de 01 (uma) ou até 03 (três) competências, a partir da data de início da autorização, são registrados utilizando-se o código 1 ou 3.  
 

•	Novo Laudo de APAC: a unidade deverá solicitar nova autorização de APAC ao órgão emissor/autorizador, para o mesmo paciente, caso necessite continuar o tratamento após 03 (três) competências. Vale lembrar que a cada 03 (três) competências deverá ser solicitada nova autorização, caso o usuário continue o tratamento.  
•	Emissão de duas APAC: podem ser emitidas para procedimentos identificados como concomitantes ao tratamento para um mesmo paciente, na mesma competência, verificar as condições relacionadas no SIGTAP.  
•	Solicitação de mudança de procedimento: Durante o período de validade de uma APAC: caso a hipótese diagnóstica mude durante o tratamento ou seja  identificada outra patologia de maior gravidade que implique na necessidade de mudança do procedimento inicialmente autorizado, a APAC deverá ser encerrada com o código 2.6 por mudança de procedimento, conforme Tabela Motivo de Saída/Permanência e um novo Laudo deverá ser emitido pelo profissional responsável pelo paciente com o código do novo procedimento a ser autorizado.  

## **Procedimentos Secundários na APAC:**  
•	Registro: Os procedimentos secundários devem ser registrados na APAC juntamente com o procedimento principal. A correta associação entre procedimentos principais e secundários é fundamental para o adequado faturamento e controle dos serviços prestados.  
•	Compatibilidade: É necessário observar as compatibilidades estabelecidas na Tabela de Procedimentos do SUS (SIGTAP) para garantir que os procedimentos secundários sejam compatíveis com o procedimento principal registrado na APAC.  


## **Cadastro no CNES:**  
•	Exigências: Para a realização de determinados procedimentos, a unidade deve estar devidamente cadastrada no Cadastro Nacional de Estabelecimentos de Saúde (CNES) no serviço e classificação correspondentes, conforme as exigências estabelecidas no SIGTAP.  


## **Autorizadores de APAC:**
•	Profissionais Médicos: A Portaria MS/SAS nº 433, de 14 de novembro de 2000, estabelece que somente profissionais médicos vinculados à rede do SUS ou prestadores de serviços podem ser autorizadores de APAC. É importante que esses profissionais estejam devidamente cadastrados e habilitados para realizar a autorização dos procedimentos.  

## **Prontuário do paciente APAC:**  
Compõe a documentação comprobatória da assistência prestada, incluindo prescrições médicas, relatórios de enfermagem, registros de evolução multidisciplinar e resultados de exames complementares.  
Além disso, o prontuário deve conter:  
•	A identificação completa do paciente e os registros de admissão e alta.  
•	A compatibilidade entre os procedimentos realizados e os diagnósticos apresentados.  
•	A justificativa para a continuidade, se for o caso.  
•	O consentimento informado para procedimentos invasivos e terapêuticos de maior complexidade.  

Procedimentos que utilizam Apac como instrumento de registro são:  
• Ultrassonografia de mama.  
• Ressonância magnética de mama.  
• Cateterismo cardíaco.  
• Deficiência auditiva.  
• Glaucoma.  
• Diagnóstico de doenças raras.  
• Paciente submetido à ventilação mecânica não invasiva.  
• Acompanhamento de paciente queimado.  
• Acompanhamento de cirurgia bariátrica.  
• Acompanhamento de paciente pré-dialítico.  
• Radioterapia.  
• Quimioterapia.  
• Iodoterapia.  
• Terapia renal substitutiva.  
• Odontologia especializada.  
• Litotripsia.  
• Cirurgia ambulatorial eletiva.  
• relacionados transplantes.  
• Medicamentos.  

## **Procedimentos APAC por Grupo e Subgrupo:**  
Exames Secundários Registrados na APAC.  
Os exames secundários registrados na APAC (Autorização de Procedimentos de Alta Complexidade) possuem valores de referência definidos na Tabela SIGTAP.  

**(Subgrupo 02.02) – Diagnóstico em Laboratório Clínico:**  
Os procedimentos secundários referem-se a exames laboratoriais de média e alta complexidade que são solicitados como complementares a um procedimento principal já autorizado via APAC.  

Principais Características:  
•	Os exames secundários não podem ser solicitados isoladamente, devendo estar vinculados a um procedimento principal.  
•	Justificativa clínica obrigatória no prontuário.  
•	Controle e auditoria para verificar compatibilidade entre os exames solicitados e a condição clínica registrada.  

Exemplos de Exames Secundários:  
•	Dosagens hormonais para monitoramento de doenças crônicas.  
•	Exames genéticos vinculados a investigações diagnósticas.  
•	Testes laboratoriais para acompanhamento de terapias de alta complexidade.  

**(Subgrupo 02.04) – Diagnóstico por Radiologia**  

**(Subgrupo 02.05) – Diagnóstico por Ultrassonografia**  
Os procedimentos Ultrassonografia de Mama Unilateral para Avaliação de Possíveis Complicações de Implante de Prótese (código 02.05.02.020-8) e Ultrassonografia de Mama Bilateral para Avaliação de Possíveis Complicações de Implante de Prótese (código 02.05.02.021-6) têm como instrumento de registro a APAC-Única.  

**(Subgrupo 02.06) – Diagnóstico por Tomografia Computadorizada**  
O procedimento Tomografia por Emissão de Pósitrons (PET-CT) (código 02.06.01.009-5) é registrado na APAC como procedimento principal e é financiado pelo FAEC por seis meses, conforme a Portaria MS/SAS nº 1.340, de 1º de dezembro de 2014.  

**(Subgrupo 02.07) – Diagnóstico por Ressonância Magnética**  

**(Subgrupo 02.11) – Diagnóstico em Otorrinolaringologia e/ou Fonoaudiologia**
Procedimentos registrados na APAC:  
•	Avaliação para Diagnóstico Diferencial de Deficiência Auditiva (código 02.11.07.010-6).  
•	Reavaliação Diagnóstica de Deficiência Auditiva em Paciente Maior de 3 anos (código 02.11.07.029-7).  
•	Reavaliação Diagnóstica de Deficiência Auditiva em Paciente Menor de 3 anos (código 02.11.07.030-0).  
•	Seleção e Verificação de Benefício do Aparelho de Amplificação Sonora Individual (AASI) (código 02.11.07.031-9).  

A unidade deve possuir habilitação específica em Média ou Alta Complexidade como Centro de Reabilitação Auditiva (22-05 ou 22.10).  

---
**Grupo 03 – Procedimentos Clínicos:**  
**Forma de Organização – 03.01.01 – Consultas Médicas e/ou Outros Profissionais de Nível Superior.**  
Os procedimentos listados a seguir são financiados com recursos do FAEC e registrados na APAC conforme as Portarias MS/SAS nº 920, de 15 de dezembro de 2011 e MS/GM nº 199, de 30 de janeiro de 2014:  
•	Consulta para Diagnóstico e/ou Reavaliação de Glaucoma (código 03.01.01.010-2).  
•	Avaliação Clínica para Diagnóstico de Doenças Raras – Eixo I: 1 – Anomalias Congênitas ou de Manifestação Tardia (código 03.01.01.019-6).  
•	Avaliação Clínica para Diagnóstico de Doenças Raras - Eixo I: 2 – Deficiência Intelectual (código 03.01.01.020-0).  
•	Avaliação Clínica de Diagnóstico de Doenças Raras Eixo I: 3 – Erros Inatos de Metabolismo (código 03.01.01.021-8).  


**Forma de Organização – 03.01.05 - Atenção Domiciliar:**  
•	Acompanhamento e Avaliação Domiciliar de Paciente submetido à Ventilação Mecânica não Invasiva (código 03.01.05.001-5) – procedimento principal financiado com recursos do MAC.  
•	Instalação e/ou Manutenção de Ventilação Mecânica não Invasiva Domiciliar (código 03.01.05.006-6) – procedimento secundário.  

**Forma de Organização – 11 – Atendimento e/ou Acompanhamento de Queimados:**  
•	Acompanhamento de Paciente Médio e/ou Grande Queimado (código 03.01.11.001-8).  
•	Acompanhamento de Paciente Pequeno Queimado (código 03.01.11.002-6).  

---
**Grupo 05 – Transplantes de Órgãos, Tecidos e Células:**  
•	Subgrupo 01 – Coleta e Exames para Fins de Doação de Órgãos, Tecidos e Células e de Transplante.  

## **Processamento APAC**  
As informações registradas no atendimento ao paciente são disponibilizadas para o setor de faturamento da unidade onde são analisadas, processadas no sistema APAC - MAG e enviadas à Secretaria Estadual ou Municipal de Saúde, conforme a gestão do estabelecimento.  

Após o processamento e análise da produção APAC, o gestor deve encaminhar em meio magnético dois arquivos:
•	Um arquivo com valores brutos para o Setor Financeiro avaliar, calcular descontos e efetuar pagamentos aos prestadores de serviço ao SUS.  
•	Um arquivo com informações para a base de dados do SIA para o DATASUS/SE/MS/RJ, para alimentação do Banco de Dados Nacional.  
•	Compete ao DATASUS efetuar a validação do banco de dados e disseminar as informações da produção ambulatorial por meio dos programas TABWIN e TABNET.  
•	O SIA emite uma série de relatórios que possibilitam auxiliar os gestores no desenvolvimento das ações de planejamento, programação, regulação, avaliação, controle e auditoria, objetivando a melhoria da qualidade do atendimento prestado a sua população.  


!!! info "Observações"

    •	Registro de mais de um procedimento principal é possível apenas para os Medicamentos do Componente Especializado da Assistência Farmacêutica, num quantitativo de, no máximo, até 05 (cinco) procedimentos principais.  
    •	Procedimentos de Tratamento Não Contínuo: Procedimentos que não admitem continuidade de tratamento só podem ser apresentados uma única vez.  
    •	Conformidade das APAC: As autorizações de procedimentos (APAC) devem seguir as normas específicas do Ministério da Saúde, além das regulamentações complementares definidas pelo gestor local.  
    •	 Não há crítica quanto à repetição de número de autorização (APAC), portanto todas as autorizações (APAC) serão normalmente consistidas.  
    •	 Consulta de Utilização de APAC: Para verificar se um número de APAC foi utilizado em outra competência ou estabelecimento, basta consultar o site [http://sia.datasus.gov.br](http://sia.datasus.gov.br) na seção “Remessas de APAC”, digitando o número da autorização.  
    •	Os registros no prontuário paciente correspondem aos procedimentos apresentados e/ou autorizados no Demonstrativo de APAC por Meio Magnético, incluindo os procedimentos secundários. Essa prática é essencial para garantir a conformidade e a precisão dos dados no Sistema Único de Saúde (SUS).  
