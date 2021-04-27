# MLBOOK: uma referência rápida sobre Aprendizagem de Máquina com Python

O objetivo deste projeto é ...


## Gerando um livro com o aplicativo jupyter-book

Para gerar o livro é necessário baixar o projeto na sua máquina local e instalar o aplicativo [jupyter-book](https://jupyterbook.org/). Este pacote está no arquivo de `requirements.txt`. Sendo assim, sugere-se criar um ambiente virtual a partir do diretório raiz deste projeto.

Para que todos os scripts deste projeto possam ser executados é necessário utilizar **Python 3**. 

````bash
virtualenv venv
source venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
````

e executar os comandos abaixo dentro deste ambiente:

````bash
cd doc/book
./make-book.sh
````

Este comando irá criar uma pasta `_build` dentro do diretório `classify-reviews-mobile/doc/book`. Dentro da pasta `_build` você irá encontrar o arquivo `html/index.html`. A partir deste arquivo você conseguirá navegar pelo livro e ler o conteúdo da documentação. 
