# TG1
Projeto trabalho graduação de banco de dados 01

FACULDADE DE TECNOLOGIA DE SÃO JOSÉ DOS CAMPOS
FATEC PROFESSOR JESSEN VIDAL








NOME DO AUTOR







TÍTULO DO TRABALHO DE GRADUAÇÃO





















São José dos Campos
20XX 

 
 
NOME DO AUTOR








TÍTULO DO TRABALHO DE GRADUAÇÃO





Trabalho de Graduação apresentado à Faculdade de Tecnologia de São José dos Campos, como parte dos requisitos necessários para a obtenção do título de Tecnólogo em Banco de Dados.


Orientador: Titulação e Nome do Orientador
Coorientador (se existir): Titulação e Nome do Coorientador








São José dos Campos
20XX 



Dados Internacionais de Catalogação-na-Publicação (CIP)
Divisão de Informação e Documentação





 





REFERÊNCIA BIBLIOGRÁFICA

SOBRENOME, Nome do Aluno. Título do Trabalho de Graduação. 20XX. 999f. Trabalho de Graduação - FATEC de São José dos Campos: Professor Jessen Vidal.







CESSÃO DE DIREITOS

NOME(S) DO(S) AUTOR(ES): Nome Completo do Aluno 
TÍTULO DO TRABALHO: Título do Trabalho de Graduação 
TIPO DO TRABALHO/ANO: Trabalho de Graduação/20XX.


É concedida à FATEC de São José dos Campos: Professor Jessen Vidal permissão para reproduzir cópias deste Trabalho e para emprestar ou vender cópias somente para propósitos acadêmicos e científicos. O autor reserva outros direitos de publicação e nenhuma parte deste Trabalho pode ser reproduzida sem a autorização do autor.





_____________________________________
Nome Completo do Autor
Endereço do Autor
XXXXX-XXX, Cidade - Estado	
NOME DO AUTOR




TÍTULO DO TRABALHO DE GRADUAÇÃO
 


Trabalho de Graduação apresentado à Faculdade de Tecnologia de São José dos Campos, como parte dos requisitos necessários para a obtenção do título de Tecnólogo em Banco de Dados.








__________________________________________________________________
Titulação, Nome do Componente da Banca - Sigla da Instituição


___________________________________________________________________
Titulação, Nome do Componente da Banca - Sigla da Instituição


__________________________________________________________________
Titulação, Nome do Orientador – Sigla da Instituição Titulação


__________________________________________________________________
Nome do Coorientador (se existir) - Sigla da Instituição





_____/_____/_____

DATA DA APROVAÇÃO (dia da banca)
Dedicatória (opcional)












































O autor oferece a obra (elemento sem título e sem indicativo numérico), ou presta homenagem a alguém, de forma clara e breve em folha única.
AGRADECIMENTOS



Na página de agradecimentos o autor dirige palavras de reconhecimento àqueles que contribuíram para a elaboração do trabalho. O conteúdo não deve ultrapassar uma página e por isso, é necessário que ele seja sucinto e objetivo.
O texto deve ser escrito em Times New Roman, Tamanho 12, Alinhamento Justificado, Espaçamento entre linhas de 1,5 linhas e com recuo de parágrafo de 1,25 cm.







































Epígrafe (opcional)




































“É citada uma sentença escolhida pelo autor (elemento sem título e sem indicativo numérico), que deve guardar coerência com o tema abordado na obra.”
Nome do autor
RESUMO


Apresentação concisa dos pontos relevantes do documento deve ser exposta no resumo. No presente caso o resumo será informativo, assim deverá ressaltar o objetivo, a metodologia, os resultados e as conclusões do documento. A ordem desses itens depende do tratamento que cada item recebe no documento original. O resumo deve ser composto por uma sequência de frases concisas, afirmativas e não em enumeração de tópicos. Deve ser escrita em parágrafo único e espaçamento de 1,5 linhas. A primeira frase deve ser significativa, explicando o tema principal do documento. Deve-se usar o verbo na voz ativa e na terceira pessoa do singular. Quanto a sua extensão, o resumo deve possuir de 150 a 500 palavras. 

