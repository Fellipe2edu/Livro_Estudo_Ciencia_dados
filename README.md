# Livro_Estudo_Ciencia_dados
Analise de dados

# Python para Análise de Dados, 3ª Edição

Materiais e notebooks IPython para "Python para Análise de Dados, 3ª
Edição" de Wes McKinney, publicado pela O'Reilly Media. O conteúdo do livro,
incluindo atualizações e correções de erratas, pode ser (https://wesmckinney.com/book/)

Follow Wes on X: [![Twitter Follow](https://img.shields.io/twitter/follow/wesmckinn.svg?style=social&label=Follow)](https://twitter.com/wesmckinn)

## Instruções de configuração

### Opção 1: Usando UV (Recomendado)

[uv](https://github.com/astral-sh/uv) is a fast Python package installer and resolver. To get started:

1.Instale o UV se ainda não o fez:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

2. Inicie o Jupyter Notebook com todas as dependências:
```bash
uv run jupyter notebook
```

Pronto! O uv criará automaticamente um ambiente virtual e instalará todos os pacotes necessários. `pyproject.toml`.

### Opção 2: Usando o Conda

1. Crie um novo ambiente conda:
```bash
conda create -n pydata-book python=3.11
conda activate pydata-book
```

2. Instalar dependências:
```bash
pip install -r requirements.txt
```

3. Iniciar Jupyter Notebook:
```bash
jupyter notebook
```

**Nota:** Este projeto utiliza o pandas 2.0.3 para garantir a compatibilidade com os notebooks.

# Leitores da 2ª Edição

Se você estiver lendo a 2ª Edição (publicada em 2017), encontre os materiais do livro reorganizados no ramo [`2ª edição`][5].

# Leitores da 1ª Edição

Se você estiver lendo a 1ª Edição (publicada em 2012), encontre os materiais do livro reorganizados no ramo [`1ª edição`][2].

## IPython Notebooks:

* [Chapter 2: Python Language Basics, IPython, and Jupyter Notebooks](http://nbviewer.ipython.org/github/pydata/pydata-book/blob/3rd-edition/ch02.ipynb)
* [Chapter 3: Built-in Data Structures, Functions, and Files](http://nbviewer.ipython.org/github/pydata/pydata-book/blob/3rd-edition/ch03.ipynb)
* [Chapter 4: NumPy Basics: Arrays and Vectorized Computation](http://nbviewer.ipython.org/github/pydata/pydata-book/blob/3rd-edition/ch04.ipynb)
* [Chapter 5: Getting Started with pandas](http://nbviewer.ipython.org/github/pydata/pydata-book/blob/3rd-edition/ch05.ipynb)
* [Chapter 6: Data Loading, Storage, and File Formats](http://nbviewer.ipython.org/github/pydata/pydata-book/blob/3rd-edition/ch06.ipynb)
* [Chapter 7: Data Cleaning and Preparation](http://nbviewer.ipython.org/github/pydata/pydata-book/blob/3rd-edition/ch07.ipynb)
* [Chapter 8: Data Wrangling: Join, Combine, and Reshape](http://nbviewer.ipython.org/github/pydata/pydata-book/blob/3rd-edition/ch08.ipynb)
* [Chapter 9: Plotting and Visualization](http://nbviewer.ipython.org/github/pydata/pydata-book/blob/3rd-edition/ch09.ipynb)
* [Chapter 10: Data Aggregation and Group Operations](http://nbviewer.ipython.org/github/pydata/pydata-book/blob/3rd-edition/ch10.ipynb)
* [Chapter 11: Time Series](http://nbviewer.ipython.org/github/pydata/pydata-book/blob/3rd-edition/ch11.ipynb)
* [Chapter 12: Introduction to Modeling Libraries in Python](http://nbviewer.ipython.org/github/pydata/pydata-book/blob/3rd-edition/ch12.ipynb)
* [Chapter 13: Data Analysis Examples](http://nbviewer.ipython.org/github/pydata/pydata-book/blob/3rd-edition/ch13.ipynb)
* [Appendix A: Advanced NumPy](http://nbviewer.ipython.org/github/pydata/pydata-book/blob/3rd-edition/appa.ipynb)

## License

### Code

O código neste repositório, incluindo todos os exemplos de código nos notebooks listados
acima, é distribuído sob a [licença MIT](LICENSE-CODE). Leia mais na
[Open Source Initiative](https://opensource.org/licenses/MIT).

[1]: https://amzn.to/3DyLaJc
[2]: https://github.com/wesm/pydata-book/tree/1st-edition
[5]: https://github.com/wesm/pydata-book/tree/2nd-edition
[6]: https://wesmckinney.com/book/
