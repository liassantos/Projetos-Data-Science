*README*

## Sobre a Análise

O script está dividido em dois arquivos .ipynb na linguagem R.
No arquivo intitulado 'Tratamento_de_dados', eu leio o dataset das escolas da Califórnia (USA) - em que contém informações de atingimento das metas estudantis, escolaridade dos pais, qualificação dos professores, dados de refeições subsidiadas pelo governo, etc-, e faço a limpeza desses dados para, em seguida, analisá-los.
No arquivo intitulado 'Análise_de_dados', eu realizo a análise estatística através de gráficos gerados pelo pacote ggplot2.

### Tratamento_de_dados

- O script começa baixando um arquivo de uma URL do Google Drive e carregando pacotes necessários como googledrive, tidyr e ggpmisc.
- Extrai o ID da URL do Google Drive, baixa o arquivo e o salva localmente como api.csv.
- Converte determinadas colunas para variáveis categóricas e substitui vírgulas por pontos em números decimais.
- Salva o dataframe processado como um arquivo CSV chamado arquivo_tratado.csv.

### Análise_de_dados

- Faço a leitura do arquivo CSV
- Crio gráficos para analisar a relação entre a escolaridade dos pais e o atingimento das metas estudantis pelas escolas da Califórnia.
- Crio gráficos para analisar a relação entre alunos que recebem refeições subsidiadas pelo governo e o atingimento das metas estudantis pelas escolas da Califórnia.
- Gero insights sobre a relação das variáveis com o atingimento das metas estudantis.
