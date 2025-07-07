# A Fusão Invisível no Mercado Financeiro Brasileiro

---

_**Integrantes:**_
* Enzo Alves Barcelos Gripp, (9eabgripp@sga.pucminas.br)
* Pedro Dias Soares, (pedro3soares@gmail.com)
* Thiago Domingos Venturim Ribeiro dos Santos, (thiagodomingosventutim@gmail.com)

**Resumo:**

---

## Sumario:

[1. Introdução](#Introdução)   

[2. Contextualização](#Contextualização)

[3. Problema](#Problema)

[4. Pergunta Direcionada a Dados](#Pergunta_Direcionada_a_Dados)

[5. Objetivos](#Objetivo)

[6. Justificativas ](#Justificativas)

[7. Público alvo](#Público_alvo)

[9. Preparação dos dados](#Preparação_dos_dados)

[8. Análise exploratórida dos dados](#Análise_exploratórida_dos_dados)

[10. Indução do modelo](#Indução_de_modelos)

[11. Resultados ](#Resultados)  

[13. Conclusão ](#Conclusão)

[14. Referências ](#REFERÊNCIAS)

[15. Apêndices](#APÊNDICES)

---

<div id='Introdução'/>  
  
## Introdução:

Com grande entusiasmo, submetemos esta análise ao Challenge State of Data Brazil 2025, uma iniciativa promovida pela comunidade Data Hackers em parceria com a Bain & Company. Motivados pela oportunidade de contribuir com o maior mapeamento do mercado de dados do país , nosso projeto investiga um dos fenômenos mais impactantes e atuais do cenário financeiro nacional.

Nossa pesquisa concentra-se na interseção entre dois movimentos convergentes e, ao mesmo tempo, contrastantes: a "Fintechzação" dos bancos e a "Bancarização" das fintechs. Enquanto o primeiro representa a incorporação de tecnologias ágeis, inovação digital e experiência centrada no usuário por instituições tradicionais, o segundo sinaliza o avanço das fintechs rumo a estruturas mais robustas, reguladas e próximas do sistema bancário convencional.

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

---

<div id='Análise_exploratórida_dos_dados'/>  

## Análise Exploratórida dos Dados:

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


