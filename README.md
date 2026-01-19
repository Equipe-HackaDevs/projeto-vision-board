# Vision Board Project | Equipe HackaDevs

> **Status:** Em Desenvolvimento (Sprint 1)

Este projeto é uma ferramenta de visualização de metas e inspirações, desenvolvida por nós da Equipe HackaDevs. Como primeiro projeto do nosso ecossistema, o foco principal é a transição fiel de um design do Figma para uma aplicação Full Stack, aplicando Metodologias Ágeis e padrões de Mercado.

## Sobre o Projeto

O Vision Board permite que usuários criem quadros visuais para organizar seus objetivos. O projeto utiliza React para uma interface dinâmica e Django para uma gestão robusta de dados e mídia.

- **Design Original:** Figma Community: https://www.figma.com/design/t8PFQb3PbHZWYU3WxvBgCa/Vision-Board-Project--Community-?node-id=49-40&t=FEMpqD2ofUBoKXQl-0
- **Arquitetura & Fluxos:** Miro Board: https://miro.com/app/board/uXjVGOmwuGo=/?share_link_id=570070081271
- **Gestão de Tarefas:** Jira (Scrum/Kanban) 

## Tech Stack

### Frontend
- **React.js:** Componentização e Gestão de Estado Global.
- **CSS3 (Pixel Perfect):** Estilização rigorosa baseada no Figma através de duplas JSX/CSS.
- **Axios:** Consumo da API REST.

### Backend (Core)
- **Python & Django:** Framework principal com foco em escalabilidade.
- **Django Rest Framework (DRF):** Construção de API REST padronizada.
- **PostgreSQL:** Banco de dados relacional de alta performance.
- **Simple-JWT:** Autenticação preparada para futura implementação.
- **Gestão de Mídia:** Backend responsável pelo carregamento e entrega da API de imagens.

## Instalação e Setup

Siga os passos abaixo para executar o projeto em seu ambiente local.

### Pré-requisitos
- **Node.js** & **npm**
- **Python 3.8+**
- **PostgreSQL**

### Backend

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Equipe-HackaDevs/projeto-vision-board
   cd nome-do-projeto/backend
   ```

2. **Crie e ative o ambiente virtual:**
   ```bash
   # Windows
   python -m venv venv
   venv\Scripts\activate

   # Linux/macOS
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Instale as dependências e execute as migrações:**
   ```bash
   pip install -r requirements.txt
   python manage.py migrate
   ```

4. **Inicie o servidor:**
   ```bash
   python manage.py runserver
   ```

### Frontend

1. **Acesse o diretório do frontend:**
   ```bash
   cd ../frontend
   ```

2. **Instale as dependências e inicie a aplicação:**
   ```bash
   npm install
   npm start
   ```

## Contribuição

Para detalhes sobre nosso workflow, padrões de commit e como abrir Pull Requests, consulte o nosso Guia de Contribuição.

## Visão do Tech Lead (Portfolio High-Level)

Neste projeto, a liderança foca em:

- **System Design:** Mapeamento da jornada do utilizador e arquitetura de fluxos.
- **Integração Cross-Stack:** Coordenação entre a entrega da API (Backend) e a renderização no Front.
- **Mentoria (Code Review):** Revisão de Pull Requests para garantir padrões de código e qualidade.

## Equipe HackaDevs

- **Bianca Caetano:** Tech Lead & Integração
- **Luiz Davi:** Backend Core & DB
- **Julie:** Arquitetura Técnica & Qualidade
- **Matheus:** Apoio, Documentação & QA
- **Squad Frontend:** Ana Beatriz Smaile, Amanda Vieira, Brenno, Breno Sant'Anna, Clarice Farias, Elena Lagroteria, Israel Santos e Victor de Souza.