# bootcampDS_Projeto02
Este é o projeto de conclusão do Módulo 02 do Bootcamp de Data Science 

## Objetivo e Premissa

Demonstrar através dos dados disponibilizados pelo Datasus, entre outras fontes, que os resultados do Programa Nacional de Imunização na saúde dos brasileiros é muito importante para mantermos o controle de doenças ainda ativas e mesmo daquelas consideradas erradicadas, e que a falta de aderência da população aos planos de vacinação tem um impacto na vida de muitas pessoas. Vamos analisar os dados dos estados brasileiros e tentar encontrar informações que tragam luz sobre o impacto da vacinação e da não vacinação sobre a saúde dos brasileiros.

## Definicão de Escopo

- Local: Todos os Estados Brasileiros
- Período: de 2008 até 2020
- Doença: Febre Amarela
- Todas as faixas etárias

## O que é o Programa Nacional de Imunizações - PNI

O êxito das Campanhas de Vacinação contra a varíola na década dos anos sessenta, mostrou que a vacinação em massa tinha o poder de erradicar a doença. O último caso de varíola notificado no Brasil foi em 1971 e, no mundo em 1977 na Somália.

Em 1973 foi formulado o Programa Nacional de Imunizações - PNI, por determinação do    Ministério da Saúde, com o objetivo de coordenar as ações de imunizações que se caracterizavam, até então, pela descontinuidade, pelo caráter episódico e pela reduzida área de cobertura. A proposta básica para o Programa, constante de documento elaborado por técnicos do Departamento Nacional de Profilaxia e Controle de Doenças (Ministério da Saúde) e da Central de Medicamentos (CEME - Presidência da República), foi aprovada em reunião realizada em Brasília, em 18 de setembro de 1973, presidida pelo próprio Ministro Mário Machado Lemos e contou com a participação de renomados sanitaristas e infectologistas, bem como de representantes de diversas instituições.

Em 1975 foi institucionalizado o PNI, resultante do somatório de fatores, de âmbito nacional e internacional, que convergiam para estimular e expandir a utilização de agentes imunizantes, buscando a integridade das ações de imunizações realizadas no país. O PNI passou a coordenar, assim, as atividades de imunizações desenvolvidas rotineiramente na rede de serviços e, para tanto, traçou diretrizes pautadas na experiência da Fundação de Serviços de Saúde Pública (FSESP), com a prestação de serviços integrais de saúde através de sua rede própria. A legislação específica sobre imunizações e vigilância epidemiológica (Lei 6.259 de 30-10-1975 e Decreto 78.231 de 30-12-76) deu ênfase às atividades permanentes de vacinação e contribuiu para fortalecer institucionalmente o Programa.

Em seguimento à erradicação da varíola, inicia-se em 1980 a 1ª CAMPANHA NACIONAL DE VACINAÇÃO CONTRA A POLIOMIELITE, com a meta de vacinar todas as crianças menores de 5 anos em um só dia. O último caso de poliomielite no Brasil ocorreu na Paraíba em março de 1989. Em setembro de 1994 o Brasil junto com os demais países da região das américas, recebeu da Comissão Internacional para a Certificação da Ausência de Circulação Autóctone do Poliovírus Selvagem nas Américas, o Certificado que a doença e o vírus foram eliminados de nosso continente.

De 1990 a 2003, o PNI fez parte do CENEPI/FUNASA - Fundação Nacional de Saúde. A partir de 2003, passou a integrar a DEVEP/SVS - Secretaria de Vigilância em Saúde, inserido na Coordenação Geral do Programa Nacional de Imunizações - CGPNI.

Ao longo do tempo, a atuação do PNI, ao consolidar uma estratégia de âmbito nacional, apresentou, na sua missão institucional precípua, consideráveis avanços. As metas mais recentes contemplam erradicação do sarampo e a eliminação tétano neonatal. A essas, se soma o controle de outras doenças imunopreveníveis como Difteria, Coqueluche e Tétano acidental, Hepatite B, Meningites, Febre Amarela, formas graves da Tuberculose, Rubéola e Caxumba em alguns Estados, bem como, a manutenção da erradicação da Poliomielite.

Cabe também a CGPNI adquirir, distribuir e normatizar o uso dos imunobiológicos especiais, indicados para situações e grupos populacionais específicos que serão atendidos nos Centros de Referência para Imunobiológicos Especiais - CRIEs. É também de responsabilidade desta coordenação a implantação do Sistema de Informação e a consolidação dos dados de cobertura vacinal em todo o país.

Destacamos que o objetivo principal do Programa é de oferecer todas as vacinas com qualidade a todas as crianças que nascem anualmente em nosso país, tentando alcançar coberturas vacinais de 100% de forma homogênea em todos os municípios e em todos os bairros.

O PNI é, hoje, parte integrante do Programa da Organização Mundial de Saúde, com o apoio técnico, operacional e financeiro da UNICEF e contribuições do Rotary Internacional e do Programa das Nações Unidas para o Desenvolvimento (PNUD).

