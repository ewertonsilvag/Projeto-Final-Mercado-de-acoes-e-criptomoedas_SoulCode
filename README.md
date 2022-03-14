# Projeto de Conclusão de Curso - Tema: Economia  💰 
O projeto visou aplicar os conceitos vistos durante o curso de engenharia de dados da SoulCode para tratar, organizar e modelar os dados de no mínimo 2 datasets escolhidos de acordo com o tema economia.
## Motivo dos datasets

No final de 2019 já podiam ser lidas notícias acerca de um possível vírus em circulação, mas só em março de 2020 a Organização Mundial da Saúde (OMS) decretou pandemía global pelo coranavírus e uma das medidas de segurança foram o isolamento social, o que acarretou consequentemente numa desaceleração econômica em todo o mundo. Buscando entender de que forma a economia se portou durante este período a equipe resolveu buscar um dataset contendo informações sobre o mercado de ações brasileira que contemplasse o período de no mínimo novembro de 2019 a março de 2020 que foi o ínicio da pandemia. Buscando também melhores comparativos resolvi buscar mais 2 datasets, porém dessa vez em outro tipo de mercado, o da criptomoedas. Os outros dois datasets escolhidos foram os das moedas Bitcoin e Ethereum. Foram realizados todos os devidos tratamentos e normalizações nos 3 datasets em busca de garantir insights relevantes mostrados em um dashboard simples que permitissem achar as devidas respostas para o meu questionamento inicial que era saber o comportamento do mercado econômico durante a pandemia.

## Requesitos 
-Obrigatoriamente os datasets devem ter formatos diferentes (CSV / Json / Parquet / Sql / NoSql) e 1 deles obrigatoriamente tem que ser em CSV. 

-Operações com Pandas (limpezas , transformações e normalizações).

-Operações usando PySpark com a descrição de cada uma das operações.

-Operações utilizando o SparkSQL com a descrição de cada umas das operações.

-Os datasets utilizados podem ser em lingua estrangeira , mas devem ao final terem seus dados/colunas exibidos na lingua PT-BR.

-Os datasets devem ser salvos e operados em armazenamento cloud obrigatoriamente dentro da plataforma GCP (não pode ser usado Google drive ou armazenamento alheio ao google) os dados tratados devem ser armazenados também em GCP, mas obrigatoriamente em um datalake(Gstorage ) , DW(BigQuery) ou em ambos.

-Deve ser feito análises dentro do Big Query utilizando a linguagem padrão SQL com a descrição das consultas feitas.

-Deve ser criado no datastudio um dash board simples para exibição gráfica dos dados tratados trazendo insights importantes.

-Deve ser demonstrado em um workflow simples (gráfico) as etapas de ETL.

-Implementar captura e ingestão de dados por meio de uma PIPELINE com modelo criado em apache beam usando o dataflow para o work.

-Criar plotagens usando pandas para alguns insights durante o processo de Transformação. 

-Por meio de uma PIPELINE fazer o carregamento dos dados normalizados diretamente para um DW ou DataLake ou ambos.

-Montar um relatório completo com os insights que justificam todo o processo de ETL utilizado