Palavras-Chave: Com um mínimo de 3 e no máximo 6 palavras, separadas entre si por ponto e vírgula “;” e finalizadas por ponto. As palavras-chave são palavras representativas do conteúdo do documento.
ABSTRACT


O abstract é o resumo da obra em língua estrangeira, que basicamente segue o mesmo conceito e as mesmas regras que o texto em português. Recomenda-se que para o texto do abstract o autor traduza a versão do resumo em português e faça, se necessário, os ajustes referentes à conversão dos idiomas. É importante observar que o título e texto NÃO DEVEM estar em itálico.

Keywords: Recomenda-se que o autor traduza para o inglês as Palavras-Chave em português e faça, se necessário, os ajustes referentes à conversão dos idiomas.




























LISTA DE FIGURAS

Figura 1 - Proposta metodológica	17








































LISTA DE TABELAS


Tabela 1 - População de 15 a 24 anos de idade	18































LISTA DE ABREVIATURAS E SIGLAS



ARF	Árvore da Realidade Futura
APS	Advanced Planning and Scheduling
ARA	Árvore da Realidade Atual
B2B	Business to Business
CD		Centro de Distribuição
CEPAA 	Council on Economic Priorities Accreditation Agency
































LISTA DE SÍMBOLOS



dab		Distância Euclidiana
O(n)	Ordem de um Algoritmo





































SUMÁRIO

1. INTRODUÇÃO	15
1.1. Objetivos do Trabalho	15
1.2. Conteúdo do Trabalho	15
2. FUNDAMENTAÇÃO TÉCNICA	17
2.1. Título 2.1	17
2.2. Título 2.2	17
3. DESENVOLVIMENTO	18
3.1. Arquitetura do Sistema	18
3.2. Título 3.2	18
4. RESULTADOS	19
4.1. Título 4.1	19
4.2. Título 4.2	19
5. CONSIDERAÇÕES FINAIS	20
5.1. Contribuições	20
5.2. Trabalho Futuros	20
REFERÊNCIAS	21
APÊNDICE A/ANEXO A – EXEMPLO DE APÊNDICE/ANEXO	23
Como deve ser a formatação das Figuras, Tabelas e Equações no trabalho	24
Como deve ser mencionada as Siglas no trabalho	26
Como deve ser feitas as citações no trabalho	26
Como utilizar as referências bibliográficas no texto do trabalho	27



 
1. INTRODUÇÃO
A introdução deve conter uma breve revisão sobre o tema do trabalho de graduação,  problematização, relevância, proposta metodológica, motivação e justificativa do tema. 
Em relação a formatação, a configuração da página deve ser A4 medindo (21,0 cm x 29,7 cm) com margem esquerda e superior de 3 cm e margem direita e inferior de 2 cm. A fonte é Times New Roman, Tamanho 12 para o texto. O espaço entre linhas é de 1,5 linhas e texto justificado. Espaços especiais devem ser usados para as páginas de rosto, verso e banca. Esta informação pode ser obtida a partir do modelo especificado do site da FATEC‐SJC.
Os títulos dos capítulos serão escritos em tamanho 14, a fonte é Times New Roman e em negrito, não devendo ser utilizado o termo “capítulo”. Os subitens são em negrito, tamanho 12 com a fonte Times New Roman e numerados a partir da numeração do capítulo. Os capítulos são numerados em arábico. 
Todas as folhas do trabalho de graduação, a partir da folha de rosto, devem ser contadas sequencialmente (Exceto a folha no qual consta os Dados de Catalogação, pois esta é impressa no verso da folha de rosto). Da contra capa, inclusive, a numeração é sequencial em algarismos romanos. A partir da Introdução continua a numeração sequencial em algarismos arábicos no canto superior direito da folha. A numeração da página é feita em tamanho 10. Apêndice(s) e Anexo(s) seguem a numeração sequencial em algarismos arábicos. 

