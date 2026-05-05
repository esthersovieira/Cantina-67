# 🍝 Cantina 67

Sistema web para gerenciamento de uma cantina, desenvolvido com **Django**, focado em organização de pedidos, controle de produtos e uma experiência simples e eficiente para usuários e administradores.

---

## 📌 Sobre o Projeto

O **Cantina 67** é uma aplicação web criada para facilitar o dia a dia de cantinas escolares ou comerciais, permitindo:

* **Cadastro e gerenciamento de produtos:** Controle total sobre o que é vendido.
* **Controle de pedidos:** Fluxo organizado desde a escolha até a entrega.
* **Administração de usuários:** Diferentes níveis de acesso para clientes e equipe.
* **Interface intuitiva:** Navegação simplificada para garantir agilidade no atendimento.

O projeto foi pensado para ser escalável, organizado e de fácil manutenção, seguindo as melhores práticas do framework Django.

---

## 🚀 Tecnologias Utilizadas

* **Python 3** - Linguagem base do projeto.
* **Django** - Framework web robusto para o backend.
* **SQLite** - Banco de dados padrão (facilmente substituível por PostgreSQL ou MySQL).
* **HTML5 + CSS3** - Estruturação e estilização.
* **Bootstrap** - Framework de CSS para garantir responsividade.

---

## ⚙️ Funcionalidades

- [x] **Cadastro de produtos:** Inclusão de fotos, preços e descrições.
- [x] **Listagem de itens:** Menu organizado para visualização rápida.
- [x] **Sistema de pedidos:** Carrinho de compras e finalização.
- [x] **Sistema de pagamentos:** Módulo dedicado para transações.
- [x] **Painel Administrativo:** Gerenciamento via Django Admin.
- [x] **Autenticação:** Sistema de login/logout seguro para clientes.
- [x] **Categorização:** Organização de itens (ex: Bebidas, Salgados, Doces).

---

## 📂 Estrutura do Projeto

```text
cantina67/
│
├── cantina67/          # Configurações globais do projeto (settings, urls)
├── pagamentos/         # Módulo de processamento de pagamentos
├── clientes/           # Gerenciamento de perfis e autenticação de usuários
├── setup/              # App principal / Configurações iniciais
├── produtos/           # CRUD e lógica de exibição de produtos
├── pedidos/            # Lógica de criação e histórico de pedidos
├── templates/          # Arquivos HTML (Frontend)
├── static/             # Arquivos estáticos (CSS, JS e imagens)
├── db.sqlite3          # Banco de dados local
└── manage.py           # Utilitário de linha de comando do Django
```

---

## 🔧 Instalação e Execução

Siga os passos abaixo para rodar o projeto localmente:

### 1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/cantina67.git
cd cantina67
```

### 2. Crie e ative um ambiente virtual
```bash
# Criar o ambiente
python -m venv venv

# Ativar (Windows)
venv\Scripts\activate

# Ativar (Linux/Mac)
source venv/bin/activate
```

### 3. Instale as dependências
```bash
pip install -r requirements.txt
```

### 4. Execute as migrações do banco de dados
```bash
python manage.py migrate
```

### 5. Crie um superusuário (Admin)
```bash
python manage.py createsuperuser
```

### 6. Inicie o servidor
```bash
python manage.py runserver
```

Agora, acesse:
* **Aplicação:** [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
* **Painel Admin:** [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

---

## 🎨 Interface

O sistema possui uma interface simples, limpa e responsiva. O uso de **Bootstrap** permite que a aplicação seja utilizada em dispositivos móveis e desktops sem perda de usabilidade.

---

## 🧪 Melhorias Futuras

- [ ] Integração com gateways de pagamentos online (Pix, Cartão) 💳
- [ ] Criação de API REST com **Django REST Framework**
- [ ] Sistema de relatórios financeiros e de estoque 📊
- [ ] Notificações em tempo real para pedidos prontos 🔔
- [ ] Desenvolvimento de um aplicativo mobile (React Native ou Flutter) 📱

---

## 🤝 Contribuição

Contribuições tornam a comunidade open source um lugar incrível!
1. Faça um **Fork** do projeto.
2. Crie uma **Branch** para sua feature (`git checkout -b feature/minha-feature`).
3. Dê um **Commit** nas suas mudanças (`git commit -m 'Adicionando nova feature'`).
4. Faça um **Push** para a Branch (`git push origin feature/minha-feature`).
5. Abra um **Pull Request**.

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 💡 Autor

Desenvolvido com ☕ e 💻 por **Esther Sophia Vieira**.
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/esthersovieira)