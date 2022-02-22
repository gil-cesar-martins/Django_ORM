# Django_ORM
Estudo de um Mapeamento Objeto-Relacional (ORM) 

Projeto para estudo de um ORM de uma suposta montadora. O banco dedados possui em suas colunas a Montadora, o Modelo, Chassi, Preço e Motoristas dos veículos.

A idéia, então será demostrar no Django os relacionamentos dos tipos OneToOne, ManyToOn e ManyToMany e o modo de deleção de objetos em cascata (CASCADE). 

Deploy local
Instale o django com o comando pip:

´pip install django´ 

Instale as dependências no requirements.txt:

´pip freeze > requirements.txt´

Qualquer alteração nos models deve ser concluída com o comando:

´python manage.py makemigrations´

E depois migrar os models para o banco de dados:

python manage.py migrate

Crie um superusuário para o gerenciamento do banco de dados:

python manage.py createsuperuser

Execute sua aplicação:

python manage.py runserver

Para acessar vá no seu navegador e digite http://localhost:8000
