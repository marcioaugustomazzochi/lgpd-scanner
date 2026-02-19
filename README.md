# 🛡️ LGPD Scanner

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Status](https://img.shields.io/badge/Status-Concluído-success)
![License](https://img.shields.io/badge/License-MIT-green)

Ferramenta desenvolvida em **Python** para identificar dados sensíveis em arquivos de texto, como:

- 📧 Emails  
- 🆔 CPF  
- 💳 Cartões de crédito  

O sistema gera relatórios estruturados e gráficos estatísticos para auxiliar na conformidade com a **Lei Geral de Proteção de Dados (LGPD)**.

---

## 🚀 Instalação

```bash
# Criar diretório do projeto
mkdir -p ~/lgpd_scanner
cd ~/lgpd_scanner

# Criar ambiente virtual
python3 -m venv venv
source venv/bin/activate

# Instalar dependências
pip install pandas matplotlib rich
▶️ Execução
python3 scanner.py
O sistema irá:

✔️ Analisar arquivos da pasta data/

✔️ Identificar dados sensíveis

✔️ Classificar o nível de risco

✔️ Gerar relatório CSV automaticamente

📊 Relatório Gerado
O relatório é salvo em:

reports/relatorio_scan.csv
Ele contém:

Arquivo analisado

Tipo de dado encontrado

Valor identificado

Nível de risco (Médio ou Alto)

📸 Exemplo do relatório:
![Relatório CSV](screenshots/2_relatorio_csv.png)
Ou simplesmente:


📈 Geração de Gráficos
Para visualizar estatísticas dos dados encontrados:

python3 gerar_grafico.py
O gráfico será salvo em:

reports/grafico_tipo.png
📸 Distribuição dos tipos de dados:

📂 Estrutura do Projeto
lgpd_scanner/
│
├── data/
├── reports/
├── screenshots/
│   ├── 1_terminal_scan.png
│   ├── 2_relatorio_csv.png
│   └── 3_grafico.png
│
├── scanner.py
├── gerar_grafico.py
├── requirements.txt
└── README.md
🛠 Tecnologias Utilizadas
Python 3

Pandas

Matplotlib

Regex

Rich

Git & GitHub

🔐 Objetivo do Projeto
Demonstrar como automatizar a detecção de dados sensíveis em arquivos locais, gerar relatórios estruturados e produzir visualizações gráficas para apoiar processos de adequação à LGPD.

📌 Melhorias Futuras
Interface Web

Dashboard interativo

Exportação em PDF

Integração com banco de dados

Análise recursiva de diretórios

👨‍💻 Autor
Seu Nome Aqui

📜 Licença
Este projeto está sob a licença MIT.
