<p align="center"><img src="https://media-exp1.licdn.com/dms/image/C4D0BAQGb8_oLQ1MyUA/company-logo_200_200/0?e=2159024400&v=beta&t=9B6o6krvcHzXfbzlOijhg2syo_kyGzBMlRmRH8UKBBY"></p>

<h1><b><p align="center">Case</p></b></h1>
<p align="justify">Dado as tabelas TB_VENDEDOR e TB_VENDAS já compartilhadas , peço para que seja efetuada as seguintes tarefas.</br>
Lembrando que você poderá realizar o teste em excel, sheets, Power BI ou em qualquer ferramenta que tenha uma análise visual que respondam às perguntas abaixo.</p>

<ol>
<h2><li><b>Criar uma rotina de ETL (Integration Services), que importe a base de dados “baseDados.xlsx”.</b></li></h2>
<h2><li><b> No pacote criado, marcar um flag na tabela TB_VENDEDOR para os mesmos que forem do estado “PR”. Pois estes vendedores serão inválidos para nossa apuração e análise.</b></li></h2>
<h2><li><b>Faremos uma apuração das vendas por vendedor, em que geraremos um arquivo .csv contendo os campos ID_VENDEDOR, BONUS_R$.</b></li></h2>
Onde bônus será:</br>
Vendedor que a soma das vendas seja até R 1.000,00(𝐵ô𝑛𝑢𝑠𝑑𝑒𝑅  500,00)</br>
Vendedor que a soma das vendas seja entre R 1.000,01𝑒𝑅  2.000,00 (Bônus de R$ 750,00)</br>
Vendedor que a soma das vendas seja mais R 2.000,00(𝐵ô𝑛𝑢𝑠𝑑𝑒𝑅  1.000,00)</br>
<h2><li><b>Precisamos gerar os seguintes relatórios (Reporting Services, Power BI, Excel, ...)</b></li></h2>
</ol>