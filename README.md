🩸 Gerenciamento de Doadores - Flask






Sistema web simples para gerenciar doadores de sangue, feito em Python com Flask e SQLite. Possui autenticação de usuários, roles e CRUD completo de doadores.

💡 Funcionalidades

Cadastro, edição e remoção de doadores

Validação automática de idade e peso

Sistema de login/logout com roles:

Admin: pode cadastrar, editar e deletar doadores

Recepcionista: pode cadastrar e editar, mas não deletar

Feedback visual via flash messages

Armazenamento de dados em SQLite

🛠 Tecnologias usadas

Python 3.x

Flask

Flask SQLAlchemy

Werkzeug (hashing de senhas)

SQLite

⚙️ Requisitos

Python 3.x instalado

Instalar dependências com:

pip install Flask Flask-SQLAlchemy Werkzeug

🚀 Como rodar o projeto

Clone este repositório:

git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio


Instale as dependências:

pip install -r requirements.txt


Execute o aplicativo:

python app.py


Abra no navegador:

http://127.0.0.1:5000/
