# TUTORIAL-Analise-de-dados-com-python-e-pandas

> Status do Projeto: Em desenvolvimento

## Objetivo:
O repositório criado por Mateus Yamaguti com base o livro **Análise de dados com Python e Pandas** (Chen, 2018). Tem como objetivo servir de guia organizado para estudantes iniciantes na área de Análise de dados a obterem um guia de exemplos práticos e didáticos. E por fim, reforçar conteúdos agragando minhas próprias anotações.


### Tecnologias

![Pandas](https://img.shields.io/badge/-Pandas-333333?style=flat&logo=pandas)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)


### Capítulos 

- Capítulo 1: Básico sobre o DataFrame do Pandas

## Descrição do projeto 

<p align="justify">
  Descrição do projeto
</p>

<p style="color: orange;">Atenção: Sugere-se que a leitura dos cpítulo 1 e 2 seja flutuando, uma vez que a ideia desse guia é dar prática aos iniciantes.</p>

## Como rodar a aplicação :arrow_forward:

No terminal, clone o projeto: 

```
git clone https://github.com/mateusyamaguti/TUTORIAL-Introducao-a-linguagem-sql.git
```

##  Ferramentas sugeridas
Gerenciador de banco de dados: SQLite, MySQL workbench e Oracle Live SQL
Editor de projeto: VSCode


# 🧪 Guia de instalação Conda e Jupyter Notebook

Este guia rápido apresenta os comandos essenciais para criar e configurar ambientes Conda, instalar o Jupyter Notebook e habilitar extensões úteis para seu fluxo de trabalho em ciência de dados.

---

## 🐍 Criando um ambiente Conda

Para criar um ambiente virtual com Conda, utilize o seguinte comando (você pode ajustar a versão do Python conforme necessário, para esse repositório foi utilizado o nome **book**):

```bash
conda create -n nome_do_ambiente python=3.10
```

---

## ▶️ Ativando o ambiente Conda

Sempre que for trabalhar em um projeto específico, **ative o ambiente** que você criou:

```bash
conda activate nome_do_ambiente
```

---

## 📓 Instalando o Jupyter Notebook no ambiente virtual

Com o ambiente ativado, instale o Jupyter Notebook:

```bash
conda install jupyter
```

Para iniciar o Jupyter Notebook (com o ambiente já ativado), use:

```bash
jupyter notebook
```

---

## 📓 Instalando bibliotecas necessária para o tutorial

Com o ambiente ativado, instale as seguintes biblioteca:

```bash
conda install pandas xlwt openpyxl seaborn numpy ipython jupyter statsmodels scikit-learn regex wget odo numba
conda install -c conda-forge pweave # you don't really need this package, it was used to build and create the book
conda install -c conda-forge feather-format
pip install lifelines pandas-datareader
```
---

## 🧩 Instalando extensões no Jupyter Notebook

As extensões do Jupyter adicionam funcionalidades extras, como auto-salvamento, TOC, colapsar células etc.

### Passo a passo:

1. Certifique-se de que o canal `conda-forge` está habilitado.
2. Com o ambiente ativado, instale as extensões com:

```bash
conda install -c conda-forge jupyter_contrib_nbextensions
```

3. Ative o configurador gráfico das extensões:

```bash
jupyter nbextensions_configurator enable --user
```

---

## ⚠️ Problema com dependência ausente (`webcolors`)

Se você encontrar o seguinte erro ao tentar instalar ou ativar as extensões:

```
DistributionNotFound: The 'webcolors>=24.6.0; extra == "format-nongpl"' distribution was not found and is required by jsonschema
```

### 🛠 Solução recomendada

Execute os comandos abaixo **com o ambiente ativado**:

```bash
# 1. Ative seu ambiente virtual
conda activate nome_do_ambiente

# 2. Instale o pacote que está faltando
pip install webcolors

# 3. Reinstale o pacote de extensões (caso necessário)
pip install jupyter_contrib_nbextensions

# 4. Reinstale as extensões no Jupyter
jupyter contrib nbextension install --user
```

---

✅ Após isso, ao iniciar o Jupyter Notebook, você verá uma aba chamada **Nbextensions** no menu principal. Lá você poderá ativar/desativar extensões conforme sua necessidade.




## Desenvolvedores/Contribuintes :octocat:

Liste o time responsável pelo desenvolvimento do projeto

| [<img src="https://avatars.githubusercontent.com/u/104587996?s=400&u=3566cc0da3b05b02e8cd36bed3c709d0046f5b61&v=4" width=115><br><sub>Mateus Yamaguti</sub>](https://github.com/Diana-ops) |  
| :---: | :---: | :---: 

## Licença 

The [MIT License]() (MIT)

Copyright :copyright: 2025 - TUTORIAL ESTRUTURA DE DADOS EM C
