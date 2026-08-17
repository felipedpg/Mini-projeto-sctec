Mini-Projeto Avaliativo - Módulo 1 - Semana 07
Sobre o projeto

Este projeto foi desenvolvido como parte da avaliação do projeto SCTEC e tem como objetivo realizar uma Análise Exploratória de Dados (AED) utilizando a base Varejo.csv, presente no seguinte endereço https://www.kaggle.com/datasets/namespaiva/base-varejo/data

A análise foi desenvolvida em Python, utilizando principalmente a biblioteca Pandas, e executada no Visual Studio Code (VS Code).

O projeto contempla as seguintes etapas:

Importação e inspeção da base de dados; Identificação de valores nulos; Identificação e remoção de registros duplicados; Identificação de possíveis inconsistências; Limpeza e padronização de dados textuais; Tratamento dos valores #N/D; Conversão da coluna DATA para o formato datetime; Ajuste dos tipos de dados; Estatística descritiva da variável de número de filhos dos clientes; Agrupamento dos dados por gênero; Agrupamento dos dados por categoria de produto; Geração de conclusões sobre os principais resultados encontrados; Exportação de uma nova base de dados limpa.

Arquivos do projeto Miniprojeto_NomeDoAluno_Turma/ │ ├── Varejo.csv ├── analise_varejo.py ├── df_limpo.csv └── README_FelipePaiva_AnaliseDados.md Descrição dos arquivos Varejo.csv — base de dados original utilizada no projeto. analise_varejo.py — script Python responsável pela análise exploratória e limpeza dos dados. df_limpo.csv — arquivo gerado pelo script após a realização das etapas de limpeza. README.md — documentação e instruções para execução do projeto.

Tecnologias utilizadas Python Pandas Visual Studio Code GitHub Como executar o projeto no VS Code

Instalar o Python
Certifique-se de que o Python está instalado no computador.

Para verificar, abra o terminal do VS Code e execute:

python --version 2. Instalar o Pandas

No terminal do VS Code, execute:

pip install pandas 3. Abrir o projeto

Abra a pasta do projeto no Visual Studio Code.

Certifique-se de que o arquivo Varejo.csv está na mesma pasta que o arquivo:

analise_varejo.py 4. Executar o script

No terminal do VS Code, execute:

python analise_varejo.py

O programa realizará automaticamente as etapas de análise e exibirá os resultados no terminal.

Ao final da execução, será criado o arquivo:

df_limpo.csv

contendo a base após as etapas de limpeza.

Principais etapas da análise Importação

Ao final, o programa apresenta no terminal um resumo da análise, incluindo os principais problemas encontrados, os resultados estatísticos, os agrupamentos e as principais conclusões obtidas a partir da base.

A base tratada é salva automaticamente como:

df_limpo.csv Observação

Esse projeto tem finalidade academica e foi criado com o objetivo de aplicar tecnicas básicas de análise exploratória, limpeza e transformação de dados com Python.
