🍝 Cantina 67

Sistema web para gerenciamento de uma cantina, desenvolvido com Django, focado em organização de pedidos, controle de produtos e uma experiência simples e eficiente para usuários e administradores.

📌 Sobre o Projeto

O Cantina 67 é uma aplicação web criada para facilitar o dia a dia de cantinas, permitindo:

Cadastro e gerenciamento de produtos
Controle de pedidos
Administração de usuários
Interface intuitiva para clientes e equipe

O projeto foi pensado para ser escalável, organizado e de fácil manutenção.

🚀 Tecnologias Utilizadas
Python 3
Django
SQLite (padrão, pode ser alterado)
HTML5 + CSS3
Bootstrap (opcional)
⚙️ Funcionalidades

✔️ Cadastro de produtos
✔️ Listagem de itens disponíveis
✔️ Sistema de pedidos
✔️ Sistema de pagamentos
✔️ Painel administrativo (Django Admin)
✔️ Autenticação de usuários
✔️ Organização por categorias

📂 Estrutura do Projeto
cantina67/
│
├── cantina67/        # Configurações do projeto
├── pagamentos        #Sistema de pagamentos
├── clientes          #Login dos clientes
├── setup/            # App principal
├── produtos/         # Gerenciamento de produtos
├── pedidos/          # Sistema de pedidos
├── templates/        # Arquivos HTML
├── static/           # CSS, JS e imagens
├── db.sqlite3        # Banco de dados
└── manage.py

🔧 Instalação e Execução
1. Clone o repositório
git clone https://github.com/seu-usuario/cantina67.git
cd cantina67
2. Crie um ambiente virtual
python -m venv venv

Ative o ambiente:

Windows:
venv\Scripts\activate
Linux/Mac:
source venv/bin/activate
3. Instale as dependências
pip install -r requirements.txt
4. Execute as migrações
python manage.py migrate
5. Crie um superusuário
python manage.py createsuperuser
6. Inicie o servidor
python manage.py runserver

Acesse no navegador:

http://127.0.0.1:8000/

Admin:

http://127.0.0.1:8000/admin/


🎨 Interface

O sistema possui uma interface simples e responsiva, podendo ser facilmente customizada com frameworks como Bootstrap ou Tailwind.

🧪 Melhorias Futuras
Integração com pagamentos online 💳
API REST com Django REST Framework
Sistema de relatórios 📊
Notificações em tempo real 🔔
Aplicativo mobile 📱
🤝 Contribuição

Contribuições são bem-vindas!

Fork o projeto
Crie uma branch (git checkout -b feature/minha-feature)
Commit suas mudanças (git commit -m 'Minha nova feature')
Push (git push origin minha-feature)
Abra um Pull Request
📄 Licença

Este projeto está sob a licença MIT.
Sinta-se livre para usar e modificar.

💡 Autor

Desenvolvido por Esther Sophia Vieira 🚀