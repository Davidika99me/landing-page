# 📱 MobileDev - Landing Page de Serviços Mobile
**Desenvolvido por David Moreto**.

Uma aplicação Full Stack moderna e de alta conversão para agências de desenvolvimento. O projeto utiliza um **Tema Dark** sofisticado com acentos em azul neon, integrando uma interface elegante a um sistema de captura de leads persistente.

---

## 🚀 Funcionalidades Principais

O site foi estruturado seguindo as melhores práticas de UX e desenvolvimento:

1.  **Hero Section:** Título de impacto, descrição e CTA focado em conversão.
2.  **Serviços:** Grid responsivo com as frentes de atuação (Apps Nativos, UI/UX, Escalabilidade).
3.  **Sobre Nós:** Seção institucional com história, missão e uma **Galeria de Projetos** integrada.
4.  **Formulário de Contato:** Integração completa com o backend para envio de mensagens.
5.  **Persistência de Dados:** Todas as mensagens enviadas são salvas automaticamente em um banco de dados MySQL.

---

## 🛠️ Tecnologias Utilizadas

### Front-end
* **HTML5 / CSS3:** Estrutura semântica e estilização avançada (Flexbox/Grid).
* **JavaScript (ES6):** Manipulação de DOM, Scroll Suave e consumo de API (Fetch).

### Back-end
* **Node.js & Express:** Framework para criação da API REST.
* **MySQL:** Banco de dados relacional para armazenamento das mensagens.
* **CORS & Body-Parser:** Middlewares para segurança e tratamento de dados.

## Como rodar o projeto

* **Live Server** Instale a extensão do Live Server no VsCode para carregar a página web
* **server.js** Rode o arquivo server.js localizado na pasta /backend e certifique-se de configurar o seu banco de dados com suas credenciais.

---

## 📂 Estrutura do Projeto

```text
/
├── frontend/             # Interface do usuário
│   ├── index.html
│   ├── style.css
│   └── script.js
├── backend/              # Servidor e API
│   ├── server.js
│   ├── package.json
│   └── node_modules/     # Dependências do Node
└── README.md             # Documentação
