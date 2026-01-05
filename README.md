#AAD&E - Automação de analise de dados e envios.

Automação de download, análise e envio automático de relatórios extraídos de sistemas internos — entrega de resultados formatados diretamente no corpo do e-mail.

---

## 📄 Descrição do Projeto

O **AAD&E** é um script desenvolvido em Python para automatizar a rotina de extração e análise de dados em empresas.  
Ele:

- acessa um site ou sistema interno da empresa,  
- baixa planilhas contendo dados (Excel / CSV ),  
- processa e analisa esses dados com a biblioteca `pandas`,  
- gera um resumo formatado dos resultados,  
- envia automaticamente um e-mail com o relatório diretamente no corpo da mensagem.  

Esta automação é ideal para tarefas repetitivas, economizando tempo e reduzindo erros humanos no manuseio manual de planilhas e relatórios.

---

## ✅ Funcionalidades principais

- Login/acesso automático ao sistema da empresa (via automação web ou download manual programado)  
- Download automatizado da planilha de dados  
- Processamento e análise de dados com `pandas`  
- Cálculos, filtros, consolidações e limpeza de dados — conforme a necessidade do relatório  
- Montagem de relatório resumido com os principais indicadores e métricas  
- Envio automático por e-mail (via SMTP, Outlook, ou método configurado), com o relatório embutido no corpo do e-mail  

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

- **Python 3** — linguagem principal do projeto  
- **pandas** — manipulação e análise de dados (dataframes, limpeza, agregações) :contentReference[oaicite:0]{index=0}  
- **smtplib** (ou biblioteca equivalente) — envio de e-mails via SMTP/servidor de e-mail :contentReference[oaicite:1]{index=1}  
- **openpyxl** (caso use planilhas Excel) — leitura e manipulação de arquivos `.xlsx`  
- **pyautogui** — automação de navegação e download, caso o sistema interno não ofereça API direta  
- Outras bibliotecas padrão de Python conforme necessário (`os`, `datetime`, etc.)

---



