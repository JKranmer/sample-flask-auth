# 🔐 Sample Flask Auth

Uma API de autenticação robusta desenvolvida com Flask, implementando funcionalidades de registro, login e gerenciamento de sessões com banco de dados.

## 📋 Descrição

Este projeto demonstra a implementação de um sistema de autenticação completo usando Flask, incluindo:

- Sistema de registro e login de usuários
- Autenticação de sessões com Flask-Login
- Integração com banco de dados usando SQLAlchemy
- Proteção de rotas e middleware de segurança
- Gerenciamento seguro de senhas com hash

## 🛠️ Tecnologias Utilizadas

- **Flask 2.3.0** - Framework web minimalista
- **Flask-SQLAlchemy 3.1.1** - ORM para manipulação do banco de dados
- **Flask-Login 0.6.2** - Gerenciamento de sessões e autenticação
- **Werkzeug 2.3.0** - Utilitários WSGI e ferramentas de segurança

## 📁 Estrutura do Projeto

```
sample-flask-auth/
├── .venv/              # Ambiente virtual Python
├── README.md           # Documentação do projeto
├── requirements.txt    # Dependências do projeto
└── .gitignore         # Arquivos ignorados pelo Git
```

## 🚀 Como Executar

### Pré-requisitos

- Python 3.7 ou superior
- pip (gerenciador de pacotes Python)

### Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/JKranmer/sample-flask-auth.git
   cd sample-flask-auth
   ```

2. **Crie e ative o ambiente virtual**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Linux/Mac
   # ou
   .venv\Scripts\activate     # Windows
   ```

3. **Instale as dependências**
   ```bash
   pip install -r requirements.txt
   ```

4. **Execute a aplicação**
   ```bash
   python app.py
   ```

   A aplicação estará disponível em `http://localhost:5000`

## 👨‍💻 Autor

**JKranmer**
- GitHub: [@JKranmer](https://github.com/JKranmer)

## 📞 Suporte

Se você tiver alguma dúvida ou problema, por favor abra uma [issue](https://github.com/JKranmer/sample-flask-auth/issues) no GitHub.
