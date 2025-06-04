# 🛠 ProjetoV&V - Gerenciamento de Pessoas

## 📌 Descrição
Projeto para gerenciamento de cadastro, edição, listagem e remoção de pessoas usando Python, Flask e Behave para testes BDD.

## 🚀 Tecnologias Utilizadas
- 🐍 Python
- ⚡ Flask (Back-end)
- 🧪 Behave (Testes BDD)
- 📦 SQLite (Banco de Dados)

## 📂 Estrutura do Projeto
```
ProjetoV&V/
│── app.py                # Arquivo principal do servidor Flask
│── requirements.txt      # Dependências do projeto
│── features/             # Testes BDD
│   ├── cadastrar_pessoa.feature
│   ├── editar_pessoa.feature
│   ├── listar_pessoas.feature
│   ├── remover_pessoa.feature
│   ├── steps/            # Implementação dos testes
│   │   ├── cadastro_steps.py
│   │   ├── editar_steps.py
│   │   ├── listar_steps.py
│   │   ├── remover_steps.py
│── static/               # Arquivos estáticos (CSS, JS)
│── templates/            # Templates HTML
│── database.db           # Banco de dados SQLite
```

## ⚙️ **Instalação**
1️⃣ **Clone o repositório**:
```bash
git clone https://github.com/seu-usuario/ProjetoV&V.git
cd ProjetoV&V
```

2️⃣ **Instale as dependências**:
```bash
pip install -r requirements.txt
```

3️⃣ **Inicie o servidor**:
```bash
python app.py
```

## 🧪 **Rodando os Testes**
```bash
python -m behave
```


