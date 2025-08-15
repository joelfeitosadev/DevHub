# DevHub - Conceito de Rede Social para Desenvolvedores

![GitHub languages](https://img.shields.io/github/languages/top/joelfeitosadev/DevHub?style=flat-square)
![GitHub last commit](https://img.shields.io/github/last-commit/joelfeitosadev/DevHub?style=flat-square)
![License](https://img.shields.io/github/license/joelfeitosadev/DevHub?style=flat-square)

Um protótipo de interface para o "DevHub", um conceito de feed de rede social focado na comunidade de desenvolvedores. Este projeto foi criado como um estudo prático para aplicar e demonstrar habilidades avançadas em desenvolvimento front-end, incluindo a customização de frameworks, automação de deploy e criação de layouts complexos e responsivos.

## ✨ Funcionalidades Principais

* **Tema Dark por Padrão:** Interface moderna e confortável para os olhos, utilizando o sistema de temas do Bootstrap.
* **Layout Responsivo:** Um layout de três colunas para desktops que se adapta de forma fluida para tablets e dispositivos móveis.
* **Header Complexo:** Barra de navegação com links, um campo de busca funcional e um dropdown de opções de usuário.
* **Feed de Posts:** Componentes de card para exibir posts de usuários de forma organizada.
* **Componentes Interativos:** Uso de badges, dropdowns e botões para uma experiência de usuário rica.

## 🛠️ Tecnologias e Metodologias Utilizadas

Este projeto foi construído com um foco em práticas modernas de desenvolvimento front-end.

* **Ambiente de Desenvolvimento:**
    * **[Vite](https://vitejs.dev/):** Ferramenta de build para um desenvolvimento rápido com Hot Module Replacement (HMR).
    * **[SASS](https://sass-lang.com/):** Pré-processador CSS para customização avançada e organização dos estilos.
* **Framework e Bibliotecas:**
    * **[Bootstrap 5](https://getbootstrap.com/):** Utilizado como base para o sistema de grid, componentes e utilitários.
    * **[Bootstrap Icons](https://icons.getbootstrap.com/):** Biblioteca de ícones SVG.
* **Versionamento:**
    * **Git & GitHub:** Para controle de versão.
    * **Conventional Commits:** Padrão de commits para um histórico limpo e organizado.

## 🎨 Customização com SASS

Uma parte central do projeto foi a customização profunda do Bootstrap via SASS, em vez de apenas sobrescrever o CSS.

* O arquivo `_custom-variables.scss` centraliza a modificação de variáveis SASS do Bootstrap (cores, fontes, bordas, etc.).
* O `_bootstrap-components.scss` importa apenas os componentes necessários do framework, otimizando o tamanho final do arquivo CSS.
* O `style.scss` orquestra a importação de todos os arquivos na ordem correta, garantindo que as customizações sejam aplicadas corretamente.

## 🚀 Rodando o Projeto Localmente

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/joelfeitosadev/DevHub.git
    ```

2.  **Acesse a pasta do projeto:**
    ```bash
    cd DevHub
    ```

3.  **Instale as dependências:**
    ```bash
    npm install
    ```

4.  **Inicie o servidor de desenvolvimento:**
    ```bash
    npm run dev
    ```

5.  Abra seu navegador e acesse `http://localhost:5173` (ou a porta que o Vite indicar).

## 📄 Licença

Este projeto está sob a licença MIT.