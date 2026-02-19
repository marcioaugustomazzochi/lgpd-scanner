# 📘 Documentação de Execução e Evidências – LGPD Scanner

## 📌 Visão Geral

Este documento apresenta o fluxo completo de execução do projeto **LGPD Scanner**, incluindo os comandos utilizados no ambiente Kali Linux e as evidências (prints) geradas durante cada etapa do processo.

O objetivo é demonstrar tecnicamente o funcionamento da ferramenta, desde a preparação do ambiente até a geração do relatório e do gráfico estatístico.

---

# 🖥️ 1. Preparação do Ambiente

## 📸 Evidência:
screenshots/1_terminal_scan.png <img width="1920" height="936" alt="image" src="https://github.com/user-attachments/assets/c31d1269-66f8-487b-b021-69bf059e9e9d" />

## 🔧 Comandos Executados:

python3 -m venv venv

Criação de um ambiente virtual isolado para garantir que as dependências do projeto não interfiram no sistema operacional.

source venv/bin/activate

Ativação do ambiente virtual.

pip install -r requirements.txt

Instalação das bibliotecas necessárias para execução do projeto.

---

# 🔍 2. Execução do Scanner

## 📸 Evidência:
screenshots/1_terminal_scan.png <img width="1920" height="936" alt="image" src="https://github.com/user-attachments/assets/5e677bf1-ff77-462b-aaa7-5435d30841fd" />

## 🔧 Comando Executado:

python3 scanner.py

## ⚙️ Funcionamento:

Durante esta etapa, o sistema:

- Percorre os arquivos contidos na pasta `data/`
- Analisa o conteúdo em busca de padrões sensíveis
- Identifica possíveis:
  - CPFs
  - Endereços de e-mail
  - Outros dados pessoais
- Classifica o nível de risco
- Gera automaticamente um relatório em formato CSV

---

# 📊 3. Geração do Relatório

## 📸 Evidência:
screenshots/2_relatorio_csv.png <img width="1920" height="936" alt="Relatório 4" src="https://github.com/user-attachments/assets/dbb2b01b-9dfc-45e7-a4ab-2db3babd9f3e" />

## 📂 Arquivo Gerado:

reports/relatorio_scan.csv

## 📋 Estrutura do Relatório:

O relatório contém:

- Nome do arquivo analisado
- Tipo de dado sensível identificado
- Valor encontrado
- Classificação de risco

O arquivo pode ser aberto em ferramentas como Excel ou LibreOffice para análise detalhada.

---

# 📈 4. Geração do Gráfico Estatístico

## 📸 Evidência:
screenshots/3_grafico.png <img width="1920" height="936" alt="image" src="https://github.com/user-attachments/assets/e24a507e-d416-4fe3-be8f-4dc0ed9870e7" />

## 🔧 Comando Executado:

python3 gerar_grafico.py

## 📊 Funcionamento:

O script realiza:

- Leitura do arquivo relatorio_scan.csv
- Agrupamento dos dados por tipo de informação sensível
- Geração automática de gráfico estatístico
- Salvamento da imagem em:

reports/grafico_tipo.png

Esta etapa permite visualização quantitativa das ocorrências detectadas.

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
