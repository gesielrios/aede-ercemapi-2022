<p align="center">
    <img src="./github/banner.jpeg" width="600px"/><br><br>
</p>

# AEDE-ERCEMAPI-2022

Repositório com material utilizado no Minicurso: Análise Exploratória de Dados Espaciais com Python apresentado na X ESCOLA REGIONAL DE COMPUTAÇÃO
CEARÁ, MARANHÃO E PIAUÍ ERCEMAPI 2022

## Resumo

O desenvolvimento acentuado de tecnologias para análise de dados no espaço geográfico ocorrido nos últimos anos tem oferecido possibilidades inovadoras ao entendimento da influência dos efeitos espaciais na explicação de vários fenômenos e constitui um grande desafio para diversas áreas do conhecimento científico. A análise exploratória de dados espaciais (AEDE) é a extensão da análise exploratória de dados (AED) para o problema de detecção de propriedades espaciais de conjuntos de dados onde, para cada valor de atributo, existe um dado locacional. Este dado de localização referencia o ponto ou a área à qual o atributo se refere. AEDE é um conjunto de técnicas que visa descrever e visualizar distribuições espaciais, identificar locais atípicos ou discrepantes espaciais, descobrir padrões de associação espacial, clusters e sugerir regimes espaciais ou outras formas de heterogeneidade espacial. O objetivo deste minicurso é alinhar a teoria e a prática, apresentando alguns dos conceitos e técnicas associadas à AEDE com python, com foco em dados vetoriais tabulares.

O Minicurso cobrirá os seguintes tópicos, usando Jupyter Notebooks e exercícios práticos com dados do mundo real:

Introdução
Dados Espaciais
Matrizes de ponderação espacial
Mapas coropléticos
Autocorrelação espacial global
Autocorrelação espacial local

## 🧪 Tecnologias

Este Minicurso exigirá instalações recentes de:

python v3.9
matplotlib
geopandas
pysal
[Jupyter Notebook or Lab] (http://jupyter.org)

Se você ainda não tem esses pacotes instalados, recomendamos usar o gerenciador de pacotes conda para instalar todos os requisitos (você pode instalar o miniconda ou instalar a (maior) distribuição Anaconda, encontrada em https://www.anaconda.com/download /).

Usando conda, recomendamos criar um novo ambiente com todos os pacotes usando os seguintes comandos:

Clone o projeto:

```bash
$ git clone https://github.com/gesielrios/aede-ercemapi-2022.git
```

Acesse o diretório do projeto e instale as dependências:

```bash
# ensure you have at least conda >=4.6
conda update conda
# setting the configuation so all packages come from the conda-forge channel
conda config --add channels conda-forge
conda config --set channel_priority strict

# creating the environment
conda create -n aede-ercemapi-2022 python=3.9
# activating the environment
conda activate aede-ercemapi-2022
# dependencies install
pip install -r requirements.txt
```

## 🎓 Agredecimentos

🚀 <a href="https://ercemapi22.ifma.edu.br/" target="_blank">ERCEMAPI 2022</a>.

## 📝 Licença

Este projeto está licenciado sob a Licença MIT.