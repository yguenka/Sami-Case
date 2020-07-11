<p align="center"><img src="https://media-exp1.licdn.com/dms/image/C4D0BAQGb8_oLQ1MyUA/company-logo_200_200/0?e=2159024400&v=beta&t=9B6o6krvcHzXfbzlOijhg2syo_kyGzBMlRmRH8UKBBY"></p>

<h1><b><p align="center">Case</p></b></h1>
<p align="justify">Dado as tabelas TB_VENDEDOR e TB_VENDAS já compartilhadas , peço para que seja efetuada as seguintes tarefas.</br>
Lembrando que você poderá realizar o teste em excel, sheets, Power BI ou em qualquer ferramenta que tenha uma análise visual que respondam às perguntas abaixo.</p>

<ol>
<h2><li><b><p align="justify">Criar uma rotina de ETL (Integration Services), que importe a base de dados ´baseDados.xlsx´.</p></b></li></h2>



<h2><li><b><p align="justify">No pacote criado, marcar um flag na tabela TB_VENDEDOR para os mesmos que forem do estado “PR”. Pois estes vendedores serão inválidos para nossa apuração e análise.</p></b></li></h2>
<h2><li><b><p align="justify">Faremos uma apuração das vendas por vendedor, em que geraremos um arquivo .csv contendo os campos ID_VENDEDOR, BONUS_R$.</p></b></li></h2>
Onde bônus será:</br>
Vendedor que a soma das vendas seja até R$ 1.000,00 (Bônus de R$ 500,00)</br>
Vendedor que a soma das vendas seja entre R$ 1.000,01 e R$ 2.000,00 (Bônus de R$ 750,00)</br>
Vendedor que a soma das vendas seja mais R$ 2.000,00 (Bônus de R$ 1000,00)</br>
<h2><li><b><p align="justify">Precisamos gerar os seguintes relatórios (Reporting Services, Power BI, Excel, ...)</p></b></li></h2>
<ol>
	<h3><li><b><p align="justify">Qtd e total das vendas por estado;</p></b></li></h3>
	<h3><li><b><p align="justify">Qtd e total das vendas por mês;</p></b></li></h3>
	<h3><li><b><p align="justify">Por vendedor: A média do valor de vendas, quantos dias entre a primeira e última venda;</p></b></li></h3>
	<h3><li><b><p align="justify">Exibir todas as vendas de cada vendedor, acumulando(somando) as vendas até aquele momento da venda</p></b></li></h3>
</ol>
</ol>