1.1. Objetivos do Trabalho 
O objetivo geral deste trabalho é...
Para a consecução deste objetivo foram estabelecidos os objetivos específicos:
•	Realizar uma investigação sobre os atuais...
•	Propor ...


1.2. Conteúdo do Trabalho
O presente trabalho está estruturado em seis Capítulos, cujo conteúdo é sucintamente apresentado a seguir:
No Capítulo 2 é feita a fundamentação das tecnologias...
O Capítulo 3 apresenta o desenvolvimento da solução...
No Capítulo 4 são apresentados os resultados ...
O Capítulo 5 apresenta as considerações finais  deste trabalho a partir da análise dos resultados obtidos...

2. FUNDAMENTAÇÃO TÉCNICA
Neste capítulo serão revistos textos que subsidiem os conhecimentos necessários ao entendimento do trabalho apresentado. Será realizada pesquisa na literatura específica envolvendo manuais técnicos, catálogos de fabricantes, base de patentes, livros texto, revistas técnicas, quando o trabalho for acadêmico, ou  será feito o levantamento de requisitos, tecnologias utilizadas e suas justificativas e soluções existentes/similares no caso do trabalho tecnológico (com cliente real).
O título do capítulo 2 deve ser FUNDAMENTAÇÃO TÉCNICA, porém os subtítulos fica a critério do(s) autor(es). 
Em relação a formatação, deve seguir o padrão das instruções apresentadas ao final deste documento.
2.1. Título 2.1
Texto.....
2.2. Título 2.2
Texto.....

3. DESENVOLVIMENTO
Neste capítulo deve ser abordado a metodologia e o enfoque experimental utilizados no trabalho. O título DESENVOLVIMENTO é  OBRIGATÓRIO, podendo os subtítulos  serem modificados pelo(s) autor(es) de acordo com o trabalho que está sendo desenvolvido, com uma abordagem tecnológica ou científica. 
Em relação a formatação, deve seguir o padrão das instruções apresentadas ao final deste documento.
3.1. Arquitetura do Sistema
Esse subtítulo e conteúdo  é obrigatório.....
3.2. Título 3.2
Texto.....

4. RESULTADOS
Nesta fase será realizada uma análise crítica dos resultados obtidos, comparando com os esperados e os visualizados na Fundamentação Técnica. Considerando o trabalho tecnológico nesse capítulo a demonstração da realização dos testes com o cliente são obrigatórios.
Em relação a formatação, deve seguir o padrão das instruções apresentadas ao final deste documento.
4.1. Título 4.1
Texto.....
4.2. Título 4.2
Texto.....

5. CONSIDERAÇÕES FINAIS
Esta é a parte final do trabalho, referindo-se às hipóteses discutidas anteriormente. A conclusão é uma resposta para a problemática do tema proposto na introdução, com base nos resultados que o(s) autor(es) avaliou e interpretou. 
Em relação a formatação, deve seguir o mesmo das instruções apresentadas ao final deste documento.
5.1. Contribuições
Nessa seção  deverão ser listadas as contribuições do trabalho, experiências e dificuldades dos autor no decorrer do trabalho.

5.2. Trabalho Futuros
Este trabalho não encerra as contribuições no tema (incluir o tema), mas abre oportunidade para os seguintes trabalhos futuros:

•	Trabalho futuro 1
•	Trabalho futuro 2
•	Trabalho futuro N



