💼 Sistema de Cadastro de Usuários

Sistema simples web para cadastro e consulta de usuários, desenvolvido em Django, com foco em praticar conceitos de CRUD (Cadastro e Consulta) e estruturação de aplicações web.

📑 Índice  

     🔧 Decisões técnicas
      📚 Frameworks e bibliotecas
        ⚙️ Requisitos
          📂 Estrutura do Projeto
            🔗 Acesse o Projeto Localmente
              📈 print 

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

🔗 Acesse o Projeto Localmente:

💻 Link de acesso

     http://127.0.0.1:8000/

✍️ Como utilizar:

1.Preencha o nome e idade no formulário.

2.Clique em "Enviar" para adicionar um novo usuário.

3.Os usuários cadastrados aparecerão listados na tabela abaixo do formulário.


![Captura de tela_3-7-2025_172237_127 0 0 1](https://github.com/user-attachments/assets/63ed4e1a-36d8-4a0c-9fc6-c6085a1da692)
![Captura de tela_3-7-2025_172224_127 0 0 1](https://github.com/user-attachments/assets/943f7ccc-c7a0-44e0-9ff2-b9c0f11644ed)
