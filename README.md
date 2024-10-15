<h1 dir="auto">Objetivo</h1>

<p>&nbsp;</p>

<p>O objetivo desse projeto &eacute; criar um modelo de aprendizado de m&aacute;quina que prever com precis&atilde;o o diagn&oacute;stico de um paciente que tem ou n&atilde;o diabetes, com base em certas medi&ccedil;&otilde;es cl&iacute;nicas dispon&iacute;veis no conjunto de dados disponibilizados pelo&nbsp;<strong>Institute of Diabetes and disgestive and Kidney Disesases</strong>, atrav&eacute;s do Kaggle (comunidade online para cientistas de dados e profissionais de aprendizado de m&aacute;quina da Google LLC) e pode ser obtido no link abaixo.</p>

<p><a href="https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database" rel="noopener" target="_blank">https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database</a></p>

<h3 dir="auto">T&eacute;cnicas aplicadas:</h3>

<ul dir="auto">
	<li>An&aacute;lise explorat&oacute;ria</li>
	<li>Correla&ccedil;&atilde;o de Pearson;</li>
	<li>Regress&atilde;o Log&iacute;stica;</li>
	<li>M&eacute;tricas de performance do modelo:
	<ul>
		<li>Precision</li>
		<li>Sensibilidade</li>
		<li>Especificidade</li>
		<li>Curva ROC/AUC</li>
		<li>KS</li>
	</ul>
	</li>
	<li>Interpreta&ccedil;&atilde;o do Modelo;</li>
	<li>Otimiza&ccedil;&atilde;o e ajustes.</li>
</ul>

<h3 dir="auto">&nbsp;</h3>

<h1 dir="auto"><strong>Introdu&ccedil;&atilde;o</strong></h1>

<p>&nbsp;</p>

<p>O diagn&oacute;stico preciso de diabetes, muita das vezes, &eacute; um desafio na &aacute;rea da sa&uacute;de, e, neste projeto, aplicamos t&eacute;cnicas avan&ccedil;adas de aprendizado de m&aacute;quina para criar um modelo preditivo capaz de identificar, com alta precis&atilde;o, pacientes com diabetes a partir de medi&ccedil;&otilde;es cl&iacute;nicas. Utilizando um conjunto de dados&nbsp;do <strong>Institute of Diabetes and Digestive and Kidney Diseases</strong>, dispon&iacute;vel na plataforma Kaggle, o modelo foi projetado para otimizar a identifica&ccedil;&atilde;o precoce e auxiliar no tratamento eficaz da doen&ccedil;a.</p>

<p>Para garantir a robustez do modelo, foram utilizadas v&aacute;rias t&eacute;cnicas de ci&ecirc;ncia de dados. A <strong>Correla&ccedil;&atilde;o de Pearson</strong> foi empregada para identificar rela&ccedil;&otilde;es entre as vari&aacute;veis cl&iacute;nicas e o diagn&oacute;stico de diabetes, sendo importante para evitarmos problemas de multicolinearidade.</p>

<p>Essa t&eacute;cnica&nbsp;&eacute; amplamente usada em diferentes contextos, como no estudo de correla&ccedil;&atilde;o entre vari&aacute;veis econ&ocirc;micas e padr&otilde;es de consumo, sendo um m&eacute;todo cl&aacute;ssico para avaliar a influ&ecirc;ncia de fatores em um determinado resultado.</p>

<p>A <strong>Regress&atilde;o Log&iacute;stica</strong>, por sua vez, foi a t&eacute;cnica central na cria&ccedil;&atilde;o do modelo preditivo. Comumente usada em contextos como a previs&atilde;o de default em modelos de cr&eacute;dito ou a probabilidade de sucesso de campanhas de marketing, a regress&atilde;o log&iacute;stica &eacute; ideal para problemas de classifica&ccedil;&atilde;o bin&aacute;ria, como a detec&ccedil;&atilde;o de diabetes (ter ou n&atilde;o ter a doen&ccedil;a). Sua capacidade de estimar a probabilidade de ocorr&ecirc;ncia de um evento a torna especialmente valiosa neste contexto de diagn&oacute;stico cl&iacute;nico.</p>

