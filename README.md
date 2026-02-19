# 🛡️ LGPD Scanner  

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue">
  <img src="https://img.shields.io/badge/Status-Concluído-success">
  <img src="https://img.shields.io/badge/License-MIT-green">
</p>

---

## 🔎 Sobre o Projeto

O **LGPD Scanner** é uma ferramenta desenvolvida em Python para detectar automaticamente dados sensíveis em arquivos de texto, como:

- 📧 Emails  
- 🆔 CPF  
- 💳 Credit Card Numbers  

O sistema gera relatórios estruturados e gráficos estatísticos para apoiar processos de adequação à **Lei Geral de Proteção de Dados (LGPD)**.

---

## ⚙️ Funcionalidades

✔️ Varredura automática de arquivos  
✔️ Identificação via Expressões Regulares (Regex)  
✔️ Classificação de nível de risco  
✔️ Geração de relatório CSV  
✔️ Geração de gráfico estatístico  

---

## 🚀 Instalação

~~~bash
git clone https://github.com/marcioaugustomazzochi/lgpd-scanner.git
cd lgpd-scanner

python3 -m venv venv
source venv/bin/activate

pip install -r requirements.txt
~~~

---

## ▶️ Execução

~~~bash
python3 scanner.py
~~~

Após a execução:

- 📄 O relatório será salvo em `reports/relatorio_scan.csv`
- 📊 O gráfico será salvo em `reports/grafico_tipo.png`

Para gerar apenas o gráfico:

~~~bash
python3 gerar_grafico.py
~~~

---

## 📂 Estrutura do Projeto

~~~
lgpd_scanner/
│
├── data/
├── reports/
├── screenshots/
├── scanner.py
├── gerar_grafico.py
├── requirements.txt
└── README.md
~~~

---

## 🛠 Tecnologias Utilizadas

- Python 3  
- Pandas  
- Matplotlib  
- Expressões Regulares  
- Ric 
- Git & GitHub  

---

## 🎯 Objetivo Técnico

Este projeto demonstra:

- Manipulação de arquivos  
- Processamento de dados com Pandas  
- Uso de Expressões Regulares  
- Geração de relatórios automatizados  
- Criação de visualizações com Matplotlib  
- Organização de projeto para portfólio  

---

## 📌 Melhorias Futuras

- 🌐 Interface Web (Flask ou FastAPI)  
- 📊 Dashboard interativo  
- 📄 Exportação em PDF  
- 🗄 Integração com banco de dados  
- 🔍 Análise recursiva de diretórios  

---

## 👨‍💻 Autor

**Marcio Augusto Mazzochi**  
Tecnólogo em Segurança da Informação  
MBA em Cibersegurança e Gestão de Riscos (cursando)

---

## 📜 Licença

Este projeto está sob a licença MIT.
