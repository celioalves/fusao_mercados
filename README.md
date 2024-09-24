## Projeto de Fusão de Mercados

### Explicação do projeto
<br>

##### Recebi o seguinte trabalho e informação, um grande supermercado estava fazendo a aquisição e fusão de outras duas redes do mesmo ramo. Com isso fora passado os dados de ambas as redes que estavam sendo adquiridas. O objetivo era trabalhar com esses dados que vinham de bases diferentes, em formatos distintos. Assim, me solicitaram que eu fizesse a fusão dos dados de ambas as redes para que pudessem ter um controle de estoque (filiais), controle de vendas, quais produtos estavam sendo comercializados por essas redes adquiridas e, se possível, que apresentasse a última data de venda registrada de cada item.

##### Acontece que uma das duas empresas adquiridas, não registrava a data de venda, então todos os itens que não possuiam tal informação, tiveram a data de venda marcada como indisponível.

##### Divisão do projeto: <br> Primeiro efetuei a divisão da pasta na qual trabalharia no projeto em 4 subpastas: <br> data_raw - onde estavam os arquivos brutos; <br> data_processed - onde o arquivo final foi salvo; <br> notebooks - onde trabalhei com o Jupyter Notebook para fazer a exploração dos arquivos; <br> e por último, scripts - onde foi elaborada a pipeline de dados.

##### Na pasta scripts, o arquivo fusao_mercados.py é onde está a pipeline, que pode ser alterada pelo usuário, adicionando novos arquivos que possam ser gerados com o tempo, está dividida na leitura de arquivos (path) e ETL. Já no arquivo processamento_dados.py, é onde o bruto aconteceu, estão as funções, a classe que foi utilizada e tudo mais. Neste último arquivo não há porque o usuário fazer qualquer interação.
