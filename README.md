# 🏦 Sistema Bancário Avançado

> Simulação de operações bancárias com funcionalidades como criação de contas, depósitos, saques, transferências e geração de extrato, com lógica modular e persistência de dados.

---

## 📋 Sumário

- [🚀 Funcionalidades](#-funcionalidades)
- [⚙️ Pré-requisitos](#️-pré-requisitos)
- [📦 Instalação](#-instalação)
- [▶️ Execução](#️-execução)
- [🧠 Arquitetura](#-arquitetura)
- [🧪 Casos de Uso](#-casos-de-uso)
- [🤝 Contribuição](#-contribuição)

---

## 🚀 Funcionalidades

- [x] Criar e excluir contas
- [x] Realizar depósitos, saques e transferências
- [x] Ver saldo e extrato de uma conta
- [x] Persistência de dados (arquivo/SQLite)
- [x] Validação de operações
- [ ] Autenticação de usuário (em desenvolvimento)

---

## ⚙️ Pré-requisitos

- Python 3.10 ou superior
- pip instalado

---

## 📦 Instalação

```bash/powershell
# Clone o repositório
git clone https://github.com/lavih2048/sistema-bancario-avancado.git

# Acesse a pasta do projeto
cd sistema-bancario-avancado

# Instale dependências (se houver)
pip install -r requirements.txt
```
---

## ▶️ Execução

# Execute o sistema
python main.py

---

## 🧠 Arquitetura

sistema-bancario-avancado/
├── main.py              # Arquivo principal
├── models/              # Entidades como Conta, Cliente, Transação
├── services/            # Regras de negócio (depósitos, saques, etc)
├── db/                  # Persistência de dados
├── controllers/         # Lógica de interface/entrada
├── tests/               # Testes automatizados
└── README.md

---

## 🧪 Casos de Uso

> criar_conta 1234 João
Conta 1234 criada com sucesso.

> depositar 1234 500
Depósito de R$ 500 efetuado.

> transferir 1234 5678 200
Transferência de R$ 200 realizada de João para Maria.

> extrato 1234
Saldo atual: R$ 300
Últimas transações:
- Depósito: R$ 500
- Transferência: -R$ 200

---

## 🤝 Contribuição

1. Fork o repositório

2. Crie uma branch: git checkout -b feature/nome-da-feature

3. Commit suas mudanças: git commit -m 'feat: nova funcionalidade'

4. Push para a branch: git push origin feature/nome-da-feature

5. Abra um Pull Request

---