REFERÊNCIAS 
AGENDA 21. Conferência da Nações Unidas sobre Meio Ambiente e Desenvolvimento. Disponível em http://www.mma.gov.br/sitio/index.php?ido=conteudo.monta&idEstrutura=18 Acesso em: 12/10/2010.
ALVES, J. M. Proposta de um Modelo Híbrido de Gestão da Produção: aplicação na indústria aeronáutica. 2001. 236 f. Tese (Doutorado em Engenharia Mecânica) - Faculdade de Engenharia Mecânica, Universidade Estadual de Campinas, Campinas, 2001.
ALVES FILHO, A. G.; CERRA, A. L.; MAIA, J. L. ; SACOMANO NETO, M. e BONADIO, P. V. G. Pressupostos da Gestão da Cadeia de Suprimentos: Evidências de Estudos sobre a Indústria Automobilística. G&P – Gestão & Produção. Vol. 11, n. 3, p. 275-288, Set.-Dez. 2004.
ANGERHOFER, B. J. e ANGELIDES, M. C. A model and a performance measurement system for collaborative supply chains. Science Direct - Decision Support Systems, Vol. 42, p. 283-301, 2006.
BALLOU, R. H. Gerenciamento da Cadeia de Suprimentos. São Paulo: Artmed, 2005.
SANTOS, R. F. Proposta de um sistema híbrido de Contabilidade Gerencial: Estudo de Caso na Empresa Siber do Brasil S.A. 2005. 168 f. Dissertação (Mestrado em Ciência no Curso de Engenharia Aeronáutica e Mecânica, Área de Produção) - ITA - Instituto Tecnológico de Aeronáutica, São José dos Campos, 2005.
SANTOS, R. S. e ALVES, J. M. Proposta de um Modelo de Gestão da Cadeia de Suprimentos com o Apoio da Teoria das Restrições, VMI e B2B. In: ENCONTRO NACIONAL DE ENGENHARIA DE PRODUÇÃO, 2009, Salvador. Anais... Salvador, 2009. 12 f.
ZILIO, S. D. Modeling and verification of parallel processes. In: CASSEZ, Franck et al (Ed.). Mobile processes: a commented bibliography. New York: Springer-Verlag, 2001. p. 206-222. (Lectures Notes in Computer Science, v. 2067). 
ASSOCIAÇÃO BRASILEIRA DE NORMAS TÉCNICAS. NBR 5462: 1994: confiabilidade e mantenabilidade: terminologia. Rio de Janeiro, 1994. 
EMBRAPA. Unidade de Apoio, Pesquisa e Desenvolvimento de Instrumentação Agropecuária (São Carlos, SP). Paulo Estevão Cruvinel. Medidor digital multissensor de temperatura para solos. BR n. PI 8903105-9. 26 jun. 1989, 30 maio 1995.
MICROSOFT. Project for windows 95: project planning software. Version 4.1: [S.l.]: Microsoft Corporation, 1995. Conjunto de programas. 1 CD-ROM. 
ALLISON, D.O.; MINECK, R.E. Aerodynamic characteristics and pressure distributions for an executive-jet baseline airfoil section. Washington, DC: NASA, 1993. 25 p. (NASA TM-4529).
MARINHO, P. A pesquisa em ciências humanas. Petrópolis: Vozes, 1980 apud MARCONI, M. A.; LAKATOS, E. M. Técnicas de pesquisa. São Paulo: Atlas, 1982.



As referências acima são das fontes: 
Amarelo: Internet
Verde: Dissertação ou Tese de Mestrado e Doutorado
Azul Claro: Artigo publicado em periódico
Magenta: Livro
Azul Escuro: Congresso
Vermelho: Capítulo de livro
Cinza: Normas técnicas 
Roxo: Patentes
Verde Escuro: Programa de computador 
Marrom: Relatório técnico
AZUL Petróleo: Exemplo de referência com apud




















APÊNDICE A/ANEXO A – EXEMPLO DE APÊNDICE/ANEXO
A.1	Exemplo de Subseção do Apêndice A

Apêndice e anexos são opcionais no documento. O documento pode conter quantos apêndices ou anexos forem necessários. Lembrando que Apêndice é um documento ou texto elaborado pelo autor a fim de complementar sua argumentação e Anexo é um documento ou texto não elaborado pelo autor que servem de fundamentação ou comprovação (por exemplo: relatórios, mapas, leis, estatutos dentre outros). Os apêndices devem aparecer após as referências, e os anexos, após os apêndices, e ambos devem constar no sumário. 
Caso tenha mais do que um apêndice e ou um anexo, deve-se utilizar a nomenclatura: Apêndice A, Apêndice B, Apêndice C etc.














