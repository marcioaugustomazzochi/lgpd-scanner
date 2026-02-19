# 📘 Documentação de Execução e Evidências – LGPD Scanner

## 📌 Visão Geral

Este documento apresenta o fluxo completo de execução do projeto **LGPD Scanner**, incluindo os comandos utilizados no ambiente Kali Linux e as evidências (prints) geradas durante cada etapa do processo.

O objetivo é demonstrar tecnicamente o funcionamento da ferramenta, desde a preparação do ambiente até a geração do relatório e do gráfico estatístico.

---

# 🖥️ 1. Preparação do Ambiente

## 📸 Evidência:

<img src="https://github.com/user-attachments/assets/c31d1269-66f8-487b-b021-69bf059e9e9d" width="900">

## 🔧 Comandos Executados:

python3 -m venv venv  

source venv/bin/activate  

pip install -r requirements.txt  

---

# 🔍 2. Execução do Scanner

## 📸 Evidência:

<img src="https://github.com/user-attachments/assets/5e677bf1-ff77-462b-aaa7-5435d30841fd" width="900">

## 🔧 Comando Executado:

python3 scanner.py  

---

# 📊 3. Geração do Relatório

## 📸 Evidência:

<img src="https://github.com/user-attachments/assets/dbb2b01b-9dfc-45e7-a4ab-2db3babd9f3e" width="900">

Arquivo gerado:

reports/relatorio_scan.csv  

---

# 📈 4. Geração do Gráfico Estatístico

## 📸 Evidência:

<img src="https://github.com/user-attachments/assets/e24a507e-d416-4fe3-be8f-4dc0ed9870e7" width="900">

Comando executado:

python3 gerar_grafico.py  

---

# 🎯 Conclusão Técnica

O projeto demonstra:

✔ Implementação prática de análise de dados sensíveis  
✔ Aplicação de conceitos da LGPD  
✔ Automação de geração de relatórios  
✔ Organização estrutural de projeto  
✔ Documentação técnica adequada  

---

# 👨‍💻 Autor

Marcio Augusto Mazzochi  
Tecnólogo em Segurança da Informação  
MBA em Cibersegurança e Gestão de Riscos (cursando)
