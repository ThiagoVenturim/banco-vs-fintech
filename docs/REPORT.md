# A Fusão Invisível no Mercado Financeiro Brasileiro

---

_**Integrantes:**_
* Enzo Alves Barcelos Gripp, (eabgripp@sga.pucminas.br)
* Pedro Dias Soares, (pedrosoares@gmail.com)
* Thiago Domingos Venturim Ribeiro dos Santos, (thiagodomingosventutim@gmail.com)

**Resumo:**

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

---

<div id='Eixo_1'/>  

## Eixo 1: Remuneração e Valorização Profissional.

### Distribuição Anual (2022-2024):

Os gráficos comparativos anuais mostraram a porcentagem de profissionais em cada faixa salarial. O objetivo era identificar padrões consistentes e diferenças estruturais. Por exemplo, se um tipo de empresa concentra mais profissionais em faixas salariais mais baixas ou mais altas.

<img width="1247" height="790" alt="download" src="https://github.com/user-attachments/assets/ae2c2fe1-b663-49e0-ac73-860f30fa8124" />
<img width="1247" height="790" alt="download" src="https://github.com/user-attachments/assets/d5c24468-1b39-4b71-94f3-6c2b4dfcd303" />
<img width="1247" height="790" alt="download" src="https://github.com/user-attachments/assets/ce8ea154-a28e-425d-88cc-9239e7d107ec" />


**Analise do Resultado**

Observando os gráficos de "Distribuição Salarial Comparativa" (2022, 2023 e 2024), notamos um padrão consistente:

* Bancos (Grande Porte): A maior concentração de profissionais (o pico dos gráficos) está consistentemente na faixa de R$ 8.001 a R$ 12.000. Em 2023 e 2024, mais de 26% dos respondentes de bancos se encontram nessa faixa. Isso sugere que este é o "coração" da força de trabalho dos bancos, provavelmente composto por muitos cargos de nível pleno e sênior inicial.

* Fintechs (Pequeno/Médio Porte): A distribuição é mais espalhada. Embora também tenham uma concentração relevante na faixa de R$ 8.001 a R$ 12.000, as fintechs mostram uma porcentagem maior de funcionários em faixas salariais mais altas (acima de R$ 16.000) quando comparadas aos bancos.



### Variação Ano a Ano: 

A análise da variação percentual anual: (2023 vs. 2022) revelou a dinâmica do mercado. Os gráficos evidenciaram quais faixas salariais tiveram o maior crescimento ou queda na representatividade de profissionais, indicando tendências como “achatamento” ou “valorização” de certos níveis de remuneração em bancos e Fintech's.

<img width="1247" height="790" alt="image" src="https://github.com/user-attachments/assets/8deef9e9-b75e-4b60-8ef3-4e31aa048867" />
<img width="1247" height="790" alt="image" src="https://github.com/user-attachments/assets/e844080b-5e70-4836-b5a6-3abaec018731" />

**Analise dos Resultados**

Os gráficos de "Variação Anual" mostram o dinamismo do mercado:

* Em 2023: As fintechs mostraram um crescimento explosivo na faixa de R$ 25.001 a R$ 30.000 (+213%), indicando uma forte movimentação para contratação de especialistas e líderes. Em contrapartida, diminuíram a presença em faixas mais baixas.

* Em 2024: A tendência se intensifica nos salários mais altos. As fintechs apresentam um crescimento massivo de +110% na faixa acima de R$ 40.000. Ao mesmo tempo, praticamente eliminaram (-100%) a faixa salarial mais baixa ("Menos de R$ 1.000/mês"). Os bancos, por sua vez, mostraram um aumento notável de +70% na faixa de R$ 25.001 a R$ 30.000, talvez como uma reação para competir pelo mesmo talento que as fintechs buscaram no ano anterior.


### Perfil Médio Consolidado (2022-2024):