INSTRUÇÕES GERAIS PARA FORMATAÇÃO DO TRABALHO DE GRADUAÇÃO

Como deve ser a formatação das Figuras, Tabelas e Equações no trabalho 
É caracterizado como figura todo desenho, esquema, fluxograma, fotografia, gráfico, mapa, organograma, planta, quadro, retrato, figura, imagem, entre outros. 
Para as figuras sua identificação aparece na parte superior, precedida da palavra Figura seguida de seu número de ordem de ocorrência no texto, em algarismos arábicos, ponto (em negrito) e da respectiva legenda. A identificação da figura e a legenda devem ser em texto centralizado, e em espaçamento simples, caso ocupe mais de uma linha do texto. A legenda da figura deve conter as informações necessárias à sua compreensão.
Na parte inferior da figura, deve ser indicado a fonte consultada de acordo com o modelo de referência adotado no trabalho (elemento obrigatório, mesmo que seja produção do próprio autor). A fonte deve ser alinhada à esquerda na figura em Times New Roma tamanho 10. A ilustração deve ser citada no texto como Figura (com a palavra iniciando em maiúsculo) seguida de seu número, o mais próximo possível do trecho a que se refere.

EXEMPLO:
Para atender os objetivos [...] e procedimentos técnicos utilizados na Figura 1. (Observe que a palavra figura inicia com letra maiúscula).

Figura 1 - Proposta metodológica.
 
Fonte: Adaptada de Santos (2010).

Para as tabelas sua identificação aparece na parte superior, precedida da palavra Tabela seguida de seu número de ordem de ocorrência no texto, em algarismos arábicos, ponto (em negrito) e da respectiva legenda. A identificação da tabela e a legenda devem ser em texto centralizado, e em espaçamento simples, caso ocupe mais de uma linha do texto. A legenda da tabela deve conter as informações necessárias à sua compreensão.
Na parte inferior da tabela, deve ser indicado a fonte consultada de acordo com o modelo de referência adotado no (elemento obrigatório, mesmo que seja produção do próprio autor). A fonte deve ser alinhada à esquerda na tabela em Times New Roma tamanho 10. A tabela deve ser citada no texto como Tabela (com a palavra iniciando em maiúsculo) seguida de seu número, o mais próximo possível do trecho a que se refere.

EXEMPLO:
A Tabela 1 apresenta a população entre... (observe que a palavra tabela inicia com letra maiúscula).








Tabela 1 - População de 15 a 24 anos de idade.


Ano	População de 15 a 24 anos de idade
	
Total Absoluto	Variação
	Participação em relação à população total	Taxa de crescimento (%)
		Absoluta	Relativa (%)		
1940	8246733			20,1	
1950	10489368	2426352	27,2	20,3	2,4
1960	13413413	2924048	27,9	19,2	2,5
1970	18539088	5125672	38,2	19,9	3,3
1980	25089191	6550103	35,3	21,1	3,1
1991	28582350	3493159	13,9	19,5	1,2
1996	31088484	2506134	8,8	19,8	1,7
Fonte: Oliveira (2015)


No caso das equações, para facilitar a leitura, devem aparecer no texto como Equação seguida de seu número de ordem de ocorrência no texto, em algarismos arábicos. As variáveis da equação devem estar descritas em seguida.

EXEMPLO:
A Equação 1 representa a condição... (observe que a palavra equação inicia com letra maiúscula).
x2 + y2 = z2                                                                                                  (1)
Onde x, y e z são variáveis do processo.

Como deve ser mencionada as Siglas no trabalho
Caso o(s) autor(es) do trabalho opte em não utilizar a lista de abreviaturas e siglas, quando mencionadas pela primeira vez no texto, deve ser indicada entre parêntesis, precedida do nome completo. EXEMPLO: Segundo a Associação Brasileira de Normas Técnicas (ABNT) ... (observe que as palavras referentes à abreviação iniciam com a letra maiúscula).

