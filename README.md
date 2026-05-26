<div align="center">

# 🌐 Simplefolio — Portfólio Pessoal

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Publicado-22863a?style=for-the-badge&logo=github)](https://pmbfsa.github.io/simplefolio/) [![License: GPL v3](https://img.shields.io/badge/Licen%C3%A7a-GPLv3-blue?style=for-the-badge&logo=gnu)](https://www.gnu.org/licenses/gpl-3.0) [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript) [![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)](https://sass-lang.com/) [![Parcel](https://img.shields.io/badge/Parcel-B0731B?style=for-the-badge&logo=parcel&logoColor=white)](https://parceljs.org/)

Portfólio pessoal de **Paulo Márcio**, desenvolvido para apresentar projetos publicados e facilitar o contato profissional.

**[→ Acessar o portfólio](https://pmbfsa.github.io/simplefolio/)**

</div>

---

## 📋 Sobre o Projeto

Este portfólio foi desenvolvido com foco em **simplicidade e performance**, reunindo em um único lugar:

- 🗂️ Links para projetos publicados
- 📄 Acesso ao currículo
- 📞 Botões de contato direto via telefone e e-mail
- 📱 Layout responsivo para todos os dispositivos
- ✨ Animações para uma experiência mais fluida

---

## 📸 Screenshot

<div align="center">
  <img src="./examples/example.png" alt="Preview do portfólio de Paulo Márcio" width="100%">
</div>

---

## 🚀 Tecnologias Utilizadas

| Tecnologia     | Função                                              |
| -------------- | --------------------------------------------------- |
| **HTML5**      | Estrutura e marcação semântica das páginas          |
| **CSS3**       | Estilização e layout responsivo                     |
| **Sass/SCSS**  | Pré-processamento CSS com variáveis e modularização |
| **JavaScript** | Interatividade e comportamento dinâmico             |
| **Parcel**     | Bundler para empacotamento e build do projeto       |

---

## ✨ Funcionalidades

- **Responsivo** — adaptado para dispositivos móveis, tablets e desktops
- **Animações** — transições e efeitos visuais para melhorar a experiência do usuário
- **Contato direto** — botões de atalho para ligação telefônica e envio de e-mail
- **Acesso ao currículo** — link direto para download ou visualização do CV
- **Links de projetos** — seção dedicada aos projetos publicados

---

## 🛠️ Como Rodar Localmente

### Pré-requisitos

- [Node.js](https://nodejs.org/) (versão LTS recomendada)
- [npm](https://www.npmjs.com/)

### Passos

```bash
# 1. Clone o repositório
git clone https://github.com/pmbfsa/simplefolio.git

# 2. Acesse a pasta do projeto
cd simplefolio

# 3. Instale as dependências
npm install

# 4. Inicie o servidor de desenvolvimento
npm run start
```

O projeto estará disponível em `http://localhost:1234` (porta padrão do Parcel).

---

## 📦 Build para Produção

```bash
npm run build
```

Os arquivos otimizados serão gerados na pasta `docs/`, que é utilizada para publicação via **GitHub Pages**.

---

## 🌍 Deploy

O projeto é publicado automaticamente pelo **GitHub Pages** a partir da pasta `docs/` na branch `main`.

Acesse em: [https://pmbfsa.github.io/simplefolio/](https://pmbfsa.github.io/simplefolio/)

---

## 📁 Estrutura do Projeto

```
simplefolio/
├── src/
│   ├── assets/
│   │   ├── favicon.png             # Ícone do site
│   │   ├── omnifood.png            # Imagem de projeto
│   │   ├── profile.jpeg            # Foto de perfil
│   │   └── resume.pdf              # Currículo
│   ├── data/
│   │   └── scrollRevealConfig.js   # Configurações de animação ScrollReveal
│   ├── sass/                       # Arquivos de configuração do ambiente Sass
│   ├── scripts/
│   │   ├── scrollReveal.js         # Script de animação de scroll
│   │   └── tiltAnimation.js        # Script de animação de inclinação
│   ├── index.html                  # Página principal
│   ├── index.js                    # Entry point JavaScript
│   └── styles.scss                 # Estilos globais (Sass)
├── docs/                           # Build de produção (GitHub Pages)
├── examples/
│   └── example.png                 # Screenshot do portfólio
├── package.json
├── LICENSE
└── README.md
```

---

## 📬 Contato

Desenvolvido por **Paulo Márcio**

[![GitHub](https://img.shields.io/badge/GitHub-pmbfsa-181717?style=for-the-badge&logo=github)](https://github.com/pmbfsa)

---

## 📜 Licença

Este projeto está licenciado sob a **GNU General Public License v3.0**.
Consulte o arquivo [LICENSE](./LICENSE) para mais detalhes.