Ao calcular a média da distribuição dos três anos, foi possível visualizar um "retrato" geral e estável do perfil salarial. A análise dos dados (perfil_medio_df) sugere que:

<img width="1778" height="890" alt="download" src="https://github.com/user-attachments/assets/a96474ac-c4fb-4fc7-a5b4-ff36920df980" />


**Analise dos Resultados**

* Perfil do Banco: Foco no Meio da Carreira. Os bancos possuem uma estrutura salarial que privilegia e concentra a maior parte de seus profissionais em faixas de remuneração intermediárias. É um modelo mais padronizado e com menor variação salarial entre os cargos.

* Perfil da Fintech: Estrutura mais Flexível e Polarizada. As fintechs demonstram uma estratégia de remuneração mais distribuída. Elas comportam uma base maior de profissionais em faixas de entrada ou de menor senioridade, mas, ao mesmo tempo, são mais agressivas na remuneração de talentos de alto nível e especialistas, pagando salários mais competitivos nas faixas superiores.



### Distribuição Salarial por Senioridade e Arquétipo

Esta análise focou nos salários mais altos (o valor que 75% dos profissionais ganham a menos que ele), revelando o potencial de ganho em cada nível. O gráfico de barras comparativo permitiu visualizar o "teto" salarial mais comum para os talentos mais bem pagos em bancos e Fintech's, sendo uma métrica importante para avaliar a competitividade na atração de profissionais sêniores.

<img width="1189" height="790" alt="download" src="https://github.com/user-attachments/assets/195c85af-08fc-487e-9b46-047f1e4c8f78" />
<img width="1389" height="889" alt="image" src="https://github.com/user-attachments/assets/53ec14ff-c12b-4cad-b5da-e35e914d283f" />


**Analise dos Resultados**


 Os gráficos "Salário do 3º Quartil (p75)" e "Distribuição Salarial Completa por Senioridade" são os mais reveladores:

* Nível Júnior: Bancos tendem a pagar mais. O salário mediano e o 3º quartil (R$ 7.000) são visivelmente maiores para os profissionais júnior em bancos do que em fintechs (p75 de R$ 5.000).

* Nível Pleno: A remuneração é extremamente competitiva e praticamente idêntica entre os dois modelos. O 3º quartil para ambos é de R$ 10.000, e as medianas no gráfico de box plot também são muito próximas.

* Nível Sênior: Aqui a situação se inverte drasticamente. Fintechs pagam significativamente mais para profissionais sênior. O 3º quartil (p75) em fintechs atinge R$ 18.000, enquanto nos bancos fica em R$ 14.000. O box plot confirma isso, mostrando uma mediana e um teto salarial muito mais altos para sêniores em fintechs.




 <div id='Eixo_2'/>  

 ### Eixo 2 — Adoção Tecnológica e Estratégias de Infraestrutura
 
Neste eixo, a análise se aprofunda na infraestrutura tecnológica, investigando como bancos e Fintech's adotam plataformas de nuvem. O objetivo é medir a maturidade digital, a evolução da modernização e as estratégias de nuvem (incluindo multicloud e a persistência de sistemas legados on-premise).

* 1. Taxa de Adoção por Plataforma (AWS, Azure, GCP, On-Premise)

|ano_base|	arquétipo_tamanho	|			  cloud_usada_aws	|cloud_usada_gcp|	cloud_usada_azure	|cloud_usada_on_premise|
|------|----------------------|------------------------|-----------|--------------|------------------|
|2022	 | Grande Porte (Provável Banco)|	54.96|	16.15|	12.75|	NaN|
|      | Pequeno/Médio Porte (Provável Fintech)|	46.70	|21.98	|13.74|	NaN|
|2023	 | Grande Porte (Provável Banco)	|18.72	|25.69	|64.04|	15.41|
|      | Pequeno/Médio Porte (Provável Fintech)	|23.55|	27.80	|51.74|	10.42|
|2024  |Grande Porte (Provável Banco)	|64.41	|14.80|	29.76	|11.34|
|      |Pequeno/Médio Porte (Provável Fintech)	|55.56	|23.87	|24.69	|11.11|



