# 💻 FC - Web Developer Portfolio

![Static Badge](https://img.shields.io/badge/Status-Em_Desenvolvimento-cyan)
![Static Badge](https://img.shields.io/badge/Maintained%3F-yes-green)
![Static Badge](https://img.shields.io/badge/UI-Minimalist-black)

Uma landing page de portfólio moderna, minimalista e de alta performance, desenvolvida para destacar projetos e habilidades de desenvolvimento web.



## 🛠️ Tecnologias
Este projeto utiliza o que há de mais moderno em estilização utilitária e performance:

* **[Tailwind CSS](https://tailwindcss.com/):** Framework para estilização rápida e responsiva.
* **JavaScript (Vanilla):** Lógica customizada para persistência de tema e manipulação de DOM.
* **Google Fonts:** Tipografia *Poppins* para leitura clara.
* **HTML5 Semântico:** Para melhor indexação em motores de busca (SEO).

## 🌗 Funcionalidade de Tema (Dark/Light Mode)
O sistema de temas foi implementado focando na experiência do usuário (UX):

1.  **Detecção Automática:** O site identifica se o sistema operacional do usuário está em modo escuro.
2.  **Persistência:** A escolha do usuário (claro ou escuro) é salva no `LocalStorage`.
3.  **Anti-Flash:** Um script de bloqueio no cabeçalho garante que a página não "pisque" em branco ao ser carregada em modo escuro.

## 📂 Estrutura do Projeto
```text
├── index.html          # Arquivo principal (Estrutura e Tailwind Config)
├── js/
│   └── theme-toggle.js # Lógica de alternância de tema
└── css/
    └── style.css       # Estilos residuais