Este projeto é um sistema de cadastro de produtos desenvolvido com:

Back-end: Python 3.10, FastAPI, SQLite
Front-end: HTML, CSS, JavaScript


O cadastro dos produtos é inserido em um Banco de dados SQLite através da biblioteca FasApi com Python.


Necessário executar os seguintes procedimentos para Executar
-----------------BackEnd --------------------
Necessário instalar o Python 3.12 + pip para executar a aplicação. Em seguida abrir o cmd na pasta do projeto.

-Instalar FastAPI
pip install fastapi
pip install uvicorn
pip install sqlalchemy
pip install sqlite3

-Executar a aplicação backend(Python)
uvicorn produtos:app --reload --host 0.0.0.0 --port 8000

-Executar a aplicação FrontEnd(Html)
Executar a aplicação em modo servidor como desejar. 
Caso execute com o VsCode é possivel executar baixando a
Extensão Live Server, de Ritwick Dey, em seguida clicando
com o botão direito no arquivo Index.html e selecionando
a opção: Open With Live Server e pronto! O sistema está
pronto para ser utilizado.