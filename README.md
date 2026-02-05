# ⏱️ Sistema de Ponto Automatizado em Python

Sistema simples e funcional para **registro de ponto de funcionários**, desenvolvido em **Python**, utilizando **planilhas Excel individuais por funcionário**, autenticação por **PIN criptografado** e possibilidade de geração de **executável (.exe)**.

Projeto ideal para pequenas empresas ou como **projeto de estudo e portfólio**, com foco em automação e boas práticas.

---

## 🚀 Funcionalidades

- 📋 Cadastro de funcionários
- 🔐 Autenticação por PIN criptografado
- ⏰ Registro automático de entrada e saída
- 📊 Cálculo automático de horas trabalhadas
- 📁 Uma planilha Excel por funcionário
- 📅 Registro diário organizado
- 🧾 Estrutura pronta para relatório mensal
- 🖥️ Interface via terminal (CLI)
- 📦 Geração de executável (.exe)

---

## 🛠️ Tecnologias Utilizadas

- Python 3
- openpyxl
- bcrypt
- datetime
- json
- PyInstaller

---

## 📂 Estrutura do Projeto

SistemaDePonto/
├── app.py
├── funcionarios/
│ ├── luiza.xlsx
│ ├── joao.xlsx
├── dados/
│ └── funcionarios.json
└── README.md

## ▶️ Como Executar

### 1️⃣ Clonar o repositório

git clone https://github.com/seu-usuario/sistema-de-ponto-python.git

### 2️⃣ Instalar dependências
pip install openpyxl bcrypt

### 3️⃣ Executar o sistema
python app.py

### 📦 Gerar Executável (.exe)
pip install pyinstaller
pyinstaller --onefile app.py

- o executável será criado em:
dist/app.exe

## 🔐 Segurança
- PINs armazenados de forma criptografada
- Nenhuma senha em texto puro
- Maior segurança para autenticação interna

## 📈 Melhorias Futuras
- Interface gráfica (Tkinter / PyQt)
- Envio automático de relatórios por e-mail
- Integração com banco de dados
- Controle de tentativas de login
- Leitura biométrica
- Painel administrativo

## 👩‍💻 Autora
Luiza de Paula Matos
Estudante de Ciência da Computação e Técnico em Informática

## 🔗 LinkedIn:
https://www.linkedin.com/in/luiza-matos-2b17a3356/
