# 1. Estudo de caso I
A HBFIN DTVM SA foi criada em 2021 com objetivo popularizar o investimento no mercado financeiro. 
A principal atividade é a distribuição de fundos de investimento e o seu principal produto é a plataforma 
de investimentos, HUB FINANCEIRO. Esta plataforma oferece liberdade de escolha para seus clientes 
investirem em vários fundos de investimento de diversos gestores.
Atualmente a HBFIN tem aproximadamente 360 mil investidores e conta com 104 fundos de 
investimento disponíveis na sua plataforma.
Direcionada pelo propósito “Prover liberdade financeira para todos”, a Diretoria da HBFIN definiu cinco 
objetivos estratégicos para ano de 2023, e alguns deles contarão com a participação direta do novo 
time de Data Analytics.
Objetivos Estratégicos para o ano de 2023:
• OB1: Aumentar a base de clientes, totalizando 500 mil investidores;
• OB2: Aumentar a quantidade de fundos de investimento disponíveis na plataforma, totalizando
150 fundos; 
• OB3: Reduzir a quantidade de churn (resgate total) dos fundos;
• OB4: Aumentar a receita da empresa em 10% em relação ao ano de 2022;
• OB5: Melhorar a UX (user experience) do investidor no uso da plataforma e acrescentar novos 
recursos;
A partir dos objetivos estratégicos, produza os seguintes estudos usando Python e apresente o 
resultado no formato adequado. As fontes de dados sugeridas no item 3 podem ajudá-lo no 
desenvolvimento dos estudos.
## 1.1. 
Para o OB3, baseado em um cenário hipotético, elabore um estudo que apresente as 
abordagens (tarefas e técnicas) de Data Analytics que podem ser aplicadas para reduzir a 
possibilidade de churn dos clientes.
Dica 1: O arquivo “PRV_INVESTIDOR_ATRIBUTOS.xlsx” poderá auxiliá-lo no estudo;
Dica 2: Considere que você tem acesso pleno a todas as informações sobre os fundos de 
investimento disponíveis na plataforma HUB FINANCEIRO.
O resultado deste item deverá conter no mínimo o texto elaborado pelo candidato com as 
devidas explicações e justificativas das abordagens escolhidas.
## 1.2. 
Para o OB2, visando contribuir com a Diretoria de Produtos na escolha dos novos fundos que 
serão incluídos na plataforma, identifique de forma aleatória 50 fundos do mercado brasileiro
e calcule a rentabilidade anual em 2022. Na sequência, identifique os intervalos de quartis com 
base na rentabilidade e efetue a distribuição desses 50 fundos em seus respectivos quartis. Por 
fim, identifique em quais quartis se enquadram os 10 fundos com maior rentabilidade no ano 
de 2022 disponíveis na plataforma HUB FINANCEIRO.
Dica 1: O informe diário de fundos contido no site da CVM https://dados.cvm.gov.br/ possui 
todo o histórico de COTA e PL dos fundos da indústria.
Dica 2: Considere 31/10/2022 a data mais recente disponível. Portanto, utilize os dados do 
informe diário de fundos dos meses de janeiro/2022 e outubro/2022.
Dica 3: A relação dos fundos de investimento disponíveis na plataforma HUB FINANCEIRO estão 
no arquivo: “PRV_s.dataLISTA_FUNDOS.csv” com a informação de rentabilidade anual para a 
data base de 31/10/2022.
O resultado deste item deverá conter no mínimo o código Python utilizado; um print do gráfico
gerado como exemplo; e a lista dos fundos por quartis.

# 2. Estudo de caso II
A HBFIN ASSET MANAGEMENT SA é uma gestora de fundos de investimento que deseja elevar a 
representatividade dos fundos de renda variável em seu portfólio de produtos. Uma das iniciativas 
apreciadas pelo gestor envolve a aplicação de técnicas de Data Analytics para identificar a tendência 
dos ativos com maior número de negócios nos últimos três meses e subsidiar a tomada de decisão de 
compra ou venda do ativo dependendo se a tendência do preço do ativo é de alta ou de baixa.
Considerando que tendência de alta corresponde à elevação do preço do ativo negociado em bolsa 
durante cinco pregões consecutivos e, por outro lado, a tendência de baixa corresponde à redução do 
preço do ativo durante cinco pregões consecutivos, elabore o seguinte estudo:
## 2.1.
A partir da série histórica de cotações dos ativos negociados em bolsa nos últimos três meses, 
escolha aleatoriamente um ativo e elabore uma análise para identificar quantas vezes a 
tendência de alta ou de baixa foi confirmada no sexto dia.
Obs: O ativo cujo comportamento não se enquadra nas tendências citadas acima, conclui-se que a 
tendência é neutra.