ref: http://pni.datasus.gov.br/apresentacao.asp

## Cobertura Vacinal

Esse termo refere-se ao percentual (o número de doses aplicadas de determinado imunobiológico dividido pela população alvo e multiplicado por 100) da população que está vacinada. Quanto mais pessoas receberem determinada vacina, maior será a cobertura vacinal. A eliminação ou controle de qualquer doença imunoprevenível depende da obtenção desse índice de sucesso

A fórmula de cálculo da cobertura é o número de doses aplicadas da dose indicada (1ª, 2ª, 3ª dose ou dose única, conforme a vacina) dividida pela população alvo, multiplicado por 100. Exemplo: para a Tetravalente (DTP/Hib), considera-se o número de terceiras doses aplicadas na faixa etária de menores de 1 ano. Para a vacina oral de rotavírus humano, pode-se avaliar cobertura de 1ª e 2ª doses.

ref: https://familia.sbim.org.br/vacinas/conceitos-importantes, http://tabnet.datasus.gov.br/cgi/pni/%5Ccpnidescr.htm

## Movimento Antivacina

O movimento antivacinação foi incluído pela Organização Mundial de Saúde (OMS) em seu relatório sobre os dez maiores riscos à saúde global. De acordo com a Organização, os movimentos antivacina são tão perigosos quanto os vírus que aparecem nesta lista porque ameaçam reverter o progresso alcançado no combate a doenças evitáveis por vacinação, como o sarampo e a poliomielite. Ainda segundo a OMS, as razões pelas quais as pessoas escolhem não se vacinar são complexas, e incluem falta de confiança, complacência e dificuldades no acesso a elas. Há também os que alegam motivos religiosos para não se vacinar ou a seus filhos. “A vacinação é uma das formas mais eficientes, em termos de custo, para evitar doenças. Ela atualmente evita de 2 a 3 milhões de mortes por ano, e outro 1,5 milhão poderia ser evitado se a cobertura vacinal fosse melhorada no mundo”, afirma a OMS.

Entretanto, os movimentos antivacina vêm crescendo no mundo todo, inclusive no Brasil, que sempre foi exemplo internacional. Segundo dados do Programa Nacional de Imunizações do Ministério da Saúde (PNI/MS), nos últimos dois anos a meta de ter 95% da população-alvo vacinada não foi alcançada. Vacinas importantes como a Tetra Viral, que previne o sarampo, caxumba, rubéola e varicela, teve o menor índice de cobertura: 70,69% em 2017. De acordo com especialistas em saúde pública, se a vacinação da população brasileira fosse adequada, um novo surto de sarampo não se estabeleceria no País. Segundo o Ministério da Saúde, anualmente são aplicados cerca de 300 milhões de doses de 25 diferentes tipos de vacinas, em 36 mil postos de saúde espalhados por todo o Brasil. Ou seja, não faltam vacinas gratuitas e nem acesso a elas.

ref: https://www.sbmt.org.br/portal/anti-vaccine-movement-is-one-of-the-ten-threats-to-global-health/

## Febre Amarela

A febre amarela é uma doença hemorrágica viral aguda potencialmente grave. O nome “amarela" refere-se à icterícia que afeta alguns pacientes. A febre amarela é causada por um vírus, do gênero flavivírus,  transmitido por mosquitos pertencentes às espécies Aedes (principalmente Aedes aegypti, responsável também por transmitir a Zika, a dengue e a chikungunya) e Haemogogus. As diferentes espécies de mosquitos vivem em diferentes habitats, o que determina três tipos de ciclos de transmissão:

* Febre amarela silvestre (ou selvática): nas florestas tropicais, os macacos, que são o principal reservatório da febre amarela, são picados por mosquitos selvagens que passam o vírus para outros macacos. Ocasionalmente, os seres humanos que trabalham ou que viajam para a floresta são picados por mosquitos infectados e desenvolvem a doença.

* Febre amarela intermediária: neste tipo de transmissão, os mosquitos semidomésticos (aqueles que se reproduzem tanto na natureza quanto em torno das famílias) infectam tanto macacos quanto pessoas. Este é o tipo mais comum de surto na África.

* Febre amarela urbana: grandes epidemias ocorrem quando pessoas infectadas introduzem o vírus em áreas densamente povoadas com grande presença de mosquitos e onde a maioria das pessoas tem pouca ou nenhuma imunidade devido à falta de vacinação.

Uma pessoa não transmite a doença diretamente para outra; o macaco também não transmite a doença. É imprescindível a presença de mosquitos infectados agindo como vetores para que haja transmissão.

Geralmente, quem contrai o vírus não chega a apresentar sintomas ou os mesmos são muito fracos. As primeiras manifestações da doença são repentinas: febre alta, calafrios, cansaço, dor de cabeça, dor muscular, náuseas e vômitos por cerca de três dias.