Metodologia: A taxa de adoção foi calculada medindo a porcentagem de profissionais que utilizam cada uma das principais plataformas de nuvem (AWS, GCP, Azure), além de soluções on-premise (servidores locais). Isso foi feito agrupando os dados por ano e arquétipo (Banco vs. Fintech).

Resultados e Interpretação: A análise da tabela adoption_rates e do gráfico de evolução revela tendências significativas e algumas anomalias:

AWS e Azure como Líderes: Há uma disputa clara pela liderança entre AWS e Azure. Em 2022 e 2024, a AWS aparece com maior taxa de adoção, especialmente em grandes bancos.

Anomalia em 2023: Os dados de 2023 mostram uma queda abrupta na adoção de AWS e um pico massivo na de Azure, especialmente em bancos (64%). Isso pode indicar uma mudança real no mercado naquele ano ou, mais provavelmente, uma alteração na formulação da pergunta da pesquisa, o que pode ter influenciado as respostas. Essa volatilidade sugere cautela ao comparar diretamente as taxas de adoção de plataformas individuais ano a ano.

Adoção de GCP: O Google Cloud Platform (GCP) consistentemente apresenta uma maior taxa de adoção em Fintech's do que em bancos, sugerindo que pode ser uma opção preferencial para empresas mais novas e ágeis.

Sistemas On-Premise: A presença de infraestrutura on-premise diminuiu ligeiramente nos bancos (de 15.4% em 2023 para 11.3% em 2024), indicando um lento, mas contínuo, processo de migração para a nuvem.

* 2. Evolução da Estratégia Multicloud
  
![image](https://github.com/user-attachments/assets/fe60d40b-4ca9-449b-a5d1-5cbe6a8ffeff)

Metodologia: Foi criada uma métrica para identificar a adoção de uma estratégia multicloud, considerando como tal os profissionais que utilizam duas ou mais das três principais plataformas (AWS, Azure, GCP). Essa abordagem é estratégica para evitar dependência de um único fornecedor (vendor lock-in) e otimizar custos.

Resultados e Interpretação: O gráfico de linha sobre a adoção multicloud mostra uma tendência mais estável e clara. Ele mede a maturidade estratégica em vez da preferência por uma única plataforma. A visualização gerada permite concluir qual dos arquétipos (bancos ou Fintech's) está avançando mais rapidamente na adoção de uma infraestrutura de nuvem diversificada e resiliente. Tipicamente, espera-se um crescimento contínuo nesta métrica para ambos os segmentos.

* 3. Segmentação de Perfis de Liderança
 
![image](https://github.com/user-attachments/assets/487e108d-9816-418a-aa1e-bdbaf1b9c4eb)

Metodologia: Como um passo preparatório para análises futuras, o conjunto de dados foi filtrado para isolar os profissionais que atuam como gestores ou líderes (atua_como_gestor).

Resultado: Foi criado um novo dataframe, df_lideres, contendo 460 gestores, de um total de 2.750 profissionais no setor financeiro.

Essa segmentação é de grande valor estratégico por permitir que as próximas análises comparem diretamente as ferramentas, desafios, salários e decisões tecnológicas do ponto de vista de quem toma as decisões em relação à equipe técnica, oferecendo insights muito mais profundos sobre a governança de dados e a estratégia tecnológica nas organizações.

<div id='Eixo_3'/>  

### Eixo 3
  
<div id='Eixo_4'/> 

### Eixo 4
  
<div id='Eixo_5'/>  

### Eixo 5
  
---

<div id='Indução_de_modelos'/>  

## Indução do Modelo

---

<div id='Resultados'/>  

## Resultados:

--- 

<div id='Conclusão'/>  

## Conclusão:

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
