<div align="center">

# 👨‍🚒 Herói das Chamas 🚒

*Um mini-jogo de aventura e exploração interativa desenvolvido inteiramente em HTML puro.*

[![HTML5](https://img.shields.io/badge/HTML5-Pure-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-PT/docs/Web/HTML)
[![Status do Jogo](https://img.shields.io/badge/Status-Concluído-28a745?style=for-the-badge)]()
[![Idioma](https://img.shields.io/badge/Idioma-Português-blue?style=for-the-badge)]()

</div>

---

## 🎯 Sobre o Jogo

Você é um **bravo bombeiro** e cada segundo conta! 🔥 Uma casa está a arder e uma pessoa ficou presa lá dentro. A sua missão é explorar os diferentes cômodos da casa, navegando estrategicamente por portas e janelas, até encontrar a vítima e salvar o dia.

O projeto foi construído seguindo rigorosamente a navegação clássica por hiperligações (`<a>`) entre páginas HTML, proporcionando uma experiência imersiva de *text adventure* sem recorrer a JavaScript ou CSS externo.

---

## 🗺️ Mapa da Casa e Fluxo de Jogo

O jogo é composto por 7 espaços interligados:

1. **📍 Rua (`index.html`)** — Ponto de partida em frente à casa em chamas. Escolha entre entrar pela porta ou pela janela.
2. **🏠 Sala (`sala.html`)** — Conecta-se à rua, ao quarto e ao corredor principal.
3. **🛏️ Quarto (`quartoDireito.html`)** — Permite fugir pela janela ou aceder ao banheiro.
4. **🚿 Banheiro (`banheiro.html`)** — Ambiente fechado que liga de volta ao quarto ou à cozinha.
5. **🚪 Corredor (`corredor.html`)** — Área central que distribui o acesso para a sala, cozinha e quarto principal.
6. **🍳 Cozinha (`cozinha.html`)** — Zona de perigo com chamas ativas junto ao fogão.
7. **🎯 Quarto Principal (`quartoEsquerdo.html`)** — **Cômodo de destino!** Encontre a pessoa a tempo e conclua a missão com sucesso.

---

## 📁 Estrutura de Ficheiros

Certifique-se de que o seu repositório está organizado desta forma para que as imagens e os links funcionem corretamente:

```text
/
├── index.html
├── sala.html
├── quartoDireito.html
├── banheiro.html
├── corredor.html
├── cozinha.html
├── quartoEsquerdo.html
└── imagem/
    ├── rua.jpg
    ├── sala.jpg
    ├── quarto.jpg
    ├── banheiro.jpg
    ├── corredor.jpg
    ├── cozinha.jpg
    └── vitoria.jpg