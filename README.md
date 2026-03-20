# ImigraÁgil - Gestão AIMA Simplificada 🇵🇹

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

> Um portal web desenvolvido para simplificar e digitalizar o processo de renovação de autorizações de residência e agendamentos com a AIMA (Agência para a Integração, Migrações e Asilo).

![Screenshot do Projeto]

##  Funcionalidades Principais

* **Portal do Imigrante:** Registo seguro e login de utilizadores.
* **Gestão de Processos:** Submissão digital de pedidos de vistos/renovações com upload seguro de documentos (Passaportes, Registo Criminal, etc.).
* **Dashboard Inteligente:** Acompanhamento em tempo real do estado do processo (Rascunho, Em Análise, Aprovado, Rejeitado).
* **Agendamentos:** Geração automática de senhas para recolha presencial após aprovação do processo.
* **Geração de PDF:** Exportação do comprovativo oficial de agendamento em PDF utilizando a biblioteca `xhtml2pdf`.
* **Backoffice (Admin):** Painel de controlo executivo para os funcionários da AIMA gerirem os processos e visualizarem estatísticas do sistema.

##  Tecnologias Utilizadas

* **Backend:** Python 3, Django (Framework MVT)
* **Frontend:** HTML5, CSS3, Bootstrap 5, Bootstrap Icons
* **Base de Dados:** SQLite (Ambiente de Desenvolvimento)
* **Bibliotecas Extra:** `xhtml2pdf` (para relatórios)

##  Como correr o projeto localmente

Siga os passos abaixo para testar o projeto no seu computador:

**1. Clone o repositório:**
```bash
git clone https://github.com/SEU-USERNAME/imigraagil.git
cd imigraagil