A forma mais grave da doença é rara (só uma pequena proporção de pacientes que contraem o vírus desenvolve sintomas graves) e costuma aparecer após um breve período de bem-estar (até dois dias). A pessoa infectada pode apresentar insuficiências hepática e renal, icterícia (olhos e pele amarelados), manifestações hemorrágicas e cansaço, sintomas que podem resultar em morte num período de sete a 10 dias.

A maioria dos infectados se recupera bem e adquire imunização permanente contra o vírus, o que quer dizer que, depois de se recuperarem, não são mais suscetíveis à doença.

ref: https://www.msf.org.br/o-que-fazemos/atividades-medicas/febre-amarela

## Vacina febre amarela – FA

A vacinação contra febre amarela (VFA – atenuada) é a medida mais importante e eficaz para prevenção e controle da doença. A vacina usada no Brasil é produzida pelo Instituto de Tecnologia em Imunobiológicos (Bio-Manguinhos) da Fundação Oswaldo Cruz (Fiocruz) e consiste de vírus vivos atenuados da subcepa 17DD, cultivados em embrião de galinha. 

É um imunobiológico seguro e altamente eficaz na proteção contra a doença, com imunogenicidade de 90% a 98% de proteção. Os anticorpos protetores aparecem entre o sétimo e o décimo dia após a aplicação da vacina, razão pela qual a imunização deve ocorrer dez dias antes de se ingressar em área de risco da doença.

O esquema vacinal consiste em uma dose única a partir dos 9 meses de idade, a via de administração é subcutânea e o volume da dose é 0,5 mL.

ref: https://portalarquivos2.saude.gov.br/images/pdf/2018/janeiro/18/Guia-febre-amarela-2018.pdf

## Desenvolvimento do Trabalho

No notebook deste repositório estará todo o desenvolvimento do trabalho, desde a captura dos dados, limpeza, desenvolvimento de hipóteses, análises, visualização dos dados, até a conclusão, onde verificaremos se as premissas estão corretas.

<p align="center">
  <img src="https://github.com/cmattosr/bootcampDS_Projeto02/raw/main/imagens/defenda_o_sus.jpg">
</p>

<hr>

Olá Cientista!

Boas vindas ao Projeto do Módulo 02! Neste projeto queremos que você aplique tudo que aprendeu no módulo 1 e 2, analisando dados do programa de imunização nacional, você pode analisar dados de imunos escolhidos por você, pode analisar toda a base de dados, apenas do seu estado ou de estados específicos. Pode analisar as taxas, a cobertura ou as doses calculadas. Ademais, você pode buscar outras fontes de informações fora do DataSUS e usar outros dados do DataSUS para enriquecer suas análises.

Seguem algumas dicas para você mandar bem no desafio final do módulo: capriche nas análises, escreva suas conclusões e hipóteses (mesmo que o resultado seja inconclusivo) e não esqueça de colocar um resumo dos pontos que julgar mais interessantes do seu projeto.

Temos um conjunto de dicas para este projeto. Portanto, fique de boa, use elas como um guia para a construção da sua pesquisa e mergulhe fundo!

São boas práticas de projeto:

Delimitar o escopo do projeto de acordo com o tempo e o aprendizado desse módulo;
Utilizar a base de dados sugerida;
Estruturar o projeto de maneira organizada e lógica;
Criar um notebook que tenha um enredo atraente e coerente;
Tratar e descrever seus dados quando necessário;
Fundamentar bem o cruzamento dos dados (se você utilizar outras bases);
Aplicar as técnicas de configurações de gráficos para torná-los compreensíveis e para criar argumentações embasadas neles;
Se possível, fazer pesquisas para ir além do apresentado no módulo;
Fazer uma conclusão que relate as limitações do projeto, dando ideias para projetos futuros e apresentando os principais resultados da análise;
Citar e trazer as fontes de todo o conteúdo que apresentar e não for de sua autoria.
É recomendado que você utilize o Github para disponibilizar o seu projeto. Caso não tenha familiaridade com o Github, relaxa! Nós vamos disponibilizar essa semana um vídeo com o passo a passo de como criar seu repositório, colocar seus notebooks e estruturar seu README.

Aqui temos alguns exemplos de repositórios bem estruturados, com bons readme, e também de notebooks bem organizados:

https://github.com/CidSantiago/imersao-dados-desafio-final <br> 
https://github.com/gustavolq/Imersao-Dados-Alura <br>
https://github.com/Pedro-correa-almeida/imersao-dados-desafio-final <br>
https://colab.research.google.com/drive/1LO7paa2ArAY7I9hMzTT4Oz34l6m9K9SG?usp=sharing <br>
https://colab.research.google.com/drive/1egYeRJpwKIlrBKtBujyj5E2KW8L5HDn8?usp=sharing <br>

Qualquer dúvida é só nos procurar no Discord do Bootcamp! Bom mergulho!



