# capyba-project

## A Python-Django Rest API Project i Developed for a Challenge.
Este é um Projeto Rest API Desenvolvido na Linguagem Python, e no Framework Django. Este é um APP que funciona com um sistema de usuários, onde cada usuário
possui uma tarefa a ser realizada, cada tarefa possui um Título (Title), uma Descrição (Description) da tarefa, e uma marcação de a mesma foi completada ou não (Complete)
O sistema de tarefas funciona como um CRUD, Create, Read, Update e Delete, todas essas funcionalidades existem no sistema, o usuário pode então realizar cada uma
dessas funcionalidades.

Inicialmente para poder utilizar este app, e testa-lo, você deve inicialmente instalar a linguagem de programação Python, você pode fazer isso pelo site do Python:

https://www.python.org/downloads/ 

(Recomendo caso esteja pelo OS Windows); Ou, também pode instalar pelo terminal de sua máquina (caso esteja no Linux): 

sudo apt-get python3.10  

Agora, é necessário a instalação do Framework Django, você pode instalar pelo comando abaixo em seu terminal:

python -m pip install Django

Agora que instalamos todas as ferramentas, podemos iniciar o projeto! Utilize o comando no terminal: 
python manage.py runserver
Após o aplicativo rodar normalmente, o terminal mostrará tal mensagem: 

Starting development server at http://127.0.0.1:8000/ 

Clique no link para ser redirecionado ao APP do programa que está no navegador.

Ao entrar no link, você verá uma tela de Login, caso tenha uma conta no sistema logue normalmente (Que provavelmente não é o seu caso correto?), caso não possua uma conta vá para a página de se registrar e crie sua conta. ATENÇÃO A SENHA! recomendo que coloque uma senha normal, já que o sistema analiza se a senha tem menos de 8 caracteres, se ela é similar ao seu nome de usuário e não pode ser inteiramente numérica e não deixa o usuário criar uma conta.
Após criada a conta, você pode utlizar o sistema de Tarefas normalmente! E cada uma de suas funções CRUD, criando uma tarefa, lendo as tarefas que o usuário possui, atualizando as tarefas ou deletando as mesmas.


OBS: Um sistema admin também foi criado, caso queira entrar é necessário adicionar o /admin após o link, tornando assim:

http://127.0.0.1:8000/admin/

Para criar uma conta admin você deve rodar este comando em seu terminal: 

python manage.py createsuperuser

Com a conta criada você pode entrar na área dos Admins normalmente.