<p>Al&eacute;m disso, o desempenho do modelo foi avaliado por meio de v&aacute;rias m&eacute;tricas, como <strong>Precision</strong>, <strong>Sensibilidade</strong> e <strong>Especificidade</strong>, que s&atilde;o fundamentais para equilibrar a identifica&ccedil;&atilde;o correta tanto de pacientes doentes quanto saud&aacute;veis. Tamb&eacute;m utilizamos a <strong>Curva ROC/AUC</strong> e o <strong>KS</strong> para realizar uma avalia&ccedil;&atilde;o mais abrangente, permitindo uma an&aacute;lise visual da capacidade discriminativa do modelo em diferentes limiares.</p>

<p>Essas m&eacute;tricas foram essenciais para diagnosticar o desempenho do modelo, possibilitando ajustes que tornaram os resultados mais adequados ao contexto espec&iacute;fico do problema, melhorando a identifica&ccedil;&atilde;o dos pacientes diab&eacute;ticos com maior precis&atilde;o</p>

<p>Essa combina&ccedil;&atilde;o de t&eacute;cnicas e m&eacute;tricas n&atilde;o apenas assegura a cria&ccedil;&atilde;o de um modelo altamente preciso, mas tamb&eacute;m fornece insights profundos sobre as vari&aacute;veis mais relevantes para o diagn&oacute;stico de diabetes. O resultado &eacute; uma ferramenta de apoio &agrave; decis&atilde;o m&eacute;dica que pode auxiliar significativamente na identifica&ccedil;&atilde;o precoce da doen&ccedil;a, contribuindo para melhores resultados cl&iacute;nicos e maior efici&ecirc;ncia no tratamento.</p>

<p dir="auto">___________________________________________________________________________________________________________________</p>

<p dir="auto">&nbsp;</p>

<h1 dir="auto"><strong>Conclus&atilde;o</strong></h1>

<p>Neste projeto, desenvolvemos um modelo de aprendizado de m&aacute;quina para prever o diagn&oacute;stico de diabetes utilizando medi&ccedil;&otilde;es cl&iacute;nicas.&nbsp;</p>

<p>O modelo apresentou uma <strong>precis&atilde;o de 74%</strong>, o que significa que, dos pacientes classificados como diab&eacute;ticos, 74% de fato tinham a doen&ccedil;a. A <strong>sensibilidade</strong>, no entanto, foi de 58%, indicando que o modelo n&atilde;o identificou todos os casos positivos. A <strong>especificidade</strong> foi de <strong>89%</strong>, evidenciando uma boa capacidade de identificar corretamente aqueles que n&atilde;o t&ecirc;m diabetes.</p>

<p>Em um problema como o diagn&oacute;stico de diabetes, &eacute; crucial minimizar os falsos negativos, pois a n&atilde;o detec&ccedil;&atilde;o de um paciente diab&eacute;tico pode trazer s&eacute;rios riscos. Ajustamos, ent&atilde;o, o <strong>corte de probabilidade</strong> para <strong>0,25</strong>, o que resultou em uma redu&ccedil;&atilde;o de <strong>63,4% nos falsos negativos</strong>, e aumento da <strong>sensibilidade para 85%</strong>, frente a 58% antes aferido,o que&nbsp;aumentou&nbsp;a efic&aacute;cia na identifica&ccedil;&atilde;o dos pacientes.&nbsp;Uma observa&ccedil;&atilde;o importante &eacute;&nbsp;o comportamento inverso entre sensibilidade e especificidade, onde ao aumentar um, o outro diminui.</p>

<p>Este trabalho demonstra o poder da <strong>regress&atilde;o log&iacute;stica</strong>, que pode ser aplicada em uma variedade de contextos al&eacute;m da &aacute;rea de sa&uacute;de, como finan&ccedil;as e marketing. Contudo, o modelo criado aqui n&atilde;o &eacute; exaustivo. Em uma nova abordagem, utilizando <strong>redes neurais artificiais (RNA)</strong>, conseguimos atingir <strong>98% de sensibilidade</strong> com o mesmo conjunto de dados, o que seria o ideal para uso em ambientes cl&iacute;nicos. Essa t&eacute;cnica ser&aacute; abordada em um pr&oacute;ximo case,&nbsp;mostrando seu potencial para elevar ainda mais a precis&atilde;o do diagn&oacute;stico.</p>

<p dir="auto">___________________________________________________________________________________________________________________</p>

<p>Para entender como essas conclus&otilde;es foram alcan&ccedil;adas, acompanhe o desenvolvimento do problema de neg&oacute;cio proposto, algoritmo criados e t&eacute;cnicas utilizadas clicando aqui.</p>
