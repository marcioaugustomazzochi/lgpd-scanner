# 📘 Documentação de Execução e Evidências – LGPD Scanner

## 📌 Visão Geral

Este documento apresenta o fluxo completo de execução do projeto **LGPD Scanner**, incluindo os comandos utilizados no ambiente Kali Linux e as evidências (prints) geradas durante cada etapa do processo.

O objetivo é demonstrar tecnicamente o funcionamento da ferramenta, desde a preparação do ambiente até a geração do relatório e do gráfico estatístico.

---

# 🖥️ 1. Preparação do Ambiente

## 📸 Evidência:

<img width="1920" height="936" alt="image" src="https://github.com/user-attachments/assets/2b7dfe21-e05a-4679-8982-09068f6a7059" />

## 🔧 Comandos Executados:

python3 -m venv venv  

source venv/bin/activate  

pip install -r requirements.txt  

---

# 🔍 2. Execução do Scanner

<img width="1920" height="936" alt="image" src="https://github.com/user-attachments/assets/ff4c7d61-95aa-4958-b80b-c6af1c93880f" />

## 🔧 Comando Executado:

python3 scanner.py  

---

# 📊 3. Geração do Relatório

## 📸 Evidência:

<img width="1920" height="936" alt="image" src="https://github.com/user-attachments/assets/2abb6e5c-3aa0-4e2e-abeb-392c61802786" />

Arquivo gerado:

reports/relatorio_scan.csv  

---

# 📈 4. Geração do Gráfico Estatístico

## 📸 Evidência:

<img width="1920" height="936" alt="Print 4" src="https://github.com/user-attachments/assets/b6a7cb93-658b-4560-a3c6-c2ebee356f0b" />

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