Como deve ser feitas as citações no trabalho 
As citações no texto, figuras e tabelas devem seguir o sistema “autor-data”. Este sistema deve ser seguido consistentemente ao longo de todo o trabalho, permitindo sua correlação na lista de referências (item REFERÊNCIAS BIBLIOGRÁFICAS). 

Sistema autor-data

No texto, deve-se indicar o(s) Autor(es) pelo SOBRENOME sem as iniciais, em maiúsculas, seguido do ano da publicação, separados por vírgula e entre parênteses. Casos especiais de citação devem seguir o modelo (ver item Como utilizar as referências bibliográficas no texto do trabalho). No texto das referências, o sistema data-autor, devem aparecer em ordem alfabética.

EXEMPLOS:
(a) Robôs flexíveis apresentam graus de liberdade adicionais (SOUZA, 2013). 
(b) Citações de mais de um documento de autores diferentes devem ser separados por “;”. Exemplo: (SILVA, 2003; COSTA, 2000; OLIVEIRA, 2014).
(c) Quando houver coincidência de sobrenomes de autores, acrescentar as iniciais de seus prenomes: (BARBOSA, C., 1958) e (BARBOSA, O., 1958). Se mesmo assim existir coincidência, colocam-se os prenomes por extenso: (BARBOSA, Cássio, 1965) e (BARBOSA, Celso, 1965).
(d) As citações de diversos documentos do mesmo autor, publicados num mesmo ano, são distinguidas pelo acréscimo de letras minúsculas, em ordem alfabética, após a data e sem espacejamento. Acrescentar as letras após a data, tanto a citação, quanto na referência. Exemplo: a pesquisa apresentou um resultado (SILVA, 2010a) e também outro resultado (SILVA, 2010b).

Como utilizar as referências bibliográficas no texto do trabalho

No texto há várias maneiras de referenciar a literatura utilizada para o desenvolvimento do trabalho. Há várias maneiras de se fazer uma citação como, citação indireta, citação indireta, citação de citação e entre outras.

(a) Citação indireta: No caso de citações indiretas onde o texto foi baseado na obra de um autor consultado. No texto, pode ser referenciado como:
EXEMPLO: 
Segundo Santos (2010), o apoio ao... 
Santos (2010) acredita que... 
O sistema deve ser dimensionado (SANTOS, 2010).

(b) Citação direta: No caso de citações diretas, onde ocorreu a transcrição textual de parte da obra de um autor consultado, deve-se colocar a citação entre aspas e indicar a página onde se encontra a citação na referência.
EXEMPLO: 
Santos (2010, p. 23) afirma que “seu método será aplicado nos trabalhos em série”.
“O trabalho pode ser entendido como um ponto chave” (SANTOS, 2010).

(c) Citação com 4 ou mais autores: Em uma citação com 4 ou mais autores coloca-se o nome do primeiro autor seguido de et al..
EXEMPLO: 
Segundo Miguel et al. (2010), a diferença [...] e qualitativa é que...
A diferença [...] e qualitativa é que [...] final (MIGUEL et al., 2010).

(d) Citação de citação: É uma citação, direta ou indireta, de um texto em que não se teve acesso ao original.
EXEMPLO: 
Segundo Pires (2008 apud SANTOS, 2010), o apoio ao...
Segundo Pires (2008) citado por Santos (2010), o apoio ao... (opção ao apud)
O sistema de testes do perfil é subliminar (PIRES, 2009 apud SANTOS, 2010).
(e) Citação longa: Citações com mais de 3 linhas devem receber uma formatação especial, onde o tamanho da letra será 10, com espaçamento simples e início do parágrafo com 4 cm. 
EXEMPLO: Para sistema data-autor
Esta relevância também foi constatada por Hansen e Mowen (2001, p. 31) na afirmação de que:
“A grande melhoria no transporte e na comunicação levaram a um mercado global para muitas empresas de manufatura e de serviços. Várias décadas atrás, as empresas não sabiam sobre, e nem se importavam com, o que empresas similares do Japão, França, Alemanha e Cingapura estavam fazendo. Estas empresas estrangeiras não eram concorrentes, já que os mercados eram separados por uma distância geográfica.”

