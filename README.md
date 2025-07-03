💼 Sistema de Cadastro de Usuários

Sistema simples web para cadastro e consulta de usuários, desenvolvido em Django, com foco em praticar conceitos de CRUD (Cadastro e Consulta) e estruturação de aplicações web.

📑 Índice  

     🔧 Decisões técnicas
      📚 Frameworks e bibliotecas
        ⚙️ Requisitos
          🚀 Como executar o projeto
            📂 Com entrada web
              📈 Fluxograma

🔧 Decisões técnicas:
- 🐍 Python e Django: Escolhidos por serem ferramentas poderosas e acessíveis para desenvolvimento web rápido e estruturado. Django foi selecionado para praticar a criação de projetos escaláveis com banco de dados integrado.

- 🌐 HTML e Bootstrap: Utilizados para criação da interface web simples e responsiva.

- 🗃️ SQLite: Banco de dados leve e fácil de configurar, ideal para projetos de aprendizado e prototipagem.

📚 Frameworks e bibliotecas:
- Python
- Django
- SQLite
- CSS(Bootstrap)
- HTML

⚙️ Requisitos:
- Python 3.13 ou superior
- Django instalado (pip install django)

📂 Estrutura do Projeto:

  projeto_cad_usuarios/
├── app_cad_usuarios/
│   ├── migrations/
│   ├── templates/
│   │   └── usuarios/
│   │       ├── base.html
│   │       ├── home.html
│   │       └── usuarios.html
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── views.py
│   └── urls.py
├── projeto_cad_usuarios/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── db.sqlite3
├── manage.py
└── README.md

🚀 Como executar o projeto:
- O projeto é acessado via navegador após iniciar o servidor local do Django.

🔗 Acesse o Projeto Localmente:

💻 Link de acesso

     http://127.0.0.1:8000/

✍️ Como utilizar:

1.Preencha o nome e idade no formulário.

2.Clique em "Enviar" para adicionar um novo usuário.

3.Os usuários cadastrados aparecerão listados na tabela abaixo do formulário.
