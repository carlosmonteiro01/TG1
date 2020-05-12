FACULDADE DE TECNOLOGIA DE SÃO JOSÉ DOS CAMPOS
FATEC PROFESSOR JESSEN VIDAL








CARLOS HENRIQUE MONTEIRO NETO






CONTROLE DE UMIDADE RELATIVA DO AR UTILIZANDO INTERNET DAS COISAS





















São José dos Campos
2020

 
 
CARLOS HENRIQUE MONTEIRO NETO







CONTROLE DE UMIDADE RELATIVA DO AR UTILIZANDO INTERNET DAS COISAS






Trabalho de Graduação apresentado à Faculdade de Tecnologia de São José dos Campos, como parte dos requisitos necessários para a obtenção do título de Tecnólogo em Banco de Dados.


Orientador: Professor Fabiano Sabha









São José dos Campos
2020 



Dados Internacionais de Catalogação-na-Publicação (CIP)
Divisão de Informação e Documentação





 





REFERÊNCIA BIBLIOGRÁFICA

SOBRENOME, Nome do Aluno. Título do Trabalho de Graduação. 20XX. 999f. Trabalho de Graduação - FATEC de São José dos Campos: Professor Jessen Vidal.







CESSÃO DE DIREITOS

NOME(S) DO(S) AUTOR(ES): Carlos Henrique Monteiro Neto
TÍTULO DO TRABALHO: Controle de umidade relativa do ar utilizando internet das coisas
TIPO DO TRABALHO/ANO: Trabalho de Graduação/2020.


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



 
1.	INTRODUÇÃO
Hoje a Forming Tubing do Brasil, (Forming Tubing, 1993), opera num crescente em relação à produção de filtros para refrigeração, a matéria prima usada é o cobre, e uma das grandes dificuldades do setor é o controle da umidade relativa do ar, que hoje é feito manualmente.
Na produção é necessário ter um controle da umidade pois o filtro tem que ser produzido dentro de uma determinada porcentagem de umidade(40% à 80%), vejamos primeiro o porquê se utilizar do cobre.
É utilizado o cobre na fabricação pois  o cobre oferece múltiplos benefícios: contribui para o aumento da eficiência energética, estimula a energia sustentável e promove o desenvolvimento tecnológico, além de ter a qualidade de ser antimicrobiano. Entre as inúmeras características que definem o cobre como o elemento ideal para a utilização em refrigeração e climatização, destaca-se sua alta condutividade térmica.
São propriedades e características do cobre para aplicação em sistemas de refrigeração e climatização: (Procobre, 2015)

• Boa resistência a pressões internas e golpes de aríete.
• Em caso de incêndio, não pega fogo nem libera gases tóxicos.
• É de fácil manuseio e transporte.
• Suas peças podem ser unidas por soldagem, garantindo segurança às tubulações.
• Tem boa deformação plástica, garantindo a confecção das tubulações.
• Resiste a altas e baixas temperaturas.
• Fornecido em barras rígidas e rolos flexíveis em grandes comprimentos.
• Não oxida facilmente quando exposto à atmosfera ambiente.
• Resistente às intempéries.	
• Intercambiável com qualquer tubo e conexão.
Agora vamos entender o porquê essa limitação, vejamos, na NR17 que trata sobre as adaptações das condições de trabalho, no artigo 17.5.2 trata bem essa questão:
“ 17.5.2. Nos locais de trabalho onde são executadas atividades que exijam solicitação intelectual e atenção constantes, tais como: salas de controle, laboratórios, escritórios, salas de desenvolvimento ou análise de projeto, dentre outros, são recomendadas as seguintes condições de conforto:
Níveis de ruído de acordo com o estabelecido na NBR 10152, norma brasileira registrada no INMETRO;
Índice de temperatura efetiva entre 20°C e 23°C;
Velocidade do ar não superior a 0,75m/s
Umidade relativa do ar não inferior a 40%” (Governamental, 2012)

Com isso obedecendo a norma da NR17 e diante testes criou-se o parâmetro de umidade no local entre 40% a 80%.
Quando ocorre a produção dos artefatos se a peça ficar exposta ao ambiente com umidade relativa do ar abaixo de 40% o que ocorre é a saturação dos filtros, fazendo-se com que a produção do artefato perca a eficiência de absorção da umidade, e acima de 80% o que ocorre é a condensação dos elementos do filtro fazendo-se o artefato ficar ineficiente já que o mesmo ficou exposto a grande quantidade de umidade. 
Após o processo de fabricação 10% dos itens fabricados é passado pelo processo de qualidade, e nele é verificado sua eficiência através de teste.
Hoje o operador líder da unidade de filtro da Forming Tubing é o responsável pela coleta dos dados de umidade relativa de ar do espaço reservado à produção do filtro secador, o mesmo utiliza-se de um medidor de umidade estilo relógio que fica na parede e mostra a porcentagem da umidade no local.
O espaço para produção é de 70m² e conta com 4 aparelhos de ar-condicionado com função de umidificador, 2 deles localizados no centro e um em cada ponta.
O operador de hora em hora numa planilha(figura1), adiciona a umidade do local e se ficou abaixo de 40% liga os aparelhos de ar-condicionado e se ficou acima de 80% desliga os aparelhos, conseguindo assim manter a média para obter o máximo de eficiência do filtro secador.
 
1.1. Problema apresentado 
            Controle manual da umidade relativa do ar no ambiente de produção de filtro
secador da fábrica Forming Tubing do Brasil. 

1.2. Conteúdo do Trabalho
O presente trabalho está estruturado em seis Capítulos, cujo conteúdo é sucintamente apresentado a seguir:
No Capítulo 2 é feita a fundamentação das tecnologias
O Capítulo 3 apresenta o desenvolvimento da solução
No Capítulo 4 são apresentados os resultados
O Capítulo 5 apresenta as considerações finais  deste trabalho a partir da análise dos resultados obtidos

