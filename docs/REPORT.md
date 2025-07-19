# A Fusão Invisível no Mercado Financeiro Brasileiro

---

_**Integrantes:**_
* Enzo Alves Barcelos Gripp, (eabgripp@sga.pucminas.br)
* Pedro Dias Soares, (pedrosoares@gmail.com)
* Thiago Domingos Venturim Ribeiro dos Santos, (thiagodomingosventutim@gmail.com)

**Resumo:**
Este projeto, submetido ao Challenge State of Data Brazil 2025, analisa a transformação do setor financeiro brasileiro sob a ótica dos profissionais de dados. O estudo investiga a dinâmica entre a "Fintechzação" dos bancos e a "Bancarização" das fintechs.

Utilizando uma análise longitudinal inédita com dados das pesquisas de 2022, 2023 e 2024, a pesquisa explora a evolução de salários, tecnologias, desafios de liderança e perfis profissionais.

O objetivo é mapear como a disputa entre bancos tradicionais e fintechs está moldando o mercado de trabalho e as carreiras em dados no Brasil, fornecendo insights estratégicos para profissionais e empresas do setor.
---

## Sumario:

[1. INTRODUÇÃO](#Introdução)   

[2. CONTEXTUALIZAÇÃO](#Contextualização)

[3. PROBLEMA](#Problema)

[4. PERGUNTA DIRECIONADA A DADOS](#Pergunta_Direcionada_a_Dados)

[5. OBJETIVOS](#Objetivo)

[6. JUSTIFICATIVAS](#Justificativas)

[7. PÚBLICO ALVO](#Público_alvo)

[9. PREPARAÇÂO DOS DADOS](#Preparação_dos_dados)

[8. ANÁLISE EXPLORATÓRIA DOS DADOS](#Análise_exploratória_dos_dados)

[10. INDUÇÃO DO MODELO](#Indução_de_modelos)

[11. RESULTADOS](#Resultados)  

[13. CONCLUSÃO](#Conclusão)

[14. REFERÊNCIAS](#REFERÊNCIAS)

[15. APÊNDICES](#APÊNDICES)

---

<div id='Introdução'/>  
  
## Introdução:

Com grande entusiasmo, submetemos esta análise ao Challenge State of Data Brazil 2025, uma iniciativa promovida pela comunidade Data Hackers em parceria com a Bain & Company. Motivados pela oportunidade de contribuir com o maior mapeamento do mercado de dados do país, nosso projeto investiga um dos fenômenos mais impactantes e atuais do cenário financeiro nacional.

Nossa pesquisa concentra-se na interseção entre dois movimentos convergentes e, ao mesmo tempo, contrastantes: a “Fintechzação” dos bancos e a “Bancarização” das Fintech's. Enquanto o primeiro representa a incorporação de tecnologias ágeis, inovação digital e experiência centrada no usuário por instituições tradicionais, o segundo sinaliza o avanço das Fintech's rumo a estruturas mais robustas, reguladas e próximas do sistema bancário convencional.

Para explorar as nuances dessa transformação, realizamos uma análise longitudinal inédita utilizando as bases da pesquisa State of Data Brazil dos anos de 2022, 2023 e 2024 (a base central deste Challenge). Essa abordagem nos permite observar a evolução do ecossistema de dados ao longo do tempo e responder a perguntas essenciais.

Nosso objetivo é ir além de uma análise exploratória descritiva, propondo uma visão temporal e comparativa que revele tendências, padrões e insights relevantes sobre como o mercado de dados tem refletido — e influenciado — a transformação do setor financeiro brasileiro.

Convidamos a banca avaliadora e a comunidade a explorar conosco esta jornada analítica, que busca unir rigor técnico, inovação metodológica e impacto real sobre os rumos da economia digital no Brasil.

---

<div id='Contextualização'/>  
  
## Contextualização:

Nos últimos dez anos, o Brasil vivencia um verdadeiro ponto de inflexão em seu sistema financeiro — uma transformação profunda impulsionada por avanços tecnológicos e por reformas regulatórias estratégicas. Durante décadas, a “Bancarização” foi a principal métrica de inclusão financeira no país, com foco em integrar a população ao sistema bancário tradicional por meio da expansão de agências, contas correntes e produtos convencionais. No entanto, um novo fenômeno emergiu e passou a redefinir as regras do jogo: a “Fintechzação”.

O lançamento do PIX, em 2020, pelo Banco Central, foi um divisor de águas. Essa tecnologia de pagamentos instantâneos não somente democratizou o acesso a transações financeiras, como também nivelou o campo competitivo. Fintech's — com seu DNA digital, foco em experiência do usuário e cultura orientada por dados — ganharam protagonismo e passaram a competir diretamente com bancos tradicionais em escala nacional.

Esse novo cenário desencadeou uma dinâmica inédita:

  * A ascensão das Fintech's: empresas nativamente digitais conquistaram rapidamente milhões de clientes, muitos dos quais anteriormente "desbancarizados" ou sub-atendidos. Elas reinventaram experiências de crédito, investimento e pagamento, tornando-as mais acessíveis, rápidas e intuitivas.

  * A Reação dos Incumbentes: Diante da concorrência crescente, os grandes bancos aceleraram sua própria transformação digital. Investiram pesadamente em tecnologia, criaram estruturas ágeis — como seus próprios bancos digitais — e modernizaram seus sistemas legados. Nesse processo, a “bancarização” deixou de significar somente inclusão no sistema bancário e passou a abranger também a digitalização de seus próprios serviços e clientes.

No centro dessa revolução está o dado. Hoje, a disputa por clientes, a personalização do crédito, a prevenção de fraudes e a criação de produtos inovadores são travadas em um território comum: a análise de dados, o Machine Learning e a Inteligência Artificial.

É exatamente nesse contexto que nossa pesquisa se insere. Apesar da ampla cobertura midiática sobre a transformação do setor financeiro, ainda são raras as análises que focam em quem realmente executa essa mudança: os profissionais de dados. A série histórica da pesquisa **State of Data Brazil**, de 2022 a 2024, oferece uma oportunidade ímpar de examinar essa transformação pela ótica dos dados — e das pessoas que os dominam.

Com base nessas bases, nossa investigação busca mapear a evolução das carreiras, remunerações, ferramentas e desafios dos profissionais de dados, explorando como esses aspectos se comportam diante da crescente convergência (e competição) entre a agilidade das Fintech's e a escala dos bancos tradicionais em seu processo de digitalização.

---

<div id='Problema'/>  

## Problema:

O setor financeiro brasileiro está em meio a uma revolução digital, marcada pela disputa acirrada entre a agilidade das Fintech's (“Fintechzação”) e a escala dos bancos tradicionais (“Bancarização”).

O _problema_ é que, embora essa transformação seja visível do ponto de vista do mercado e do consumidor, seu impacto real sobre o capital humano que a executa — os profissionais de dados — permanece amplamente desconhecido e sem dados estruturados.

---

<div id='Pergunta_Direcionada_a_Dados'/> 

## Perguntas Direcionada a Dados:

A partir das bases da pesquisa State of Data Brazil dos anos 2022, 2023 e 2024, estruturamos esta análise com base em perguntas orientadas a dados, cada uma guiada por hipóteses que serão validadas ou refutadas com evidências quantitativas. O objetivo é compreender como a disputa entre Bancos Tradicionais e Fintech's molda o cenário profissional da área de dados no Brasil — em termos de remuneração, infraestrutura tecnológica, desafios de liderança e transformações no perfil dos profissionais.

### **Eixo 1 — Remuneração e Valorização Profissional**

* Pergunta-chave:
  Como a mediana salarial dos profissionais de dados evoluiu comparativamente entre Bancos Tradicionais (associados à "Bancarização") e Fintech's (associadas à "Fintechzação") entre 2022 e 2024?

* Hipótese:
  Em 2022, impulsionadas pela euforia do ecossistema de startups e pela ampla disponibilidade de capital de risco, as Fintech's tenderam a oferecer salários mais agressivos para atrair talentos qualificados. Acreditamos que, com a virada de mercado observada a partir de 2023 — marcada pela maior exigência de rentabilidade e pelo enxugamento de quadros —, essa vantagem salarial foi reduzida. Nossa hipótese é que, neste novo cenário, os bancos tradicionais reagiram, ajustando suas faixas salariais para atrair e reter profissionais sêniores e estratégicos, promovendo uma convergência salarial entre os dois setores.

### **Eixo 2 — Adoção Tecnológica e Estratégias de Infraestrutura**

* Pergunta-chave:
  Qual foi a evolução na preferência por provedores de nuvem (AWS, Azure, GCP) entre Bancos e Fintech's, e como essa escolha reflete suas respectivas estratégias de mercado e posicionamento tecnológico?

* Hipótese:
  Apesar da imagem tradicionalmente associada à rigidez dos bancos, nossa hipótese é que essas instituições aumentaram a adoção da AWS para iniciativas voltadas à inovação, dados e transformação digital. Por outro lado, as Fintech's, à medida que amadurecem e lidam com demandas de escalabilidade e custos, migraram para ambientes multicloud, ampliando sua adoção de Azure (pela integração com serviços corporativos) e GCP (pela eficiência em Big Data e Machine Learning). A distribuição por provedor, portanto, poderá revelar indícios estratégicos da maturidade tecnológica de cada segmento.

###  **Eixo 3 — Desafios de Liderança e Gestão**

* Pergunta-chave:
  Quais foram os principais desafios de gestão relatados por líderes de dados em Bancos e Fintech's entre 2022 e 2024, e como essas dificuldades se diferenciaram entre os dois modelos de organização?

* Hipótese:
  Esperamos identificar padrões distintos de desafios organizacionais. A hipótese é que líderes em Fintech's reportaram mais frequentemente questões relacionadas à escalabilidade de times, gestão do crescimento acelerado e estruturação de processos em ambientes ainda em consolidação. Já os líderes de bancos devem ter apontado como principais obstáculos a mudança de cultura organizacional, a modernização de sistemas legados e as restrições impostas pela burocracia interna. Essa diferença reflete as prioridades e maturidades distintas desses ambientes no enfrentamento de transformações digitais.

###  **Eixo 4 — Impacto da Transição de Mercado na Atuação Profissional**

* Pergunta-chave Principal:
  Como a transição do mercado entre 2023 e 2024 — de um ciclo de crescimento acelerado para um cenário de foco em eficiência e lucratividade — impactou a atuação dos profissionais de dados no setor financeiro?

* Hipótese Geral:
  Acreditamos que essa inflexão no ambiente macroeconômico e no setor de tecnologia, marcada por cortes de investimento, reestruturações e maior pressão por retorno financeiro, alterou profundamente o perfil, as ferramentas e as expectativas dos profissionais de dados no setor bancário e nas Fintech's. Para validar essa hipótese, exploraremos três subdimensões:

###  **Eixo 5 — Perfil Profissional dos Cientistas de Dados no Setor Financeiro**

* Pergunta-chave Principal:
  Como evoluiu o perfil dos profissionais de dados atuando em bancos e Fintech's entre 2022 e 2024, considerando aspectos como formação, senioridade, áreas de atuação e competências técnicas?

* Hipótese Geral:
  Nos últimos três anos, o setor financeiro passou por transformações estruturais que impactaram diretamente a composição e as exigências em torno dos profissionais de dados. Nossa hipótese é que houve uma especialização progressiva, com perfis mais técnicos, multidisciplinares e experientes ganhando protagonismo, especialmente em áreas críticas como Machine Learning, engenharia de dados e produtização de modelos. Essa tendência teria se acentuado nas Fintech's até 2022, mas passou a ser incorporada também pelos bancos a partir de 2023, com a aceleração da digitalização.

### v

**Pergunta-chave Principal:**

Como a distribuição geográfica dos profissionais de dados no setor financeiro brasileiro evoluiu entre 2022 e 2024? Quais polos de talentos se consolidaram para além do eixo Rio-São Paulo, e de que forma a ascensão do trabalho remoto reconfigurou as estratégias de atração e retenção de talentos por parte de Bancos e Fintechs?

**Hipótese Geral:**

Nossa hipótese é que, embora o eixo Rio-São Paulo mantenha sua histórica relevância como centro financeiro, a consolidação do trabalho remoto pós-pandemia impulsionou uma significativa descentralização dos talentos de dados. Inicialmente, as Fintechs, mais ágeis e digitais, capitalizaram sobre essa tendência para atrair profissionais de diversas regiões do país com modelos de trabalho flexíveis, ganhando vantagem competitiva.

 A partir de 2023, os bancos tradicionais, ao perceberem a perda de talentos para essa concorrência distribuída, foram forçados a adaptar suas estratégias, adotando modelos híbridos ou totalmente remotos.

 Esse movimento resultou na formação e fortalecimento de novos polos de tecnologia e dados em cidades como Florianópolis, Recife, Belo Horizonte e Campinas, transformando a disputa por profissionais em uma competição de escala nacional, não mais restrita aos grandes centros urbanos.


---

<div id='Objetivo'/>  

## Objetivo Geral:

O presente estudo visa analisar comparativamente a evolução e as diferenças estruturais no perfil profissional, nas faixas de remuneração, nas tecnologias adotadas e nos desafios enfrentados por profissionais de dados atuantes nos ecossistemas da chamada “Fintechzação” (empresas de tecnologia financeira) e da “Bancarização” digitalizada (instituições financeiras tradicionais) no Brasil.

A partir de uma abordagem quantitativa e longitudinal, o estudo utilizará os microdados das pesquisas State of Data Brazil referentes aos anos de 2022, 2023 e 2024, visando fornecer um panorama fundamentado em evidências sobre o impacto dessas duas forças concorrentes — e cada vez mais convergentes — na dinâmica do mercado de trabalho em ciência de dados no setor financeiro.

### Objetivos Específicos
Para viabilizar a consecução do objetivo geral, serão perseguidos os seguintes objetivos específicos:

  * Analisar a evolução da remuneração
    * Quantificar e comparar a mediana salarial dos profissionais de dados atuantes em bancos e Fintech's ao longo dos anos de 2022 a 2024.
    *  Identificar se a diferença de remuneração entre os setores aumentou, reduziu ou se estabilizou, à luz das mudanças macroeconômicas e da maturação das estratégias digitais no período.

  * Investigar a adoção tecnológica
    * Mapear as tendências de uso dos principais provedores de nuvem (AWS, Azure e GCP) por setor.
    * Verificar se as escolhas tecnológicas adotadas refletem diferentes níveis de maturidade, estratégias de escalabilidade, compliance e inovação entre bancos e Fintech's.

  * Comparar os desafios de liderança e gestão
    * Identificar os principais desafios relatados por líderes e gestores de dados em ambos os setores.
    * Analisar como esses desafios evoluíram no período e em que medida refletem características organizacionais distintas, como burocracia, escalabilidade ou transformação cultural.

  * Avaliar o impacto da transição de mercado (2023–2024)
    * Investigar como a mudança do modelo de crescimento exponencial para uma lógica orientada à eficiência e rentabilidade (foco em ROI) afetou a atuação dos profissionais de dados.
    *Analisar variações no perfil de contratação (com ênfase na senioridade), na valorização de competências técnicas, na percepção de estabilidade profissional e nas estratégias de carreira adotadas pelos profissionais em bancos e Fintech's.

---

<div id='Justificativas'/>  
  
## Justificativas:

Justificativa deste projeto se baseia em sua alta relevância estratégica e originalidade. Para os profissionais de dados, a análise funcionará como um guia de carreira baseado em dados, auxiliando em decisões sobre salários, habilidades e qual setor seguir. Para as empresas, fornecerá um diagnóstico competitivo sobre o mercado de talentos, essencial para estratégias de contratação e retenção.

Sua originalidade está na análise comparativa e evolutiva (2022–2024), que revela tendências reais ao invés de um retrato estático. Por fim, a pesquisa é extremamente oportuna, ao analisar o impacto da recente transição de mercado, fornecendo um mapa atualizado e necessário para toda a comunidade de dados brasileira.

---

<div id='Público_alvo'/>  

## Público_alvo


O presente estudo destina-se a um conjunto diversificado de públicos, cujas atividades profissionais e interesses estratégicos convergem para a interseção entre os setores de tecnologia e finanças no Brasil. O público-alvo pode ser segmentado em grupos primários, que são os sujeitos diretos da análise, e em um grupo secundário, que constitui o ecossistema de suporte e análise de mercado.

**Profissionais da Área de Dados**

Este grupo representa o foco central da investigação, para o qual os resultados oferecem um panorama detalhado do campo de atuação.

_Profissionais em atuação no setor financeiro_

Para analistas, cientistas, engenheiros de dados e outros especialistas que já atuam em bancos e fintechs, o estudo fornece subsídios para:
* Estruturar negociações de remuneração a partir de benchmarks salariais de mercado;
* Fundamentar decisões de carreira, como a escolha ou a transição entre instituições financeiras tradicionais e empresas de tecnologia financeira (fintechs);
* Direcionar o desenvolvimento de competências técnicas, com base nas tecnologias e ferramentas de maior relevância e adoção em cada segmento.

_Profissionais em formação ou em transição de carreira_

Para estudantes, recém-formados e profissionais que buscam ingressar na área de dados no setor financeiro, a pesquisa funciona como um referencial para:
* Compreender o perfil de competências e as qualificações mais demandadas pelo mercado;
* Analisar as faixas de remuneração de entrada e as perspectivas de progressão;
* Avaliar as distintas culturas organizacionais e desafios inerentes a bancos e fintechs.

**Organizações do Setor Financeiro**

As instituições que protagonizam a transformação digital do setor são um público estratégico, para o qual a análise oferece inteligência competitiva.

_Lideranças e gestores estratégicos_

Para executivos como Chief Technology Officers (CTOs), Chief Data Officers (CDOs) e diretores de áreas de dados e inovação, o estudo apresenta-se como uma ferramenta para:
* Realizar benchmarking de estratégias de tecnologia, remuneração e gestão de talentos;
* Diagnosticar a maturidade da própria operação de dados em comparação com o mercado;
* Informar o planejamento estratégico relacionado à infraestrutura tecnológica e à estruturação de equipes.

_Setores de Recursos Humanos e Aquisição de Talentos_

Para as equipes responsáveis pela gestão de pessoas, a pesquisa oferece um diagnóstico detalhado sobre o mercado de talentos, permitindo:
* Estruturar políticas de remuneração e benefícios mais competitivas;
* Otimizar os processos de recrutamento e seleção, alinhando as descrições de vagas às competências efetivamente valorizadas;
* Desenvolver estratégias para a retenção de profissionais qualificados.

_Ecossistema de Mercado e Acadêmico_

De forma mais ampla, os resultados do estudo são de interesse para um conjunto de atores que analisam, regulam ou oferecem serviços ao setor. Este grupo engloba empresas de consultoria estratégica, provedores de tecnologia (especialmente de computação em nuvem), instituições de ensino superior e técnico, e a comunidade de dados em geral. Para estes, a pesquisa oferece subsídios empíricos para análises de mercado, desenvolvimento de produtos, adequação de matrizes curriculares e fomento a debates qualificados sobre a evolução do setor no país.

---

<div id='Preparação_dos_dados'/>  

## Preparação dos dados:

A fase de preparação dos dados neste projeto foi dividida em várias sub-etapas essenciais para transformar os dados brutos de dife eu crentes anos em um conjunto de dados coeso e pronto para análise.

1. Coleta e Integração Inicial dos Dados
  Importação das Bases de Dados: Foram importados três conjuntos de dados distintos, correspondentes às pesquisas State of Data Brazil dos anos de 2022, 2023 e 2024. Para cada ano, um DataFrame do pandas foi criado (df_2022, df_2023, df_2024).

  Adição de Rastreabilidade Temporal: Para permitir a diferenciação e a análise comparativa entre as pesquisas, uma nova coluna, ano_base, foi adicionada a cada DataFrame, contendo o ano correspondente da coleta dos dados.

2. Limpeza e Padronização dos Dados (Data Cleaning)
  Padronização dos Nomes das Colunas: Uma etapa fundamental foi a padronização dos nomes das colunas em todas as três bases de dados. Foi criado um mapeamento com nomes simplificados e unificados (colunas_2022_simplificadas, colunas_2023_simplificadas, colunas_2024_simplificadas). Essa ação foi vital para:

  Harmonizar as variáveis entre os diferentes anos.

  Viabilizar a concatenação correta dos DataFrames.

  Assegurar a consistência semântica, mesmo com pequenas alterações nas perguntas da pesquisa ao longo do tempo.

3. Construção do Conjunto de Dados Final (Data Construction)
  Junção das Bases de Dados: Após a padronização, os três DataFrames anuais foram unidos em um único DataFrame chamado data_completo utilizando a função pd.concat. Este processo resultou em um conjunto de dados consolidado com 14.781 registros e 427 colunas, pronto para análises temporais.

  Seleção de Dados Relevantes (Subset): Para focar a análise em um segmento de mercado específico, foi criado um subconjunto de dados (df_financeiro) contendo apenas os registros dos setores de 'Finanças ou Bancos' and 'Seguros ou Previdência'. Isso reduziu o escopo para 2.750 registros, permitindo uma análise mais aprofundada do setor financeiro.

  Verificação de Dados Ausentes: Foi realizada uma verificação de valores nulos na coluna numero_funcionarios_empresa do DataFrame df_financeiro, confirmando que não havia dados faltantes nesta variável específica, o que é importante para a etapa seguinte.

4. Formatação e Geração de Novos Atributos (Feature Engineering)
  Criação de uma Variável Derivada: Um desafio identificado foi a ausência de uma distinção clara entre bancos tradicionais e Fintech's na base de dados. Para contornar isso, foi criada uma nova variável categórica, arquétipo_tamanho, com base na hipótese de que o número de funcionários poderia servir como um critério de distinção:

  Grande Porte (Provável Banco): Empresas com mais de 1.000 funcionários.

  Pequeno/Médio Porte (Provável Fintech): Empresas com até 1.000 funcionários.

  Essa nova coluna permitiu a segmentação e a análise comparativa entre esses dois perfis de empresas dentro do setor financeiro.

---

<div id='Análise_exploratória_dos_dados'/>  

## Análise Exploratória dos Dados:

Nossa análise exploratória foi estruturada a partir dos cinco eixos definidos anteriormente, permitindo uma visão multidimensional da transformação digital no setor financeiro brasileiro a partir da atuação dos profissionais de dados. Abaixo, detalhamos os principais achados de cada eixo.

* [Eixo 1 — Remuneração e Valorização Profissional](#Eixo_1)

* [Eixo 2 — Adoção Tecnológica e Estratégias de Infraestrutura](#Eixo_2)

* [Eixo 3 — Desafios de Liderança e Gestão](#Eixo_3)

* [Eixo 4 — Impacto da Transição de Mercado na Atuação Profissional](#Eixo_4)

* [Eixo 5 — Perfil Profissional dos Cientistas de Dados no Setor Financeiro](#Eixo_5)
  
* [Eixo 6 — A Geografia da Disputa por Talentos no Setor Financeiro(#Eixo- 6)

---

<div id='Eixo_1'/>  

## Eixo 1: Remuneração e Valorização Profissional.

### Distribuição Anual (2022-2024):

Os gráficos comparativos anuais mostraram a porcentagem de profissionais em cada faixa salarial. O objetivo era identificar padrões consistentes e diferenças estruturais. Por exemplo, se um tipo de empresa concentra mais profissionais em faixas salariais mais baixas ou mais altas.

<img width="1247" height="790" alt="image" src="https://github.com/user-attachments/assets/ae671ff3-2b3c-49ce-af2e-cbc419c9d54d" />
<img width="1247" height="790" alt="image" src="https://github.com/user-attachments/assets/cf9773ce-5a13-46d3-bbd6-43533a5ffb5f" />
<img width="1247" height="790" alt="image" src="https://github.com/user-attachments/assets/3f8d25f8-682d-4fdb-817b-62b4633d953a" />


**Analise do Resultado**

* **Finalidade dos Gráficos:** Servir como uma "fotografia" da estrutura de remuneração em cada setor para cada ano do estudo, permitindo uma comparação visual direta da evolução.

* **O que os Gráficos Mostram:**

2024: 0 As distribuições são visivelmente distintas. As Fintechs (azul claro) mostram uma concentração maior de profissionais em faixas salariais mais baixas (até R$ 4.000) e tatbém faixa altas ( R$ 20.000 - R$25.000), sugerindo uma estrutura mais heterogênea. Os Bancos(marrom) ja demostrava uma forte concentração na faixa de R$ 8.000- R$12.000. 
 
2023: A concentração dos Bancos na faixa de R8.000−R12.000 atinge seu pico (27,9%). As Fintechs mostram um aumento na faixa de R4.000−R6.000, mas a diferença geral entre os perfis permanece.

2024: Este é o gráfico chave. As duas distribuições se tornam notavelmente similares. Ambos os setores agora têm sua maior concentração de profissionais na faixa de R8.000−R12.000 (Bancos com 26%, Fintechs com 23,3%). A "barriga" do gráfico de ambos os arquétipos está alinhada, indicando uma estrutura salarial muito mais parecida.

* **Importância para a Análise:** Estes gráficos são a evidência visual primária da convergência salarial. A transição de perfis distintos em 2022 para perfis muito semelhantes em 2024 é a principal história que seus dados contam sobre remuneração.

* **Objetivo Atendido:** Atende diretamente ao objetivo de "Quantificar e comparar a mediana salarial dos profissionais de dados atuantes em bancos e Fintechs ao longo dos anos de 2022 a 2024".

* **Validação da Hipótese:** Os gráficos dão forte suporte à hipótese. A semelhança da distribuição em 2024 confirma a tese de que a vantagem salarial inicial das Fintechs foi reduzida e que os setores se aproximaram, promovendo uma convergência salarial.


### Variação Ano a Ano: 

A análise da variação percentual anual: (2023 vs. 2022) revelou a dinâmica do mercado. Os gráficos evidenciaram quais faixas salariais tiveram o maior crescimento ou queda na representatividade de profissionais, indicando tendências como “achatamento” ou “valorização” de certos níveis de remuneração em bancos e Fintech's.

<img width="1389" height="789" alt="image" src="https://github.com/user-attachments/assets/1d3fbe70-b949-44e8-a4a1-eaec3ef3cce1" />
<img width="1389" height="789" alt="image" src="https://github.com/user-attachments/assets/cc41ee31-936d-45e8-8d2a-00a6b7dbcae2" />


**Analise dos Resultados**


Estes gráficos mostram a variação percentual de profissionais em cada faixa salarial em relação ao ano anterior. Eles explicam a *dinâmica* por trás da convergência.

* **Finalidade do Gráfico:** Quantificar a *mudança* no foco de contratação e na composição das equipes de um ano para o outro, revelando as estratégias de cada setor.
  
* **O que o Gráfico Mostra:**

  
    * **Variação em 2023 (vs. 2022):** Foi um ano de movimentos agressivos. As Fintechs explodiram em contratações de salários altíssimos (um aumento de 209% na faixa de R$25-30k), característico da euforia do mercado. Os Bancos foram mais contidos, mas já mostravam reforços nas faixas de R$16-25k.
      
    * **Variação em 2024 (vs. 2023):** Este gráfico é a prova da "virada de mercado". As Fintechs mostram uma **redução drástica** de pessoal nas faixas mais baixas (-100%, -51%) e também em faixas altas (-10%, -18%), indicando o "enxugamento de quadros". Em contrapartida, os **Bancos mostram crescimento positivo em faixas salariais altas** (+69% na faixa de R$20-25k e +125% acima de R$40k), mostrando que reagiram para atrair e reter talentos estratégicos.
 
      
* **Importância para a Análise:** É a prova quantitativa da sua hipótese. Mostra a "euforia" das Fintechs (até 2023) e a subsequente "correção" e "enxugamento", ao mesmo tempo que evidencia a reação estratégica dos Bancos em 2024 para se tornarem mais competitivos em remuneração.

  
* **Objetivo Atendido:** Atende perfeitamente ao objetivo de "Identificar se a diferença de remuneração entre os setores aumentou, reduziu ou se estabilizou, à luz das mudanças macroeconômicas".

  
* **Validação da Hipótese:** **Validação fortíssima.** O gráfico de variação de 2024 é a materialização da sua hipótese: as Fintechs "enxugaram" após a euforia, e os Bancos ajustaram suas faixas salariais para cima, especialmente para posições mais estratégicas, acelerando a convergência.

### Perfil Médio Consolidado (2022-2024):

Ao calcular a média da distribuição dos três anos, foi possível visualizar um "retrato" geral e estável do perfil salarial. A análise dos dados (perfil_medio_df) sugere que:

<img width="1778" height="890" alt="image" src="https://github.com/user-attachments/assets/1ecf0e12-df3b-488b-9c3c-06f875b81362" />


**Analise dos Resultados**

* Perfil do Banco: Foco no Meio da Carreira. Os bancos possuem uma estrutura salarial que privilegia e concentra a maior parte de seus profissionais em faixas de remuneração intermediárias. É um modelo mais padronizado e com menor variação salarial entre os cargos.

* Perfil da Fintech: Estrutura mais Flexível e Polarizada. As fintechs demonstram uma estratégia de remuneração mais distribuída. Elas comportam uma base maior de profissionais em faixas de entrada ou de menor senioridade, mas, ao mesmo tempo, são mais agressivas na remuneração de talentos de alto nível e especialistas, pagando salários mais competitivos nas faixas superiores.


### Distribuição Salarial por Senioridade e Arquétipo

Esta análise focou nos salários mais altos (o valor que 75% dos profissionais ganham a menos que ele), revelando o potencial de ganho em cada nível. O gráfico de barras comparativo permitiu visualizar o "teto" salarial mais comum para os talentos mais bem pagos em bancos e Fintech's, sendo uma métrica importante para avaliar a competitividade na atração de profissionais sêniores.

<img width="1189" height="790" alt="image" src="https://github.com/user-attachments/assets/a49a4c2f-0165-423a-95b7-dda8f5cd6178" />
<img width="1389" height="889" alt="image" src="https://github.com/user-attachments/assets/5d24fb36-0cf0-4d6e-a958-3ee47112289b" />


**Analise dos Resultados**

Estes gráficos aprofundam a análise, segmentando o salário por nível de senioridade e mostrando não apenas a média, mas a distribuição completa (boxplot) e o teto para 75% dos profissionais (3º Quartil - p75).

* **Finalidade do Gráfico:** Entender se a convergência salarial acontece de forma igual em todos os níveis de carreira (Júnior, Pleno, Sênior).
  
* **O que o Gráfico Mostra:**
    * **Nível Júnior:** Bancos pagam mais (p75 de R$7.000 vs. R$5.000 das Fintechs).
      
    * **Nível Pleno:** Há um **empate técnico total** (p75 de R$10.000 para ambos). Este é o ponto máximo da convergência.
 
    * **Nível Sênior:** **As Fintechs ainda lideram com folga**, pagando significativamente mais para seus talentos sêniores de alta performance (p75 de R$18.000 vs. R$14.000 dos Bancos). O boxplot confirma isso, mostrando a mediana e todo o quartil superior das Fintechs acima dos Bancos.
 
      
* **Importância para a Análise:** Estes gráficos adicionam uma camada de **nuance fundamental** à sua conclusão. A "convergência salarial" geral é, na verdade, uma média de três realidades distintas. A convergência é total no nível Pleno, mas a disputa por talentos Sênior ainda favorece financeiramente as Fintechs.

  
* **Objetivo Atendido:** Contribui para "Analisar a evolução da remuneração" e "Analisar variações no perfil de contratação (com ênfase na senioridade)".

  
* **Validação da Hipótese:** **Valida a hipótese com uma nuance importante.** A hipótese de que os Bancos reagiram para atrair talentos sêniores está correta (como visto no gráfico de variação), mas estes gráficos mostram que, *apesar dessa reação*, as Fintechs ainda pagam um prêmio maior para segurar seus profissionais sêniores mais qualificados. A convergência é mais forte na base e no meio da pirâmide profissional.

---

### **Conclusão Geral para o Eixo 1**

Os gráficos apresentados fornecem um conjunto robusto de evidências que **confirmam amplamente a hipótese central do Eixo 1**.

A análise sequencial dos dados de 2022 a 2024 mostra claramente um movimento de **convergência salarial** entre Bancos e Fintechs. A "virada de mercado" em 2023-2024 é visível e quantificável: as Fintechs ajustaram suas estruturas, reduzindo quadros, enquanto os Bancos investiram para se tornarem mais competitivos.

A análise por senioridade refina a conclusão: a convergência é mais forte e já se concretizou nos níveis Júnior e Pleno. No nível Sênior, embora os Bancos tenham avançado, as Fintechs ainda mantêm uma vantagem salarial significativa para seus talentos de topo, indicando que a "guerra por talentos" nesse segmento continua acirrada, com as Fintechs dispostas a pagar um prêmio pela senioridade.


---

 <div id='Eixo_2'/>  

 ## Eixo 2 — Adoção Tecnológica e Estratégias de Infraestrutura
 
Neste eixo, a análise se aprofunda na infraestrutura tecnológica, investigando como bancos e Fintech's adotam plataformas de nuvem. O objetivo é medir a maturidade digital, a evolução da modernização e as estratégias de nuvem (incluindo multicloud e a persistência de sistemas legados on-premise).

## Evolução da Adoção de Pralaformas de Nuvem : Bancos vs. Fintechs (2022-2024)
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/1eb49a26-d8c8-43ac-b7a2-707deb7a7fa1" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/902d7989-f621-4406-b7b1-a7a73bd71dea" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/5a8cd137-8f3f-4664-ab89-a1af2901fa5b" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/a7231af7-91a9-47fa-896e-8259284557c9" />

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/1011b588-8505-4606-9043-e3ceea451d6c" />
**Analise dos Resultados**

Estes materiais mostram a porcentagem de adoção de cada um dos três principais provedores de nuvem, comparando Bancos e Fintechs.

* **Finalidade do Gráfico:** Visualizar e comparar a trajetória de adoção de cada provedor de nuvem (AWS, Azure, GCP) pelos dois arquétipos ao longo dos três anos, identificando tendências, picos e vales.
  
* **O que os Gráficos Mostram:**
    * **Padrão Incomum em 2023:** O dado mais gritante é o comportamento do mercado em 2023. Houve uma queda expressiva na adoção de **AWS** por ambos os setores, coincidindo com um pico massivo na adoção de **Azure** e **GCP**.
      
    * **Evolução da AWS:** Após a queda em 2023, a AWS teve uma recuperação impressionante em 2024, tornando-se novamente a nuvem dominante em ambos os setores, e com uma taxa de adoção nos Bancos (64,4%) superior à de 2022.
 
    * **Evolução de Azure e GCP:** Após o pico em 2023, a adoção de ambos os provedores recuou em 2024, mas permaneceu em um patamar superior ao de 2022, consolidando-os como players relevantes.
 
* **Importância para a Análise:** Estes gráficos revelam que a adoção tecnológica não foi linear. O ano de 2023 foi um ponto de inflexão, sugerindo um movimento de forte experimentação ou uma resposta a condições específicas de mercado (como otimização de custos ou busca por novas funcionalidades), seguido por uma reacomodação do mercado em 2024.

* **Objetivo Atendido:** Atende diretamente ao objetivo de "Mapear as tendências de uso dos principais provedores de nuvem (AWS, Azure e GCP) por setor".

  
* **Validação da Hipótese:**
    * **Parte 1 da Hipótese (Bancos aumentaram adoção de AWS): CONFIRMADA.** Comparando o ponto inicial (2022: 55%) com o final (2024: 64,4%), os bancos de fato ampliaram o uso da AWS, validando a ideia de que a adotaram para projetos de inovação. A queda em 2023 parece ter sido um desvio temporário nessa trajetória.
      
    * **Parte 2 da Hipótese (Fintechs migraram para multicloud, ampliando Azure e GCP): CONFIRMADA.** A hipótese é fortemente corroborada pelos dados. A adoção de Azure e GCP pelas Fintechs em 2024 é maior do que em 2022. Isso indica que, à medida que amadureceram, elas de fato diversificaram sua infraestrutura, exatamente como previsto.

## Evolução da Adoção de Pralaformas de Nuvem : Bancos vs. Fintechs (2022-2024)

---

### **Conclusão Geral para o Eixo 2**

Os dados e gráficos apresentados **confirmam a hipótese central do Eixo 2**, mas com uma história mais rica do que a hipótese inicialmente previa.

1.  **Bancos Aumentaram o Uso da AWS:** A hipótese de que os Bancos aumentariam a adoção da AWS para inovação é validada ao comparar os dados de 2022 e 2024. Eles estão ativamente migrando de ambientes On-Premise e consolidando a AWS como sua principal parceira na nuvem.

2.  **Fintechs Adotaram Multicloud (Azure e GCP):** A hipótese de que as Fintechs, ao amadurecerem, migrariam para ambientes multicloud, aumentando o uso de Azure e GCP, é totalmente confirmada. O crescimento da estratégia multicloud e os níveis de adoção de Azure/GCP em 2024 comprovam essa tendência.

O "evento" principal revelado pelos gráficos foi a **explosão da experimentação multicloud em 2023**. Esse movimento, liderado pelos Bancos mas também forte nas Fintechs, levou a uma reconfiguração do mercado em 2024, onde a AWS se reafirmou como líder, mas agora dentro de um ecossistema onde Azure e GCP se consolidaram como alternativas estratégicas importantes para ambos os setores.
---

<div id='Eixo_3'/>  

## Eixo 3 — Desafios de Liderança e Gestão

### Gráfico 1 - Evolução Anual dos Desafios de Liderança
<img width="1589" height="2805" alt="__results___27_1" src="https://github.com/user-attachments/assets/124b4bb5-d3ff-45fc-b69c-a4e6413d8571" />

#### Analise dos Resultados

O gráfico de barras comparativo, "Comparativo de Desafios de Liderança: Bancos vs. Fintechs", apresenta a frequência relativa com que líderes de cada segmento (Grande Porte/Bancos e Pequeno/Médio Porte/Fintechs) reportaram os principais desafios organizacionais. A análise visual dos dados valida de forma contundente a hipótese inicial do eixo 3, revelando padrões distintos e consistentes com as diferentes maturidades e contextos operacionais de cada arquétipo.

**Principais Insights Observados:**

* **Desafios em Bancos (Grande Porte):** Os líderes deste segmento apontaram com maior frequência desafios relacionados à transformação de estruturas consolidadas. Os três pontos que mais se destacam em comparação com as fintechs são:
    * **Mudar a cultura da empresa:** Apontado por aproximadamente 17.5% dos líderes de bancos, contra cerca de 10% nas fintechs. Este é o desafio com a maior disparidade, confirmando que a mudança cultural é o principal obstáculo em ambientes tradicionais.
    * **Burocracia interna / Etapas de aprovação:** Com quase 15% de frequência nos bancos versus apenas 5% nas fintechs, a rigidez processual se mostra uma barreira significativa.
    * **Lidar com a complexidade de sistemas legados:** Um desafio técnico clássico de instituições estabelecidas, mencionado por quase 9% dos líderes de bancos, uma frequência 3.5 vezes maior que a observada nas fintechs.

* **Desafios em Fintechs (Pequeno/Médio Porte):** Os desafios mais proeminentes para os líderes de fintechs estão diretamente ligados à expansão, estruturação e competição por talentos, reflexo de um ambiente de rápido crescimento.
    * **Estruturar e organizar a área de dados:** Sendo o principal desafio reportado por este grupo (cerca de 14%), a necessidade de construir processos e governança do zero é evidente.
    * **Contratar bons profissionais:** A competição por talentos é mais sentida nas fintechs (13%) do que nos bancos (10%), um claro sintoma da necessidade de escalar as equipes rapidamente.
    * **Falta de recursos (budget):** A restrição orçamentária é um desafio significativamente mais comum em fintechs (10%) do que em bancos (6%), o que impacta diretamente a capacidade de investimento em ferramentas e pessoal.

**Conclusão da Análise do Gráfico**

Os resultados visuais confirmam a hipótese: enquanto os **líderes de bancos** estão focados em uma batalha interna contra a **inércia cultural, a burocracia e a dívida tecnológica**, os **líderes de fintechs** enfrentam os desafios de **construir, escalar e competir** em um ambiente dinâmico e com recursos mais limitados. A "fusão invisível" se manifesta aqui não como uma convergência de problemas, mas como um espelho que reflete as dores de crescimento de um lado e as dores de transformação do outro.

### Gráfico 2 - Média Consolidada dos Desafios de Liderança
<img width="1589" height="1189" alt="__results___27_3" src="https://github.com/user-attachments/assets/5664d6f8-ee70-467a-8d5a-a000d7d987a3" />

#### Analise dos Resultados

Este gráfico de barras ilustra a taxa de adoção da ferramenta de assistência por IA, GitHub Copilot, entre os desenvolvedores de ambos os arquétipos de empresa. O resultado revela uma diferença marcante e estatisticamente significativa, fornecendo fortes evidências sobre as distintas culturas de inovação e agilidade tecnológica.

#### Principais Insights Observados:

* **Adoção em Fintechs (Pequeno/Médio Porte):** Apresentam uma taxa de adoção de **16.5%**. Este número sugere um ambiente que incentiva ou, no mínimo, permite a exploração de novas tecnologias que prometem acelerar o ciclo de desenvolvimento e aumentar a produtividade.

* **Adoção em Bancos (Grande Porte):** A taxa de adoção é significativamente menor, ficando em **9.3%**. Isso representa quase metade da taxa vista nas fintechs.

#### Interpretação e Hipóteses para a Disparidade:

A diferença expressiva nos dados não é acidental e pode ser atribuída a vários fatores que corroboram a tese central do projeto:

1.  **Agilidade vs. Burocracia:** As **fintechs** operam com um foco obsessivo em velocidade (*time-to-market*). Ferramentas como o Copilot são vistas como um meio de acelerar a entrega de código. Em contrapartida, os **bancos** possuem processos de aprovação de software mais longos e rigorosos, onde questões de segurança, conformidade (compliance) e propriedade intelectual do código gerado por IA são analisadas extensivamente antes da liberação para os desenvolvedores.

2.  **Cultura de Inovação:** A cultura das **fintechs** é, por natureza, mais aberta à experimentação. Há um incentivo para que os desenvolvedores testem novas ferramentas que possam lhes dar uma vantagem competitiva. Nos **bancos**, a aversão ao risco tende a ser maior, favorecendo o uso de ferramentas e processos já consolidados e amplamente validados, o que pode retardar a adoção de tecnologias de ponta.

3.  **Ambiente Tecnológico:** Desenvolvedores em **fintechs** frequentemente trabalham com tecnologias mais modernas (*greenfield projects*), onde a integração de novas ferramentas é mais simples. Os **bancos**, por outro lado, ainda lidam com a complexidade de sistemas legados, onde a introdução de uma ferramenta como o Copilot pode apresentar desafios técnicos e de segurança adicionais.

#### Conclusão da Análise do Gráfico:

A taxa de adoção do GitHub Copilot serve como um excelente indicador da velocidade e da abertura à inovação de cada setor. O resultado deste gráfico é um reflexo prático dos desafios de liderança vistos anteriormente: a mesma **burocracia** e o receio de **mudar a cultura** que desafiam os líderes nos bancos são, provavelmente, as mesmas forças que limitam a adoção de novas ferramentas por seus times técnicos. A "Fusão Invisível" pode estar a acontecer no nível dos produtos oferecidos ao cliente final, mas no "chão de fábrica" do desenvolvimento de software, as filosofias operacionais ainda são bastante distintas.

---

<div id='Eixo_4'/> 

## Eixo 4

### Profissionais que Participaram de Entrevistas nos Últimos 6 Meses

<img width="1189" height="690" alt="image" src="https://github.com/user-attachments/assets/e8a05916-80ad-4a8f-a92b-576034097c55" />

###  Profissionais Abertos a Mudar de Emprego

<img width="1189" height="690" alt="__results___53_0" src="https://github.com/user-attachments/assets/49ef99c3-9e68-4e5f-9026-a4d3c9fc0d76" />

**Analise dos Resultados**

Os gráficos "Profissionais que Participaram de Entrevistas" e "Profissionais Abertos a Mudar de Emprego" medem a mobilidade e a intenção de carreira dos profissionais.

* **Finalidade dos Gráficos:** Medir a "temperatura" do mercado de trabalho do ponto de vista do profissional, comparando a disposição para mudar de emprego com a ação efetiva de procurar uma nova posição.
* **O que os Gráficos Mostram:**
    * **Abertura para Mudança (Sentimento):** A disposição para mudar de emprego é **consistentemente alta e estável** para ambos os setores, sempre próxima ou acima de 70%. Isso indica que os profissionais de dados estão cronicamente abertos a boas oportunidades.
    * **Participação em Entrevistas (Ação):** Aqui reside a grande mudança. Há uma **tendência de queda clara e convergente** para ambos os setores. Em 2022, no auge do mercado aquecido, quase 60% dos profissionais estavam em processos seletivos. Em 2024, esse número cai para cerca de 50%. A busca ativa por um novo emprego diminuiu.
* **Importância para a Análise:** Os gráficos revelam uma dissociação crucial entre "querer" e "fazer". Enquanto o desejo por melhores condições é perene, a iniciativa de buscar ativamente uma mudança diminuiu. Isso sinaliza um aumento na aversão ao risco e uma valorização da estabilidade no emprego atual, comportamento clássico de um mercado que "esfriou".
* **Objetivo Atendido:** Atende diretamente ao objetivo de "Analisar variações... na percepção de estabilidade profissional e nas estratégias de carreira adotadas pelos profissionais".
* **Validação da Hipótese:** **A hipótese é fortemente suportada.** A "virada de mercado" e a "maior pressão por retorno financeiro" mencionadas na hipótese se manifestam aqui como um comportamento mais cauteloso por parte dos profissionais. A diminuição na busca ativa por empregos é um reflexo direto do aumento da incerteza e do fim do ciclo de crescimento acelerado.

### Mudança nos Critérios para Escolha de Emprego (2022-2024)

<img width="1389" height="890" alt="__results___56_0" src="https://github.com/user-attachments/assets/2e901fe7-6ddb-45d1-8549-033ec66564f1" />

### Evolução da Importância dos Critérios de Escolha de Emprego (2022-2024)

<img width="1790" height="1253" alt="image" src="https://github.com/user-attachments/assets/725d4cee-5dbd-43c9-b7d1-bb40516303a9" />


Os gráficos "Mudança nos Critérios" e "Evolução da Importância" mostram o que os profissionais passaram a valorizar mais ao longo do tempo.

* **Finalidade dos Gráficos:** Identificar a mudança nas prioridades dos profissionais ao avaliar uma oportunidade de emprego, revelando a transformação de suas expectativas em resposta ao novo cenário de mercado.
* **O que os Gráficos Mostram:**
    * **Fator nº 1 e Inabalável:** "Remuneração/Salário" continua sendo, de longe, o critério mais importante, e sua relevância até aumentou ligeiramente ao longo dos anos.
    * **Critérios em Ascensão (A Busca por Segurança):** Os fatores que mais ganharam importância de 2022 para 2024 são **"Benefícios"** e **"Plano de Carreira"**. Ambos mostram uma trajetória de crescimento clara e consistente.
    * **Critérios em Queda (O Fim da Euforia):** O critério que mais perdeu importância foi **"Oportunidade de Aprendizado"**. "Flexibilidade/Remoto", apesar de ainda muito relevante, teve seu pico em 2023 e começou a declinar.
* **Importância para a Análise:** Este é o coração da validação do Eixo 4. A análise mostra uma troca de prioridades: os profissionais estão migrando de um mindset focado em crescimento pessoal e flexibilidade (típico de um mercado de "vagas sobrando") para um mindset focado em **segurança, estabilidade e previsibilidade** (típico de um mercado mais maduro e incerto).
* **Objetivo Atendido:** Responde perfeitamente ao objetivo de investigar "como a mudança do modelo de crescimento exponencial para uma lógica orientada à eficiência e rentabilidade... afetou a atuação dos profissionais de dados".
* **Validação da Hipótese:** **Validação perfeita e contundente da hipótese.** A "profunda alteração" no perfil e nas expectativas é exatamente esta: a valorização de fatores de longo prazo e segurança ("Plano de Carreira", "Benefícios") em detrimento de fatores de crescimento e aprendizado de curto prazo ("Oportunidade de Aprendizado"). Esta é a materialização do impacto da transição de mercado no mindset dos profissionais.

--- 

### **Conclusão Geral para o Eixo 4**

A hipótese central do Eixo 4 é **fortemente confirmada por todas as evidências apresentadas.**

A transição de um mercado de crescimento acelerado para um de foco em eficiência não apenas mudou as empresas, mas **transformou fundamentalmente o que os profissionais de dados buscam em suas carreiras.**

O comportamento mais cauteloso (menos entrevistas) e a mudança de prioridades (mais foco em benefícios e carreira, menos em aprendizado imediato) são duas faces da mesma moeda. Eles demonstram que, diante de um cenário de maior instabilidade e "enxugamento", os profissionais de dados passaram a valorizar a segurança e a estrutura de longo prazo que um emprego pode oferecer. A era da "aventura" deu lugar à busca pela "previsibilidade".

---

<div id='Eixo_5'/>  

## Eixo 5

## Evolução da Formação Acadêmica por Arquétipo (2022-2024)

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/d3b5fab2-fb86-46cb-bd97-53a3f4ab463d" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/160788ef-3932-4113-bff8-5cc9b2b49139" />


## Distribuição de Senioridade por Arquétipo (2022-2024)

<img width="313" height="247" alt="image" src="https://github.com/user-attachments/assets/4d18da3a-afcc-4ba4-9677-6591a44e24ac" />


**Analise dos Resultados**

Estes gráficos descrevem a composição das equipes em termos de nível de experiência e background educacional.

* **Finalidade dos Gráficos:** Caracterizar a evolução do perfil dos profissionais de dados em Bancos e Fintechs, focando na distribuição de senioridade e na formação acadêmica, que são proxies para experiência e qualificação formal.
* **O que os Gráficos Mostram:**
    * **"Seniorização" das Equipes:** O gráfico de "Distribuição de Senioridade" mostra a tendência mais importante. Em ambos os setores, a faixa de profissionais **Júnior (azul claro) diminui** de 2022 para 2024. Em contrapartida, as faixas **Pleno e Sênior (tons de verde mais escuros) aumentam**. Nos Bancos, o crescimento da faixa Sênior é particularmente expressivo.
    * **Estabilidade na Formação:** Os gráficos de "Formação Acadêmica" mostram um perfil relativamente estável. A maioria dos profissionais possui Graduação/Bacharelado, seguido por Pós-graduação. Os Bancos consistentemente apresentam uma proporção ligeiramente maior de profissionais com Mestrado e Doutorado.
* **Importância para a Análise:** A "seniorização" é um achado fundamental. Ela reflete diretamente o impacto da transição de mercado (Eixo 4): com a pressão por eficiência e ROI, as empresas priorizaram profissionais mais experientes, capazes de entregar resultados imediatos, em detrimento de perfis juniores que demandam mais treinamento e tempo de maturação.
* **Objetivo Atendido:** Atende perfeitamente ao objetivo de "Como evoluiu o perfil dos profissionais... considerando aspectos como formação, senioridade...".
* **Validação da Hipótese:** **Valida fortemente** uma parte central da hipótese. A premissa de que os perfis se tornaram **"mais experientes"** é inegavelmente confirmada pela clara tendência de aumento na proporção de profissionais Plenos e, principalmente, Sêniores em detrimento dos Juniores.

## Evolução do Uso de Tecnicas (2022-2024)

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/97d631a7-e9e5-4e9f-8638-186494a50275" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/7bfb3055-42e7-415b-8503-131f3117fa63" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/6c482757-dc54-48c4-b145-c13569d0b85d" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/ad6accf3-5a4f-4224-b277-17bd86065788" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/316efe32-a4c3-4c99-a61a-ddf5569e23d0" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/a315ff3a-c059-46e7-af9c-c0d7bfffe66f" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/fb0ed4f7-430a-410d-9f71-c6d768fb64c2" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/8e2fb803-f147-4c82-8bc2-379bc84a0fb8" />


**Analise fos Resultados**

Este conjunto de gráficos de linha mostra a evolução do uso de diferentes técnicas de Machine Learning e estatística, revelando as áreas de especialização.

* **Finalidade dos Gráficos:** Mapear a evolução das competências técnicas em uso, identificando quais tipos de modelos e métodos ganharam ou perderam relevância em cada setor, para testar a hipótese de "especialização progressiva".
* **O que os Gráficos Mostram (Padrões Gerais):**
    * **O "V" de 2023:** Muitos gráficos mostram uma queda no uso de várias técnicas em 2023, seguida por uma recuperação ou mudança de rota em 2024. Isso sugere que 2023 foi um ano de reavaliação de ferramentas e estratégias em ambos os setores.
    * **Fintechs (Linha Azul): Foco em ROI e Fundamentos.** A tendência mais dramática é o **crescimento explosivo do uso de Regressão** de 2023 para 2024. Isso, combinado com o aumento no uso de "Métodos Estatísticos Clássicos", sugere uma forte especialização em modelos robustos, interpretáveis e diretamente ligados a resultados de negócio (crédito, propensão, LTV, etc.), que são cruciais em um cenário focado em lucratividade.
    * **Bancos (Linha Marrom): Foco em Especialidades Complexas.** Os Bancos demonstram um uso consistentemente mais alto e crescente de técnicas como **NLP** e **Redes Neurais/Árvores**. Isso aponta para uma especialização em problemas de grande escala e alta complexidade, como análise de sentimento de clientes, assistentes virtuais e detecção de fraudes sofisticadas.
* **Importância para a Análise:** Esta análise é crucial por mostrar que a "especialização" não foi um movimento homogêneo. Em vez de um setor copiar o outro, cada um aprofundou o uso das técnicas que melhor respondiam às suas novas prioridades estratégicas.
* **Objetivo Atendido:** Responde diretamente à questão sobre a evolução das "competências técnicas" e o protagonismo de áreas como "Machine Learning".
* **Validação da Hipótese:** **Confirma a hipótese de especialização, mas com uma nuance fundamental.**
    * A premissa de **"especialização progressiva"** e perfis **"mais técnicos"** é **confirmada**.
    * No entanto, a ideia de que os Bancos simplesmente "incorporaram" a tendência das Fintechs é refinada. Os dados mostram **caminhos de especialização diferentes e paralelos**:
        * **Fintechs** se especializaram em **eficiência e impacto rápido no negócio** (foco em Regressão).
        * **Bancos** se especializaram em **complexidade e escala** (foco em NLP e Redes Neurais).

## Composição da Equipe de Dados em Fintechs

<img width="834" height="690" alt="__results___72_0" src="https://github.com/user-attachments/assets/db1b1472-34cd-4eb0-9c4b-af3a3961698a" />
<img width="834" height="690" alt="__results___72_1" src="https://github.com/user-attachments/assets/adfafcb3-e70c-414b-a24b-81c20bfaee08" />



**Analise dos Resultados**

Os gráficos "Composição da Equipe de Dados em Bancos" e "...em Fintechs" são cruciais para entendermos a estrutura dos times.

* **Finalidade dos Gráficos:** Detalhar a evolução da composição dos times de dados, mostrando a proporção de cada cargo (Engenheiro de Dados, Cientista, Analista, etc.) e revelando as prioridades de contratação de cada setor.
* **O que os Gráficos Mostram:**
    * **Fundação de Engenharia nas Fintechs:** Nas Fintechs, os cargos de **Engenharia de Dados e Analytics Engineer** (tons de laranja mais escuros) representam uma parcela consistentemente grande da equipe ao longo dos três anos. Isso indica uma base de engenharia de dados já madura e estabelecida.
    * **Construção da Engenharia nos Bancos:** Nos Bancos, a tendência é de **crescimento visível nos cargos de Engenharia**. As faixas azuis correspondentes a **Data Engineer, Analytics Engineer e ML Engineer** se tornam mais espessas de 2022 para 2024. Isso mostra um investimento claro e crescente na construção de uma base de engenharia de dados robusta.
* **Importância para a Análise:** Este é um dos achados mais importantes do trabalho. Ele materializa a hipótese: os Bancos estão ativamente construindo as competências de engenharia que as Fintechs, por serem nativas digitais, desenvolveram primeiro.
* **Validação da Hipótese:** **Validação fortíssima.** A hipótese de que os Bancos incorporaram tendências das Fintechs a partir de 2023 é perfeitamente ilustrada aqui. O crescimento dos papéis de engenharia nos Bancos é a prova da "especialização progressiva" e da adoção de perfis mais técnicos, focados em "engenharia de dados e produtização de modelos".

## Evolução na Adoção de Ferramentas (2022-2024)

**Analise dos Resultados**

<img width="989" height="590" alt="__results___77_0" src="https://github.com/user-attachments/assets/f020e9c4-7b1c-4564-81a2-c325e38d5118" />
<img width="989" height="590" alt="__results___77_1" src="https://github.com/user-attachments/assets/58b8018c-8c6f-4d86-942d-bb718801b16f" />
<img width="989" height="590" alt="__results___77_2" src="https://github.com/user-attachments/assets/5fdc8824-fef3-41b3-8464-c96910a8fa38" />
<img width="989" height="590" alt="__results___77_3" src="https://github.com/user-attachments/assets/e1018034-60c4-4b3e-95bd-2cb7d7e37040" />
<img width="989" height="590" alt="__results___77_4" src="https://github.com/user-attachments/assets/60c21235-5ac6-4c2b-bfd2-4409d3dc0aad" />



**Ferramentas de Engenharia e Plataforma (Airflow, Databricks, Snowflake)**

* **Finalidade dos Gráficos:** Rastrear a adoção de ferramentas centrais de orquestração (Airflow) e de plataformas de dados (Databricks, Snowflake), o que revela as decisões estratégicas mais importantes na construção da infraestrutura de dados.
* **O que os Gráficos Mostram:**
    * **Databricks:** Adoção **explosiva e massiva nos Bancos**, saltando de ~22% para mais de 50% em três anos. Nas Fintechs, a adoção é muito menor e permaneceu estável.
    * **Snowflake:** Trajetória oposta. O crescimento é **muito mais acentuado nas Fintechs**, que mais do que triplicaram sua base de uso. Nos Bancos, o crescimento foi tímido.
    * **Airflow:** Uma divergência dramática. Enquanto o uso **despencou nos Bancos** (de 58% para 33%), ele **cresceu e se consolidou nas Fintechs**, que se tornaram o principal reduto da ferramenta.
* **Importância para a Análise:** Estes gráficos são a prova definitiva de que Bancos e Fintechs estão seguindo **filosofias arquiteturais completamente diferentes**.
    * Os **Bancos** estão claramente apostando em uma estratégia de **plataforma unificada e centralizada**, com o Databricks se tornando o padrão para engenharia e ciência de dados em escala. A queda do Airflow pode ser explicada pela substituição por orquestradores nativos do Databricks ou da nuvem (Azure Data Factory).
    * As **Fintechs** estão consolidando a arquitetura do **"Modern Data Stack"**, combinando as melhores ferramentas de cada categoria: Snowflake como o Data Warehouse/Platform, Airflow como o orquestrador open-source e DBT (como vimos anteriormente) para a transformação dos dados.
* **Validação da Hipótese:** **Confirma e detalha brilhantemente a hipótese de "especialização progressiva"**. A especialização não é só no perfil do profissional, mas na arquitetura inteira. A validação das sub-hipóteses de "engenharia de dados" e "produtização de modelos" fica evidente nas escolhas de ferramentas que sustentam esses processos.

**Ferramentas de Business Intelligence (Power BI, Looker)**

* **Finalidade do Gráfico:** Analisar a preferência por ferramentas de BI, que reflete não só a capacidade de visualização, mas também a forma como os dados são consumidos e integrados à cultura corporativa.
* **O que os Gráficos Mostram:**
    * **Power BI:** Uma clara história de **convergência e ultrapassagem**. Os **Bancos** tiveram um crescimento massivo na adoção (de 35% para 60%), superando as Fintechs em 2024.
    * **Looker:** Ferramenta com maior aderência e crescimento nas **Fintechs**. Nos Bancos, o uso é menor e está em declínio após um pico em 2023.
* **Importância para a Análise:** As escolhas de BI estão fortemente atreladas ao ecossistema corporativo. O domínio crescente do Power BI nos Bancos reflete sua profunda integração com o ambiente Microsoft (Azure, Office 365). A preferência por Looker nas Fintechs sugere uma cultura mais alinhada ao ecossistema Google (GCP) e a um perfil de uso mais técnico e focado em "data apps".
* **Validação da Hipótese:** Apoia a conclusão de que os caminhos de especialização são distintos, estendendo-se até a camada final de consumo dos dados.

## Quadrantes Estratégicos de Tecnologias

<img width="991" height="1011" alt="__results___80_0" src="https://github.com/user-attachments/assets/36809676-ecb8-4762-a237-d91bcae317d0" />

## Taxa de Adoção de Linguagens de Programação 

<img width="2190" height="940" alt="__results___82_0" src="https://github.com/user-attachments/assets/3519eac6-f5d2-43ab-a539-2bc333ab7765" />

**Analise dos Resultados**

Os gráficos de "Linguagens de Programação" e "Quadrantes Estratégicos" revelam o ecossistema tecnológico.

* **Finalidade dos Gráficos:** Mapear o kit de ferramentas (linguagens) e o posicionamento estratégico das tecnologias-chave, oferecendo um resumo do cenário tecnológico.
* **O que os Gráficos Mostram:**
    * **Linguagens:** **Python e SQL são soberanos** e universais, com adoção estável e altíssima em ambos os setores. São as commodities da área.
    * **Quadrantes Estratégicos:** Este gráfico é uma síntese genial.
        * **Território Fintech:** A tecnologia **DBT (Data Build Tool)** se destaca como exclusiva do universo Fintech. Isso reforça a maturidade da função de *Analytics Engineering* nesse setor.
        * **Commodities:** **AWS e Azure** são tecnologias dominantes e disputadas por ambos.
        * **Território Banco:** Nenhuma tecnologia moderna se destaca como exclusiva dos bancos, que ainda carregam ferramentas mais tradicionais como Oracle.
* **Importância para a Análise:** Confirma as diferentes maturidades do "Modern Data Stack". As Fintechs já estão consolidadas em ferramentas ágeis e específicas de engenharia analítica (DBT), enquanto os Bancos ainda estão na jornada de adoção das nuvens principais.
* **Validação da Hipótese:** **Reforça a validação.** A distinção clara no uso de ferramentas como DBT é mais uma evidência dos diferentes caminhos de especialização e da liderança das Fintechs na adoção de certas práticas de engenharia.

## Distribuição Salarial:São Paulo vs. Outros Estados

<img width="1189" height="790" alt="__results___85_0" src="https://github.com/user-attachments/assets/151fe6ca-7b2d-4139-8787-fbb2070cb640" />

**Analise dos Resultados**

* **Finalidade do Gráfico:** Comparar a estrutura de remuneração (mediana, quartis, distribuição) dos profissionais de dados em diferentes níveis de senioridade, contrastando o mercado de São Paulo com a média dos outros estados brasileiros.
* **O que o Gráfico Mostra:**
    * **Níveis Júnior e Pleno:** Nestes níveis, a diferença salarial é pequena. As caixas (intervalo interquartil) e as medianas (linha central) são muito próximas, indicando que os salários para profissionais em início de carreira e de nível intermediário são relativamente "nacionalizados", provavelmente um efeito da consolidação do trabalho remoto.
    * **Nível Sênior:** A diferença se torna **gritante e estatisticamente significativa**. Todo o boxplot de São Paulo (azul) está deslocado para cima em relação ao dos Outros Estados (rosa). A mediana salarial é substancialmente maior, e o teto (3º quartil e outliers) é muito mais alto.
* **Importância para a Análise:** Este gráfico é fundamental para entender as disparidades regionais e a dinâmica do mercado de talentos. Ele sugere que, embora o trabalho remoto tenha equalizado as oportunidades e salários na base da pirâmide, as posições mais estratégicas, complexas e de maior remuneração ainda estão concentradas em São Paulo.
* **Insight Principal:** Existe um claro **"Prêmio de Senioridade Paulista"**. O verdadeiro diferencial financeiro de atuar em São Paulo se manifesta no nível sênior, onde a proximidade com as matrizes das empresas, os projetos de maior complexidade e os centros de decisão resultam em uma valorização muito superior à do resto do país.

## Adoção de Copilot por Desenvolvedores 

<img width="1389" height="790" alt="__results___88_0" src="https://github.com/user-attachments/assets/ecfc6636-69a5-4066-a9da-c968a50dadc9" />

**Analise dos Resultados**

* **Finalidade do Gráfico:** Comparar a taxa de adoção de uma ferramenta de ponta (GitHub Copilot), que é um proxy para inovação e busca por produtividade, entre profissionais de diferentes áreas, contrastando São Paulo com outros estados.
* **O que o Gráfico Mostra:**
    * Em **todas as áreas de atuação** (Análise/BI, Engenharia, Ciência de Dados), os profissionais localizados em São Paulo (barras laranjas) apresentam uma **taxa de adoção de Copilot consistentemente maior** do que os profissionais de Outros Estados (barras verdes).
    * A diferença é mais acentuada nas áreas com maior adoção geral, como Análise de Dados/BI e Engenharia de Dados.
* **Importância para a Análise:** Este dado complementa o anterior. Ele indica que o ecossistema de São Paulo não é apenas um polo de melhores salários para sêniores, mas também um **polo de inovação e adoção tecnológica acelerada**. Empresas e profissionais em São Paulo parecem estar na vanguarda do uso de ferramentas que aumentam a produtividade e representam o estado da arte.
* **Insight Principal:** São Paulo funciona como um **"Hub de Inovação" (Early Adopter Market)**. Além de concentrar as posições de maior valor estratégico, o ecossistema paulista é mais dinâmico tecnologicamente, adotando novas ferramentas de forma mais rápida e intensa que o restante do Brasil.

## IA Generativa é uma Prioridade na Empresa?

<img width="989" height="590" alt="__results___90_0" src="https://github.com/user-attachments/assets/a2fb2947-9a55-465b-b9a1-12bd52fe11ee" />
<img width="1473" height="790" alt="__results___92_0" src="https://github.com/user-attachments/assets/b71a11b5-e7f3-478b-9a47-2983553a20ea" />


**Analise dos Resultados**

Estes gráficos medem a adoção de tecnologias de ponta.

* **Finalidade dos Gráficos:** Avaliar como cada setor está se posicionando em relação às novas fronteiras da IA.
* **O que os Gráficos Mostram:**
    * **IA Generativa e Copilot:** Os **Bancos aparecem como maiores adotantes de IA Generativa para desenvolvedores (Copilot)** (24,6% vs. 18,7%). Isso pode indicar um movimento "top-down" de grandes corporações para aumentar a produtividade. Nas prioridades gerais de IA Generativa, o cenário é mais equilibrado, com ambos os setores em fase de exploração.
    * **Visão Computacional:** Revela a divergência mais espetacular. Enquanto o uso **cai nos Bancos**, ele **explode nas Fintechs**, quase dobrando de 2022 para 2024.
* **Importância para a Análise:** O caso da Visão Computacional é um insight poderoso. Ele provavelmente reflete a especialização das Fintechs em processos de "Know Your Customer" (KYC), como validação de documentos e biometria facial para abertura de contas, uma aplicação de altíssimo valor de negócio.
* **Validação da Hipótese:** **Confirma a "especialização progressiva" de forma brilhante.** Mostra que as Fintechs estão usando sua base tecnológica madura para se especializar em nichos de aplicação de IA que resolvem problemas de negócio diretos e imediatos.


---

### **Conclusão Gerak do Eixo 5**

Integrando todos os gráficos, a hipótese central do Eixo 5 — de que o setor financeiro passou por uma especialização progressiva, com perfis mais técnicos e experientes ganhando protagonismo — é **massivamente confirmada e profundamente detalhada.**

A análise revela a formação de **dois ecossistemas tecnológicos distintos**, cada um com sua própria lógica, refletindo as prioridades estratégicas de Bancos e Fintechs.

#### **O Ecossistema dos Bancos: A Maratona da Integração em Escala**

* **Perfil:** Equipes mais **sêniores**, com um crescimento visível na contratação de **Engenheiros de Dados e ML**.
* **Estratégia de TI:** Centralização e padronização em **plataformas unificadas e integradas**.
* **As Ferramentas-Chave:** Adoção massiva de **Databricks** como plataforma central, **Power BI** como ferramenta de BI padrão (ecossistema Microsoft) e aprofundamento em técnicas de IA complexas como **NLP e Redes Neurais** para alavancar sua escala. Adoção "top-down" de ferramentas de produtividade como o **Copilot**.

#### **O Ecossistema das Fintechs: Sprints de Inovação de Nicho**

* **Perfil:** Equipes com uma forte e madura base de **Engenharia de Dados e Analytics Engineering**.
* **Estratégia de TI:** Arquitetura **"best-of-breed"** (o melhor de cada classe), modular e ágil, baseada no **"Modern Data Stack"**.
* **As Ferramentas-Chave:** Combinação poderosa de **Snowflake + Airflow + DBT**. Preferência por ferramentas developer-centric como **Looker**. Especialização técnica em modelos de ROI rápido (**Regressão**) e em nichos de altíssimo valor de negócio (**Visão Computacional** para KYC).
  
---

<div id='Indução_de_modelos'/>  

## Indução do Modelo

---

<div id='Resultados'/>  

## Resultados:

--- 

<div id='Conclusão'/>  

## Conclusão:
# Conclusão Final


### **Conclusão Geral: A Bifurcação Estratégica e a Maturação do Mercado de Dados Brasileiro**

A análise longitudinal dos dados de 2022 a 2024 oferece uma resposta clara e multifacetada ao problema proposto: a disputa entre a "Fintechzação" dos Bancos e a "Bancarização" das Fintechs não apenas reconfigurou o mercado financeiro, mas forjou **dois ecossistemas de trabalho distintos e cada vez mais especializados para os profissionais de dados**. Se em 2022 o setor parecia uma única corrida pelo ouro, em 2024, ele se assemelha a um campeonato com modalidades diferentes, cada uma com seus próprios atletas, equipamentos e estratégias.

A seguir, estão as principais respostas e conclusões que emergem da junção de todas as análises.

#### **1. A Grande Correção do Mercado: O Fim da Euforia e a Busca por Segurança**

A primeira grande resposta que a análise oferece é que a **"virada de mercado" de 2023 foi o evento catalisador que encerrou a era de crescimento a qualquer custo e impôs uma nova realidade**. Isso se manifestou em duas frentes interligadas:

* **Na Remuneração (Eixo 1):** A agressividade salarial das Fintechs, impulsionada por capital de risco abundante, deu lugar a uma maior racionalidade. Os Bancos, por sua vez, reagiram estrategicamente, investindo para atrair talentos sêniores. O resultado foi uma **convergência salarial**, especialmente nos níveis júnior e pleno, diminuindo a arbitragem salarial que existia entre os setores.
* **No Comportamento Profissional (Eixo 4):** A incerteza econômica e os "enxugamentos" mudaram o mindset do profissional de dados. A busca frenética por novas oportunidades diminuiu, e os critérios de escolha de emprego se alteraram profundamente. A "oportunidade de aprendizado" perdeu espaço para fatores tangíveis de segurança, como **benefícios e plano de carreira**. A era da aventura deu lugar à busca por estabilidade.

#### **2. A Nova Guerra por Talentos: A "Seniorização" dos Times**

A convergência salarial não significou o fim da disputa por talentos; ela apenas mudou de foco. A análise do perfil profissional (Eixo 5) mostra que ambos os setores passaram por uma intensa **"seniorização" de suas equipes**. A proporção de profissionais juniores diminuiu, enquanto a de plenos e sêniores aumentou.

Isso revela uma nova estratégia de contratação: em um cenário que exige eficiência e ROI, as empresas priorizaram profissionais experientes, capazes de gerar impacto imediato. A guerra por talentos agora é travada nos escalões mais altos, onde as Fintechs, mesmo com o cinto mais apertado, ainda oferecem um "prêmio" para segurar seus especialistas sêniores (Eixo 1).

#### **3. A Bifurcação Estratégica: Dois Caminhos para a Especialização**


A conclusão mais profunda da análise é que, para responder a desafios de gestão distintos (Eixo 3), Bancos e Fintechs seguiram **caminhos de especialização tecnológica radicalmente diferentes**. Não se trata mais de um setor "atrasado" e outro "avançado", mas de duas filosofias que moldam o perfil, as ferramentas e as competências de seus profissionais.

* **O Ecossistema dos Bancos: A Maratona da Integração em Escala**
    * **Desafio:** Mudar a cultura, modernizar sistemas legados e garantir a qualidade dos dados em um ambiente complexo.
    * **Estratégia:** Centralização e padronização em plataformas unificadas e robustas.
    * **Perfil Técnico:** Adoção massiva de **Databricks** e **Power BI** (atrelado ao ecossistema Microsoft), com foco em **NLP** e **Redes Neurais** para resolver problemas de grande escala e um investimento crescente na construção de uma forte base de **Engenharia de Dados**.

* **O Ecossistema das Fintechs: Sprints de Inovação de Nicho**
    * **Desafio:** Escalar com agilidade, gerenciar a complexidade do crescimento e manter a cultura de inovação.
    * **Estratégia:** Utilização de uma arquitetura modular e flexível, o "Modern Data Stack".
    * **Perfil Técnico:** Domínio da combinação **Snowflake + DBT + Airflow**. Especialização em modelos de ROI rápido como **Regressão** e em nichos de altíssimo valor, como **Visão Computacional** para processos de KYC.

### **O Que Podemos Tirar Disso? As Respostas Finais**

1.  **Para o Profissional de Dados:** A escolha entre um Banco e uma Fintech deixou de ser apenas sobre salário ou estabilidade. É uma **decisão estratégica de carreira sobre em qual ecossistema tecnológico se especializar**. O profissional que prospera em um ambiente Databricks/Azure não é necessariamente o mesmo que prospera em um ambiente Snowflake/DBT/GCP. A especialização tornou-se fundamental, e a portabilidade de competências entre os dois mundos não é mais trivial.

2.  **Para as Empresas:** A competição por talentos agora é sobre **"fit" cultural e tecnológico**. Os Bancos devem vender sua capacidade de investimento em grandes plataformas e a oportunidade de resolver problemas de escala massiva. As Fintechs devem vender sua agilidade, o uso de tecnologias de ponta em nichos específicos e a capacidade de gerar impacto direto no negócio. A proposta de valor de cada um ficou mais clara e distinta.

3.  **Para o Mercado Brasileiro:** A transformação do setor financeiro resultou na **maturação e sofisticação do mercado de dados como um todo**. A existência de dois ecossistemas paralelos, mas igualmente avançados, é um sinal de um mercado saudável e em evolução, com diferentes polos de inovação que se retroalimentam e elevam o nível técnico geral do país. A "disputa" entre Bancos e Fintechs, no fim das contas, enriqueceu e diversificou as oportunidades para quem trabalha com dados no Brasil.

---

# Agradecimentos 

Nós, Thiago Santos, Pedro Dias e Enzo Gripp, gostaríamos de expressar nossa sincera gratidão a todos que dedicaram seu tempo para visualizar, acompanhar e avaliar nosso projeto. Cada feedback e interação foi essencial para nosso crescimento e aprendizado ao longo desse processo.

Em especial, deixamos um profundo e merecido agradecimento ao nosso mentor e professor Hayala Curto, cuja orientação, apoio constante e incentivo foram fundamentais para que este trabalho se concretizasse. Sem sua dedicação e confiança, certamente não teríamos chegado até aqui.

Nosso muito obrigado!

---

<div id='REFERÊNCIAS'/>  

## Referências:

**Base de Dados:**

[1] Kaggle: State of Data Brazil-(2024-2025), O maior mapeamento do mercado brasileiro de dados e AI [Data Hackers + Bain]. Disponível em: https://www.kaggle.com/datasets/datahackers/state-of-data-brazil-20242025. Acesso em: 07 jul. 2025.

[2] Kaggle: State of Data Brazil-2023, o mapeamento mais completo do mercado brasileiro de dados [Data Hackers + Bain]. Disponível em: https://www.kaggle.com/datasets/datahackers/state-of-data-brazil-2023/data. Acesso em: 07 jul. 2025.

[3] Kaggle: State of Data Brazil-2023, o mapeamento mais completo do mercado brasileiro de dados [Data Hackers + Bain]. Disponível em: https://www.kaggle.com/datasets/datahackers/state-of-data-2022.  Acesso em: 07 jul. 2025.

**Pesquisa:**

[1] Veja: Número de Fintech's no Brasil cresceu 77% desde 2020, segundo levantamento  Disponível em:https://veja.abril.com.br/coluna/radar-economico/numero-de-Fintech's-no-brasil-cresceu-77-desde-2020-segundo-levantamento. Acesso em: 07 jul. 2025.

[2] Banco Central do Brasil: Fintech's . Disponível em: https://www.bcb.gov.br/estabilidadefinanceira/Fintech's. Acesso em: 07 jul. 2025.

[3] BBCB: Banking on the future.  Disponível em: https://www.bbc.com/storyworks/control-to-customise/banking-on-the-future. Acesso em: 07 jul. 2025.

[4] Fluid Blog Dock: Fintechzação: como empresas estão se tornando Fintech's e transformando o mercado de banking e pagamentos.  Disponível em: https://dock.tech/fluid/blog/financeiro/fintechzacao/#:~:text=A%20fintechza%C3%A7%C3%A3o%20envolve%20a%20incorpora%C3%A7%C3%A3o,investimentos%20diretamente%20aos%20seus%20clientes. Acesso em: 07 jul. 2025.



---

<div id='APÊNDICES'/>  

## APÊNDICES:
