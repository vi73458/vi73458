# 🚀 Controle de Gastos – Gerencie Suas Finanças com Facilidade 💸

![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Versão](https://img.shields.io/badge/vers%C3%A3o-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Django](https://img.shields.io/badge/backend-Django-%23092E20?logo=django)
![Bootstrap](https://img.shields.io/badge/frontend-Bootstrap-%237952B3?logo=bootstrap)

<img src="https://i.imgur.com/8Km9tLL.png" alt="Capa do projeto" style="width: 100%; border-radius: 8px;">

## 📱 Sobre o Projeto

**Controle de Gastos** é uma aplicação web intuitiva para te ajudar a registrar, organizar e visualizar seus gastos de forma prática e visual. Criado com [Django](w) e [Bootstrap](w), o projeto foca em **acessibilidade, performance e usabilidade**.

---

## 🔥 Funcionalidades

✅ Cadastro e login de usuário  
✅ Adição e edição de gastos  
✅ Dashboard com resumo de despesas  
✅ Gráficos interativos com [Chart.js](w)  
✅ Filtros por data, categoria e valor  
✅ Layout responsivo

---

## 🖼️ Prévia

<img src="https://i.imgur.com/8s7zPhl.png" alt="Dashboard" width="700">

---

## 🧠 Tecnologias Utilizadas

- 💡 [Python](w) + [Django](w)
- 🎨 [HTML](w) + [CSS](w) + [Bootstrap](w)
- 📊 [Chart.js](w)
- 🗃️ [SQLite](w) (ou [PostgreSQL](w) na produção)

---

## 🚀 Como Rodar Localmente

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/controle-gastos.git
cd controle-gastos

# Crie o ambiente virtual
python -m venv venv
source venv/bin/activate  # No Windows use: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt

# Rode o servidor
python manage.py migrate
python manage.py runserver
