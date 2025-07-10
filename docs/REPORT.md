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

[8. ANÁLISE EXPLORATÓRIDA DOS DADOS](#Análise_exploratórida_dos_dados)

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

Nos últimos dez anos, o Brasil tem vivenciado um verdadeiro ponto de inflexão em seu sistema financeiro — uma transformação profunda impulsionada por avanços tecnológicos e por reformas regulatórias estratégicas. Durante décadas, a “Bancarização” foi a principal métrica de inclusão financeira no país, com foco em integrar a população ao sistema bancário tradicional por meio da expansão de agências, contas correntes e produtos convencionais. No entanto, um novo fenômeno emergiu e passou a redefinir as regras do jogo: a “Fintechzação”.

O lançamento do PIX, em 2020, pelo Banco Central, foi um divisor de águas. Essa tecnologia de pagamentos instantâneos não apenas democratizou o acesso a transações financeiras, como também nivelou o campo competitivo. Fintechs — com seu DNA digital, foco em experiência do usuário e cultura orientada por dados — ganharam protagonismo e passaram a competir diretamente com bancos tradicionais em escala nacional.

Esse novo cenário desencadeou uma dinâmica inédita:

* A Ascensão das Fintechs: Empresas nativamente digitais conquistaram rapidamente milhões de clientes, muitos dos quais anteriormente desbancarizados ou subatendidos. Elas reinventaram experiências de crédito, investimento e pagamento, tornando-as mais acessíveis, rápidas e intuitivas.

* A Reação dos Incumbentes: Diante da concorrência crescente, os grandes bancos aceleraram sua própria transformação digital. Investiram pesadamente em tecnologia, criaram estruturas ágeis — como seus próprios bancos digitais — e modernizaram seus sistemas legados. Nesse processo, a “bancarização” deixou de significar apenas inclusão no sistema bancário e passou a abranger também a digitalização de seus próprios serviços e clientes.

No centro dessa revolução está o dado. Hoje, a disputa por clientes, a personalização do crédito, a prevenção de fraudes e a criação de produtos inovadores são travadas em um território comum: a análise de dados, o Machine Learning e a Inteligência Artificial.

É exatamente nesse contexto que nossa pesquisa se insere. Apesar da ampla cobertura midiática sobre a transformação do setor financeiro, ainda são raras as análises que focam em quem realmente executa essa mudança: os profissionais de dados. A série histórica da pesquisa **State of Data Brazil**, de 2022 a 2024, oferece uma oportunidade ímpar de examinar essa transformação pela ótica dos dados — e das pessoas que os dominam.

Com base nessas bases, nossa investigação busca mapear a evolução das carreiras, remunerações, ferramentas e desafios dos profissionais de dados, explorando como esses aspectos se comportam diante da crescente convergência (e competição) entre a agilidade das fintechs e a escala dos bancos tradicionais em seu processo de digitalização.

---

<div id='Problema'/>  

## Problema:

O setor financeiro brasileiro está em meio a uma revolução digital, marcada pela disputa acirrada entre a agilidade das fintechs ("Fintechzação") e a escala dos bancos tradicionais ("Bancarização").

O _problema_ é que, embora essa transformação seja visível do ponto de vista do mercado e do consumidor, seu impacto real sobre o capital humano que a executa — os profissionais de dados — permanece amplamente desconhecido e sem dados estruturados.

---

<div id='Pergunta_Direcionada_a_Dados'/> 

## Perguntas Direcionada a Dados:

A partir das bases da pesquisa State of Data Brazil dos anos 2022, 2023 e 2024, estruturamos esta análise com base em perguntas orientadas a dados, cada uma guiada por hipóteses que serão validadas ou refutadas com evidências quantitativas. O objetivo é compreender como a disputa entre Bancos Tradicionais e Fintechs tem moldado o cenário profissional da área de dados no Brasil — em termos de remuneração, infraestrutura tecnológica, desafios de liderança e transformações no perfil dos profissionais.

**Eixo 1 — Remuneração e Valorização Profissional**

* Pergunta-chave:
Como a mediana salarial dos profissionais de dados evoluiu comparativamente entre Bancos Tradicionais (associados à "Bancarização") e Fintechs (associadas à "Fintechzação") entre 2022 e 2024?

* Hipótese:
Em 2022, impulsionadas pela euforia do ecossistema de startups e pela ampla disponibilidade de capital de risco, as fintechs tenderam a oferecer salários mais agressivos para atrair talentos qualificados. Acreditamos que, com a virada de mercado observada a partir de 2023 — marcada pela maior exigência de rentabilidade e pelo enxugamento de quadros —, essa vantagem salarial foi reduzida. Nossa hipótese é que, neste novo cenário, os bancos tradicionais reagiram, ajustando suas faixas salariais para atrair e reter profissionais sêniores e estratégicos, promovendo uma convergência salarial entre os dois setores.

**Eixo 2 — Adoção Tecnológica e Estratégias de Infraestrutura**

* Pergunta-chave:
Qual foi a evolução na preferência por provedores de nuvem (AWS, Azure, GCP) entre Bancos e Fintechs, e como essa escolha reflete suas respectivas estratégias de mercado e posicionamento tecnológico?

* Hipótese:
Apesar da imagem tradicionalmente associada à rigidez dos bancos, nossa hipótese é que essas instituições aumentaram a adoção da AWS para iniciativas voltadas à inovação, dados e transformação digital. Por outro lado, as fintechs, à medida que amadurecem e passam a lidar com demandas de escalabilidade e custos, migraram para ambientes multicloud, ampliando sua adoção de Azure (pela integração com serviços corporativos) e GCP (pela eficiência em Big Data e Machine Learning). A distribuição por provedor, portanto, poderá revelar indícios estratégicos da maturidade tecnológica de cada segmento.

**Eixo 3 — Desafios de Liderança e Gestão**

* Pergunta-chave:
Quais foram os principais desafios de gestão relatados por líderes de dados em Bancos e Fintechs entre 2022 e 2024, e como essas dificuldades se diferenciaram entre os dois modelos de organização?

* Hipótese:
Esperamos identificar padrões distintos de desafios organizacionais. A hipótese é que líderes em fintechs reportaram mais frequentemente questões relacionadas à escalabilidade de times, gestão do crescimento acelerado, e estruturação de processos em ambientes ainda em consolidação. Já os líderes de bancos devem ter apontado como principais obstáculos a mudança de cultura organizacional, a modernização de sistemas legados, e as restrições impostas pela burocracia interna. Essa diferença reflete as prioridades e maturidades distintas desses ambientes no enfrentamento de transformações digitais.

**Eixo 4 — Impacto da Transição de Mercado na Atuação Profissional**

* Pergunta-chave Principal:
Como a transição do mercado entre 2023 e 2024 — de um ciclo de crescimento acelerado para um cenário de foco em eficiência e lucratividade — impactou a atuação dos profissionais de dados no setor financeiro?

* Hipótese Geral:
Acreditamos que essa inflexão no ambiente macroeconômico e no setor de tecnologia, marcada por cortes de investimento, reestruturações e maior pressão por retorno financeiro, alterou profundamente o perfil, as ferramentas e as expectativas dos profissionais de dados no setor bancário e nas fintechs. Para validar essa hipótese, exploraremos três subdimensões:

**Eixo 5 — Perfil Profissional dos Cientistas de Dados no Setor Financeiro**

* Pergunta-chave Principal:
Como evoluiu o perfil dos profissionais de dados atuando em bancos e fintechs entre 2022 e 2024, considerando aspectos como formação, senioridade, áreas de atuação e competências técnicas?

* Hipótese Geral:
Nos últimos três anos, o setor financeiro passou por transformações estruturais que impactaram diretamente a composição e as exigências em torno dos profissionais de dados. Nossa hipótese é que houve uma especialização progressiva, com perfis mais técnicos, multidisciplinares e experientes ganhando protagonismo, especialmente em áreas críticas como Machine Learning, engenharia de dados e produtização de modelos. Essa tendência teria se acentuado nas fintechs até 2022, mas passou a ser incorporada também pelos bancos a partir de 2023, com a aceleração da digitalização.

---

<div id='Objetivo'/>  

## Objetivo Geral:

O presente estudo tem como objetivo central analisar comparativamente a evolução e as diferenças estruturais no perfil profissional, nas faixas de remuneração, nas tecnologias adotadas e nos desafios enfrentados por profissionais de dados atuantes nos ecossistemas da chamada "Fintechzação" (empresas de tecnologia financeira) e da "Bancarização" digitalizada (instituições financeiras tradicionais) no Brasil.

A partir de uma abordagem quantitativa e longitudinal, o estudo utilizará os microdados das pesquisas State of Data Brazil referentes aos anos de 2022, 2023 e 2024, visando fornecer um panorama fundamentado em evidências sobre o impacto dessas duas forças concorrentes — e cada vez mais convergentes — na dinâmica do mercado de trabalho em ciência de dados no setor financeiro.

### Objetivos Específicos
Para viabilizar a consecução do objetivo geral, serão perseguidos os seguintes objetivos específicos:

* Analisar a evolução da remuneração
  * Quantificar e comparar a mediana salarial dos profissionais de dados atuantes em bancos e fintechs ao longo dos anos de 2022 a 2024.
  *  Identificar se a diferença de remuneração entre os setores aumentou, reduziu ou se estabilizou, à luz das mudanças macroeconômicas e da maturação das estratégias digitais no período.

* Investigar a adoção tecnológica
  * Mapear as tendências de uso dos principais provedores de nuvem (AWS, Azure e GCP) por setor.
  * Verificar se as escolhas tecnológicas adotadas refletem diferentes níveis de maturidade, estratégias de escalabilidade, compliance e inovação entre bancos e fintechs.

* Comparar os desafios de liderança e gestão
  * Identificar os principais desafios relatados por líderes e gestores de dados em ambos os setores.
  * Analisar como esses desafios evoluíram no período e em que medida refletem características organizacionais distintas, como burocracia, escalabilidade ou transformação cultural.

* Avaliar o impacto da transição de mercado (2023–2024)
  * Investigar como a mudança do modelo de crescimento exponencial para uma lógica orientada à eficiência e rentabilidade (foco em ROI) afetou a atuação dos profissionais de dados.
  *Analisar variações no perfil de contratação (com ênfase na senioridade), na valorização de competências técnicas, na percepção de estabilidade profissional e nas estratégias de carreira adotadas pelos profissionais em bancos e fintechs.

---

<div id='Justificativas'/>  
  
## Justificativas:

justificativa deste projeto se baseia em sua alta relevância estratégica e originalidade. Para os profissionais de dados, a análise funcionará como um guia de carreira 
aseado em dados, auxiliando em decisões sobre salários, habilidades e qual setor seguir. Para as empresas, fornecerá um diagnóstico competitivo sobre o mercado de talentos,
essencial para estratégias de contratação e retenção.

Sua originalidade está na análise comparativa e evolutiva (2022-2024), que revela tendências reais ao invés de um retrato estático. Por fim, a pesquisa é extremamente
oportuna, pois analisa o impacto da recente transição de mercado, fornecendo um mapa atualizado e necessário para toda a comunidade de dados brasileira.

---

<div id='Público_alvo'/>  

## Público_alvo

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
Criação de uma Variável Derivada: Um desafio identificado foi a ausência de uma distinção clara entre bancos tradicionais e fintechs na base de dados. Para contornar isso, foi criada uma nova variável categórica, arquétipo_tamanho, com base na hipótese de que o número de funcionários poderia servir como um critério de distinção:

Grande Porte (Provável Banco): Empresas com mais de 1.000 funcionários.

Pequeno/Médio Porte (Provável Fintech): Empresas com até 1.000 funcionários.

Essa nova coluna permitiu a segmentação e a análise comparativa entre esses dois perfis de empresas dentro do setor financeiro.

---

<div id='Análise_exploratórida_dos_dados'/>  

## Análise Exploratórida dos Dados:

### Eixo 1: Remuneração e Valorização Profissional.

Análise Exploratória: Remuneração no Setor Financeiro (Bancos vs. Fintechs)
Após a preparação dos dados, a análise exploratória foi iniciada para extrair insights sobre as dinâmicas de remuneração. O foco foi comparar empresas de grande porte (assumidas como bancos tradicionais) e de pequeno/médio porte (assumidas como fintechs) no setor financeiro brasileiro entre 2022 e 2024.

* 1. Transformação de Dados para Análise Salarial
Para viabilizar a análise quantitativa, a variável categórica faixa_salarial foi transformada em formatos mais adequados:

Criação da Coluna salario_numerico: As faixas salariais foram convertidas para valores numéricos representativos (ex: "de R$ 8.001/mês a R$ 12.000/mês" tornou-se 10000). Essa etapa foi crucial para permitir cálculos estatísticos como média, mediana e quartis. A verificação indicou 36 valores nulos, sugerindo que algumas faixas salariais nos dados não estavam no mapeamento inicial e precisariam de tratamento ou remoção para cálculos específicos.

Ordenação da Faixa Salarial: Foi criada a coluna faixa_salarial_ordenada do tipo categórico ordenado. Isso garantiu que as visualizações respeitassem a ordem lógica das faixas, do menor para o maior salário, evitando erros de interpretação em gráficos.

* 2. Análise da Distribuição Salarial
Com os dados devidamente formatados, a análise se concentrou em como os salários se distribuíam entre os dois arquétipos de empresa ao longo dos anos.

### Distribuição Anual (2022-2024):

Os gráficos comparativos anuais mostraram a porcentagem de profissionais em cada faixa salarial. O objetivo era identificar padrões consistentes e diferenças estruturais. Por exemplo, se um tipo de empresa concentra mais profissionais em faixas salariais mais baixas ou mais altas.

![image](https://github.com/user-attachments/assets/0ebc3913-3f16-47b9-ae94-ed1f28ef23d8)

**Analise do Resultado**

No grafo longo dos três anos, os bancos mantiveram sua liderança na concentração de profissionais na faixa de R$ 8k-12k.

* As fintechs, por outro lado, mostram um fortalecimento gradual em faixas salariais mais altas, diminuindo a diferença em relação aos bancos, especialmente na faixa de R$ 12k-16k em 2024.

Nota-se uma tendência geral em ambos os arquétipos de reduzir a proporção de profissionais nas faixas mais baixas (abaixo de R$ 4.000), sugerindo uma maior senioridade do mercado ou uma valorização geral dos salários de entrada.



### Variação Ano a Ano: 

A análise da variação percentual anual (: 2023 vs. 2022) revelou a dinâmica do mercado. Os gráficos mostraram quais faixas salariais tiveram o maior crescimento ou queda na representatividade de profissionais, indicando tendências como "achatamento" ou "valorização" de certos níveis de remuneração em bancos e fintechs.

![image](https://github.com/user-attachments/assets/d02acf95-76b6-45a5-9b80-1de3aec99439)

**Analise dos Resultados**


* Mudanças em 2023: As fintechs apresentaram um crescimento percentual expressivo na faixa de R$ 30.001 a R$ 40.000 (+213%), indicando um forte movimento para atrair talentos muito caros.

* Mudanças em 2024: A tendência se repetiu, com as fintechs novamente mostrando o maior crescimento na faixa de R$ 30.001 a R$ 40.000 (+120%). Os bancos, por sua vez, tiveram seu maior pico de crescimento na faixa de R$ 25.001 a R$ 30.000 (+70%).

_Conclusão Principal:_ As fintechs demonstram ser mais ágeis e agressivas em suas políticas de remuneração, especialmente para atrair e reter talentos de ponta com salários muito elevados. Os bancos, embora mais estáveis, também mostram um esforço claro para valorizar posições de alta senioridade.



### Perfil Médio Consolidado (2022-2024):

Ao calcular a média da distribuição dos três anos, foi possível visualizar um "retrato" geral e estável do perfil salarial. A análise dos dados (perfil_medio_df) sugere que:

![image](https://github.com/user-attachments/assets/9a108575-7093-4501-b6fa-76c4a5d9de78)

* Grandes Empresas (Bancos): Concentram a maior parte de seus profissionais nas faixas mais altas, especialmente de R$ 8.001/mês a R$ 12.000/mês (25.68%) e de R$ 12.001/mês a R$ 16.000/mês (16.69%).

* Pequenas/Médias Empresas (Fintechs): Apresentam uma distribuição mais forte em faixas intermediárias, com picos em de R$ 8.001/mês a R$ 12.000/mês (19.58%) e de R$ 4.001/mês a R$ 6.000/mês (15.69%).

Isso indica que, em média, os bancos tendem a ter uma proporção maior de funcionários em faixas salariais superiores em comparação com as fintechs.


* 3. Análise Salarial por Nível de Senioridade
A investigação foi aprofundada para entender como a remuneração varia de acordo com o nível de senioridade.

### Salário do 3º Quartil (p75): 

Esta análise focou nos salários mais altos (o valor que 75% dos profissionais ganham a menos que ele), revelando o potencial de ganho em cada nível. O gráfico de barras comparativo permitiu visualizar o "teto" salarial mais comum para os talentos mais bem pagos em bancos e fintechs, sendo uma métrica importante para avaliar a competitividade na atração de profissionais sêniores.

![image](https://github.com/user-attachments/assets/f5169625-67d5-4986-9b6b-8642dc77ddb5)


**Analise dos Resultados**

A análise do "Salário do 3º Quartil (p75)" revela o potencial de ganho para os profissionais de melhor desempenho em cada nível:

* Nível Júnior: Os grandes bancos oferecem um teto salarial maior (R$ 7.000) em comparação com as fintechs (R$ 5.000).

* Nível Pleno: O potencial de ganho é idêntico e altamente competitivo, com ambos os setores oferecendo um teto de R$ 10.000.

* Nível Sênior: A situação se inverte drasticamente. As fintechs oferecem um potencial de ganho significativamente maior para seus talentos sêniores de ponta (R$ 18.000) em comparação com os grandes bancos (R$ 14.000).

_Conclusão Principal:_ Enquanto os bancos podem ser mais atraentes para o início de carreira (Júnior), as fintechs se destacam por oferecer uma remuneração superior e maior potencial de crescimento para profissionais de nível Sênior.


Resumo Geral do Eixo 1

### Distribuição Salarial Completa (Boxplot): 

O boxplot ofereceu a visão mais completa da estrutura salarial, mostrando:

* A mediana (salário central).

* A dispersão dos salários (o tamanho da "caixa").

* A presença de outliers (salários muito acima do padrão).

Essa visualização é fundamental para comparar não apenas os valores médios, but também a consistência e a amplitude salarial em cada nível de senioridade (Júnior, Pleno, Sênior e Liderança) entre os dois tipos de empresa.

![image](https://github.com/user-attachments/assets/d113d09c-f1f7-49fc-b632-bdc959eeeed5)
**Analise do Resultado**

O gráfico de "Perfil Médio de Distribuição Salarial" consolida os dados de 2022 a 2024 e oferece uma visão geral da estrutura de remuneração:

* Grandes Empresas (Bancos): A maior concentração de profissionais está na faixa de R$ 8.001 a R$ 12.000 (25,7%), com uma forte presença também na faixa de R$ 6.001 a R$ 8.000 (16,9%) e R$ 12.001 a R$ 16.000 (16,7%). Isso indica uma estrutura onde a maioria dos profissionais já se encontra em patamares salariais intermediários para altos.

* Pequeno/Médio Porte (Fintechs): A distribuição é mais espalhada nas faixas intermediárias. Embora o pico também seja em R$ 8.001 a R$ 12.000 (19,6%), há uma proporção maior de funcionários em faixas como R$ 4.001 a R$ 6.000 (15,7%) em comparação com os bancos.

Conclusão Principal: Em média, os grandes bancos possuem uma força de trabalho mais concentrada em faixas salariais superiores quando comparados às fintechs.



Em resumo, a análise exploratória do Eixo 1 transformou dados brutos de salário em insights acionáveis, mapeando as diferenças e semelhanças nas estruturas de remuneração entre bancos tradicionais e fintechs, tanto de forma geral quanto estratificada por ano e nível de senioridade.
 
 ### Eixo 2 — Adoção Tecnológica e Estratégias de Infraestrutura
 
Neste eixo, a análise se aprofunda na infraestrutura tecnológica, investigando como bancos e fintechs adotam plataformas de nuvem. O objetivo é medir a maturidade digital, a evolução da modernização e as estratégias de nuvem (incluindo multicloud e a persistência de sistemas legados on-premise).

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

Adoção de GCP: O Google Cloud Platform (GCP) consistentemente apresenta uma maior taxa de adoção em fintechs do que em bancos, sugerindo que pode ser uma opção preferencial para empresas mais novas e ágeis.

Sistemas On-Premise: A presença de infraestrutura on-premise diminuiu ligeiramente nos bancos (de 15.4% em 2023 para 11.3% em 2024), indicando um lento, mas contínuo, processo de migração para a nuvem.

* 2. Evolução da Estratégia Multicloud
  
![image](https://github.com/user-attachments/assets/fe60d40b-4ca9-449b-a5d1-5cbe6a8ffeff)

Metodologia: Foi criada uma métrica para identificar a adoção de uma estratégia multicloud, considerando como tal os profissionais que utilizam duas ou mais das três principais plataformas (AWS, Azure, GCP). Essa abordagem é estratégica para evitar dependência de um único fornecedor (vendor lock-in) e otimizar custos.

Resultados e Interpretação: O gráfico de linha sobre a adoção multicloud mostra uma tendência mais estável e clara. Ele mede a maturidade estratégica em vez da preferência por uma única plataforma. A visualização gerada permite concluir qual dos arquétipos (bancos ou fintechs) está avançando mais rapidamente na adoção de uma infraestrutura de nuvem diversificada e resiliente. Tipicamente, espera-se um crescimento contínuo nesta métrica para ambos os segmentos.

* 3. Segmentação de Perfis de Liderança
 
![image](https://github.com/user-attachments/assets/487e108d-9816-418a-aa1e-bdbaf1b9c4eb)

Metodologia: Como um passo preparatório para análises futuras, o conjunto de dados foi filtrado para isolar os profissionais que atuam como gestores ou líderes (atua_como_gestor).

Resultado: Foi criado um novo dataframe, df_lideres, contendo 460 gestores, de um total de 2.750 profissionais no setor financeiro.

Essa segmentação é de grande valor estratégico, pois permite que as próximas análises comparem diretamente as ferramentas, desafios, salários e decisões tecnológicas do ponto de vista de quem toma as decisões versus a equipe técnica, oferecendo insights muito mais profundos sobre a governança de dados e a estratégia tecnológica nas organizações.
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

[1] Veja: Número de fintechs no Brasil cresceu 77% desde 2020, segundo levantamento  Disponível em:https://veja.abril.com.br/coluna/radar-economico/numero-de-fintechs-no-brasil-cresceu-77-desde-2020-segundo-levantamento. Acesso em: 07 jul. 2025.

[2] Banco Central do Brasil: Fintechs . Disponível em: https://www.bcb.gov.br/estabilidadefinanceira/fintechs. Acesso em: 07 jul. 2025.

[3] BBCB: Banking on the future.  Disponível em: https://www.bbc.com/storyworks/control-to-customise/banking-on-the-future. Acesso em: 07 jul. 2025.

[4] Fluid Blog Dock: Fintechzação: como empresas estão se tornando fintechs e transformando o mercado de banking e pagamentos.  Disponível em: https://dock.tech/fluid/blog/financeiro/fintechzacao/#:~:text=A%20fintechza%C3%A7%C3%A3o%20envolve%20a%20incorpora%C3%A7%C3%A3o,investimentos%20diretamente%20aos%20seus%20clientes. Acesso em: 07 jul. 2025.



---

<div id='APÊNDICES'/>  

## APÊNDICES:


