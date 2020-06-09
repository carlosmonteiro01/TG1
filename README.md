Carlos Henrique Monteiro Neto

Orientador: Fabiano Sabha

Título: 

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
 
1.1. Objetivo do trabalho é a criação de um sistema automatizado de controle de umidade relativa do ar no ambiente de produção de filtro secador da fábrica Forming Tubing do Brasil. 

1.2. Conteúdo do Trabalho
O presente trabalho está estruturado em seis Capítulos, cujo conteúdo é sucintamente apresentado a seguir:
No Capítulo 2 é feita a fundamentação das tecnologias
O Capítulo 3 apresenta o desenvolvimento da solução
No Capítulo 4 são apresentados os resultados
O Capítulo 5 apresenta as considerações finais  deste trabalho a partir da análise dos resultados obtidos

2.	FUNDAMENTAÇÃO TÉCNICA
Pensando numa maior confiabilidade para obtenção dos dados de umidade relativa do ar do setor de filtro da Forming Tubing, a solução seria a criação de um sistema automatizado via Arduino (Itália, 2005) com sensores de umidade conhecido como DHT11 e o sensor de infravermelho E18-D80NK.
Tratando um pouco da parte física, a placa Arduino utilizada para o projeto será a de modelo Uno Rev3R3 Atmega328 Smd (conforme figura 2).
 
Ela será fixada próximo ao centro da sala que mede aproximadamente 168 m², nela via as portas seriais será acoplado 2 sensores, o primeiro é o de umidade conhecido como DHT11 (conforme figura 3), e o segundo é o sensor de infravermelho E18-D80NK 
(conforme figura 4).


Para programar e dar vida ao projeto utilizarei uma IDE própria da Arduino, (IDE download), conseguindo assim, dar os primeiros passos e desenvolver a aplicação, 
com ele é possível instalar bibliotecas adicionais e realizar a compilação e gravação dos programas na placa.
O sensor de umidade capta a umidade do ar na sala, e dentro dos parâmetros se necessário utilizando o sensor de infravermelho acoplado aos controles remotos ativa os 4 aparelhos de ar condicionado, a medição será feita com a média dos últimos 5 minutos, os seja, atingindo os parâmetros necessários ele regula os aparelhos para manter a máxima eficiência. 
 Com isso ganhamos em eficiência, pois como podemos ver na figura1 em algumas horas do dia foi constatado que a umidade ficou abaixo do padrão definido podendo assim danificar a produção.
Com isso também ganhamos o tempo do operador, que não precisará ficar intervindo de hora em hora para análise e intervenção manual nos aparelhos. 
Ganhamos também em qualidade pois teremos um controle maior sobre a umidade no local, trazendo assim tranquilidade aos operadores.
Os clientes com toda certeza ficaram ainda mais satisfeitos com os filtros secadores produzidos pela Forming.


