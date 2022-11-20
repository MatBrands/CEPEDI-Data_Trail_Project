# CEPEDI - Projeto Final Trilha de Dados

Este projeto tem como objetivo a conclusão da trilha de dados do curso Python Dados e Web cedido pela CEPEDI, aplicando em uma base de dados todos os conceitos vistos até o currente momento. Foi proposto a escolha de uma base de dados através do website Kaggle e então executar análises exploratórias, aplicar e comparar diversos modelos de machine learning.

Conteúdo:
- Integrantes
- Base de dados
- Instalação
- Organização do projeto
- Desenvolvimento
- Contribuições

## Integrantes

Projeto desenvolvido pelos Devs:

- [Igor Santana](https://github.com/igorssant)
- [Matheus Brandão](https://github.com/MatBrands)
- [Matheus Santos Silva](https://github.com/matheusssilva991)

## Base de dados

A base de dados escolhida para o projeto foi a "Laptop Price", que pode ser encontrada no Kaggle através deste [link](https://www.kaggle.com/datasets/muhammetvarl/laptop-price).

Dentre diversas vantagens encontradas nesta base de dados, podemos pontuar:
- Quantidade considerável de elementos para teste;
- Necessidade de tratativa de dados;
- Balanceamento entre as classes;
- Eda possibilitando diversas descobertas;
- Tamanho (possibilitando upload no github).

## Instalação

No desenvolvimento foi utilizado o gerenciador de pacotes e ambientes [Conda](https://conda.io/). Portanto para prosseguir necessita-se de sua [instalação](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).

- Instalar dependências
```sh
conda env create enviroment.yml
```

- Ativação
```sh
conda activate cepedi-project-venv
```

- Desativação
```sh
conda deactivate
```

## Organização do projeto

A estrutura de pastas do projeto buscou obedecer aos critérios organizacionais exigidos

```sh
├── datasets
│   ├── processed
│   │   └── laptop_price.pkl
│   ├── raw
│   │   ├── laptop_price.csv
├── notebooks
│   ├── edas
│   │   ├── igor_santana.ipynb
│   │   ├── matheus_mbr.ipynb
│   │   └── matheus_ssilva.ipynb
│   ├── model.ipynb
│   └── report.ipynb
│   └── tratative.ipynb
└── outputs
    ├── imgs
    │   └── README.md
    └── planilhas
        └── README.md
```

- Foi criado um notebook para cada dev com as Análises Exploratórias


```sh
├── notebooks
│   ├── edas
│   │   ├── igor_santana.ipynb
│   │   ├── matheus_mbr.ipynb
│   │   └── matheus_ssilva.ipynb
```

- Bases de dados 


```sh
├── datasets
│   ├── processed
│   │   └── laptop_price.pkl
│   ├── raw
│   │   ├── laptop_price.csv
```

- Notebook com as Principais descobertas


```sh
├── notebooks
│   └── report.ipynb
```

- Notebook com as comparações entre modelos


```sh
├── notebooks
│   ├── model.ipynb
```

- Notebook com a tratativa desses dados


```sh
├── notebooks
│   ├── tratative.ipynb
```

## Desenvolvimento

| Feature | Dev | Progresso
| ------- | --- | ---------
| EDA | Igor Santana | Concluído
| EDA | Matheus Brandão | Concluído
| EDA | Matheus Silva | Andamento
| Tratative | Matheus Brandão | Concluído
| Tratative | Matheus Silva | Concluído
| Report | Igor Santana | ---------
| Report | Matheus Silva | ---------
| Report | Matheus Brandão | ---------
| Model | Igor Santana | Andamento
| Model | Matheus Silva | Andamento
| Model | Matheus Brandão | Andamento

## Contribuições

Ressaltar contribuições que julgar relevantes.