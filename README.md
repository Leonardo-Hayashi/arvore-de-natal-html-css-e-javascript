# Árvore de Natal 3D 🎄

Este é um projeto de visualização interativa em 3D que representa uma Árvore de Natal estilizada e decorada com elementos geométricos, iluminação dinâmica e efeitos visuais avançados. Criado com a biblioteca [Three.js](https://threejs.org/), o projeto oferece uma experiência imersiva, combinando animação, shaders e pós-processamento.

---

## 🎨 Características do Projeto

### 🌟 Funcionalidades principais:
- **Árvore de Natal estilizada**: Feita com geometria cônica e decorada com formas como esferas e icosaedros.
- **Texto animado**: Uma mensagem de "Feliz Natal" percorre uma curva 3D ao redor da árvore.
- **Iluminação avançada**: Inclui luzes coloridas, reflexões e efeitos de **Unreal Bloom** para realçar os elementos da cena.
- **Elementos dinâmicos**: Decorações piscantes, animações suaves de câmera e rotação automática da cena.
- **Shaders personalizados**: Uso de Vertex e Fragment Shaders para criar efeitos visuais únicos.
- **Responsividade**: A cena se ajusta automaticamente ao tamanho da janela do navegador.

---

## 🛠️ Tecnologias Utilizadas

O projeto faz uso de tecnologias modernas para renderização 3D:

- **[Three.js](https://threejs.org/)**: Biblioteca JavaScript para criação e renderização de gráficos 3D.
- **Shaders customizados**: Para controlar a aparência visual dos objetos na cena.
- **Efeitos de pós-processamento**:
  - **Unreal Bloom**: Realça áreas brilhantes para um efeito de brilho mágico.
  - **RenderPass e ShaderPass**: Para controle e manipulação da cena renderizada.
- **Controle de câmera**:
  - [OrbitControls](https://threejs.org/docs/#examples/en/controls/OrbitControls): Permite rotacionar, aproximar e explorar a cena.

---

## 📂 Estrutura do Projeto

<a href="https://programartudo.blogspot.com/2024/11/html-tudo-o-que-precisa-para-comecar.html" target="_blank"><img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" height="40"/></a> <a href="https://programartudo.blogspot.com/2024/11/css-como-dar-estilo-ao-teu-website.html" target="_blank"><img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" height="40"/></a> <a href="https://programartudo.blogspot.com/2024/11/javascript-linguagem-dinamica-da-web.html" target="_blank"><img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" height="40"/></a>

O projeto é organizado em três arquivos principais:

### `index.html`
Este arquivo contém:
- A estrutura básica da página.
- Links para os scripts necessários, incluindo a biblioteca Three.js e seus módulos adicionais.
- Definição dos shaders personalizados (Vertex e Fragment Shaders).

### `style.css`
Define o estilo da página:
- Define o **canvas** como elemento principal, ocupando 100% da tela.
- Remove seleções e margens para uma experiência de tela cheia.

### `script.js`
É onde a mágica acontece:
- Configura a cena, câmera e renderizador.
- Cria os elementos 3D como a árvore, as decorações e o texto animado.
- Aplica os efeitos de luz e shaders personalizados.
- Configura animações e ajustes responsivos para a janela.

---

## 🎥 Pré-visualização
no VS Code para hospedar localmente.

## 🔍 Componentes do Projeto

**🌳 A Árvore**

- Estrutura cônica principal feita com **CylinderGeometry**.

- Decorada com esferas e icosaedros, distribuídos aleatoriamente em sua superfície.

## ✨ Decorações

**Esferas brilhantes:**

- Criadas com geometria de esfera.

- Materiais com cores aleatórias para cada instância.

- **Ico-esferas:** Criadas com geometria de icosaedro.

- Rotação aleatória para um efeito dinâmico.

- **Elementos iluminados:** Pequenas decorações que brilham periodicamente com efeitos de floramento.

## 💡 Iluminação

- Luzes pontuais com variação de cor e intensidade.

- Uso de material reflexivo para criar um ambiente mais realista.

## 📝 Texto Animado

- Mensagem "Feliz Natal" criada com **TextGeometry**.

- Animação baseada em uma curva 3D com **CatmullRomCurve3**.

## 🖥️ Requisitos

**Para executar o projeto, você precisará de:**

- Um navegador moderno com suporte a **WebGL** (como Chrome, Firefox ou Edge).

- Conexão com a internet para carregar as dependências da CDN.

## 📄 Licença

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/Ninja1375/arvore-de-natal-3d/blob/main/LICENSE)

- Este projeto está licenciado sob a Licença MIT, permitindo uso, modificação e distribuição.

## 🙌 Créditos

- Projeto desenvolvido utilizando a poderosa biblioteca [Three.js](https://threejs.org/).

- Inspirado por exemplos criativos e inovadores de visualizações 3D.

