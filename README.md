<div align="center">

<img src="assets/images/perfil-portfolio.jpeg" alt="Francilândio Lima" width="128" />

# Portfólio Dev — Francilândio Lima

**Desenvolvedor Backend** · Transformando necessidades em aplicações reais, envolventes e funcionais.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![Phosphor Icons](https://img.shields.io/badge/Phosphor%20Icons-3C3C3C?style=for-the-badge&logo=phosphoricons&logoColor=white)](https://phosphoricons.com/)
[![Zero dependencies](https://img.shields.io/badge/dependencies-0-82BC4F?style=for-the-badge)](#stack-tecnológica)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/francilandio-lima-dev/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Francilandio07)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/francilandiolima_fls/)
[![E-mail](https://img.shields.io/badge/E--mail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:francilandiolimaserafim832@gmail.com)

</div>

---

## Sumário

- [Sobre o projeto](#sobre-o-projeto)
- [Demonstração](#demonstração)
- [Seções da página](#seções-da-página)
- [Projetos em destaque](#projetos-em-destaque)
- [Stack tecnológica](#stack-tecnológica)
- [Estrutura do projeto](#estrutura-do-projeto)
- [Design system](#design-system)
- [Como executar](#como-executar)
- [Deploy (GitHub Pages)](#deploy-github-pages)
- [Roadmap](#roadmap)
- [Autor](#autor)
- [Licença](#licença)

---

## Sobre o projeto

Portfólio pessoal desenvolvido **do zero** em **HTML5 e CSS3 puro**, sem frameworks, bibliotecas de UI ou etapa de build. O objetivo é apresentar minha trajetória como desenvolvedor, reunir os projetos que já construí e centralizar os canais de contato em uma única página.

O foco da implementação está em **CSS moderno**: um sistema de design baseado em *custom properties*, **CSS Nesting** nativo, **CSS Grid Layout** como base do layout e ícones SVG coloridos dinamicamente com `mask-image`. O resultado é uma página leve, sem dependências de JavaScript e de manutenção simples.

**Principais características:**

- Página única (*single page*) com navegação por âncoras.
- Layout construído inteiramente com **CSS Grid** — sem frameworks como Bootstrap ou Tailwind.
- **Design tokens** centralizados em `:root` (cores, famílias tipográficas e escalas de texto).
- Ícones de tecnologia renderizados via **SVG + CSS mask**, permitindo trocar a cor de cada ícone apenas com uma variável CSS.
- Ícones de interface com **Phosphor Icons** (CDN) e tipografia com **Google Fonts**.
- CSS organizado por responsabilidade e importado em cascata por `styles/index.css`.
- **Zero dependências** e **zero build**: basta abrir o `index.html`.

---

## Demonstração

> A versão publicada via GitHub Pages ainda não está disponível. Enquanto isso, execute o projeto localmente seguindo a seção [Como executar](#como-executar) ou publique-o com as instruções de [Deploy](#deploy-github-pages).

---

## Seções da página

| Seção | Conteúdo |
| --- | --- |
| **Apresentação** (`header`) | Foto de perfil com borda de destaque, nome, cargo (*Desenvolvedor Backend*), resumo profissional e *tags* da stack: GitHub, HTML, CSS, JavaScript e Node.js. |
| **Projetos** (`#projects`) | Grade com **15 projetos em destaque**. Cada card exibe thumbnail, título e descrição, e leva à versão publicada do projeto. |
| **Serviços** (`#services`) | Dois cards com as áreas de atuação: *Websites e aplicativos* (desenvolvimento de interfaces) e *API e banco de dados* (criação de serviços do sistema). |
| **Contato** (`footer`) | Atalhos para LinkedIn, Instagram, GitHub e e-mail, com efeitos de *hover* e ícones de ação. |

Os estados de interação (`:hover`) aplicam borda e mudança de cor nos cards, nas *tags* e nos links de contato; a seta do *hero* (`CaretDoubleDown`) funciona como *scroll hint* para a seção de projetos.

---

## Projetos em destaque

| # | Projeto | Descrição | Link |
| --- | --- | --- | --- |
| 01 | **Travelgram** | Rede social onde as pessoas mostram os registros de suas viagens pelo mundo. | [Demo](https://francilandio07.github.io/Travelgram/) |
| 02 | **Tech News** | Homepage de um portal de notícias sobre a área de tecnologia. | [Demo](https://francilandio07.github.io/Portal-de-noticias/) |
| 03 | **Página de receita** | Página com o passo a passo de uma receita para cupcakes. | [Demo](https://francilandio07.github.io/Pagina-de-receita/) |
| 04 | **Zingen** | Landing page completa e responsiva de um aplicativo de karaokê. | — |
| 05 | **Refund** | Sistema para pedido e acompanhamento de reembolso. | — |
| 06 | **Página de turismo** | Informações para quem quer viajar para Busan. | [Demo](https://francilandio07.github.io/Local-Turistico/) |
| 07 | **Tiny Knight** | Jogo de um cavaleiro que enfrenta inimigos, no estilo sobrevivência. | [Jogar](https://francilandiolima.itch.io/tiny-knight-francilandio) |
| 08 | **TecBlog** | Webpage de um blog fictício. | [Demo](https://francilandio07.github.io/Projetos-Full-Stack/ProjetoCSS3Intermediario/) |
| 09 | **Notícias da cidade** | Página com notícias de uma cidade. | [Demo](https://francilandio07.github.io/Projetos-Full-Stack/ProjetoCSS3IntermediarioeAvancado/) |
| 10 | **Unes** | Site de uma universidade com as páginas "Home", "Quem somos" e "Contato". | [Demo](https://francilandio07.github.io/Projetos-Full-Stack/ProjetoFinalHTML/index.html) |
| 11 | **Time's Up** | Jogo de sobrevivência estilo pulo em plataformas móveis. | [Jogar](https://francilandio07.github.io/Jogo_TimesUp/) |
| 12 | **Rotten Tomatoes copy** | Cópia do site de avaliação de filmes Rotten Tomatoes. | [Demo](https://francilandio07.github.io/) |
| 13 | **Enduro copy** | Cópia do jogo de corrida "Enduro". | [Jogar](https://francilandio07.github.io/Lab_TecnologiasWeb/Trabalho2/index.html) |
| 14 | **Astas** | Site para serviços em celulares. | [Demo](https://francilandio07.github.io/Lab_TecnologiasWeb/CSS1/home.html) |
| 15 | **Anna Bella** | Site que exibe informações sobre uma modelo. | [Demo](https://francilandio07.github.io/Projetos-Full-Stack/ProjetoCSS3/campanhas-publicitarias.html) |

---

## Stack tecnológica

| Camada | Tecnologias |
| --- | --- |
| **Marcação** | HTML5 semântico (`header`, `main`, `section`, `footer`), acessibilidade básica com `alt` e `lang="pt-br"`. |
| **Estilização** | CSS3 com **CSS Grid Layout**, **CSS Nesting** nativo, **Custom Properties** (variáveis), `mask-image`, pseudo-classes (`:hover`) e bordas/raio via variáveis. |
| **Tipografia** | Google Fonts: **Asap** (títulos), **Inconsolata** (subtítulos) e **Maven Pro** (textos). |
| **Ícones** | **Phosphor Icons** (via CDN) para a interface e SVGs próprios em `assets/icons` para a stack. |
| **JavaScript** | Não utilizado no escopo atual — a página é totalmente estática. |
| **Ferramentas** | Visual Studio Code (+ Live Server, opcional) e Git/GitHub. **Sem** gerenciador de pacotes, bundler ou etapa de compilação. |

---

## Estrutura do projeto

```text
Portfolio-dev/
├── assets/
│   ├── icons/                     # SVGs (GitHub, HTML, CSS, JS, Node, seta)
│   └── images/                    # Foto de perfil, backgrounds e thumbnails (15)
├── styles/
│   ├── index.css                  # Ponto de entrada: importa os demais arquivos
│   ├── global.css                 # Reset + design tokens (:root)
│   ├── header.css                 # Apresentação / hero
│   ├── main.css                   # Projetos e serviços
│   └── footer.css                 # Contato
├── index.html                     # Documento único da aplicação
└── README.md
```

**Convenções adotadas:**

- Um arquivo CSS por seção da página, importado em cascata por `styles/index.css`.
- Classes ligadas ao contexto (`.tag`, `.project`, `.card`, `.social-media`) e utilitários de tipografia (`.title-lg`, `.title-md`, `.title-sm`, `.text-md`, `.text-sm`, `.subtitle`).
- Imagens e ícones nomeados por finalidade (`Thumbnail_Project-XX.png`, `Background_Intro.png`, `perfil-portfolio.jpeg`).

---

## Design system

Todas as cores, fontes e escalas tipográficas estão declaradas como *custom properties* em `styles/global.css`, o que permite alterar a identidade visual do site em um único lugar.

### Paleta de cores

| Token | Hex | Aplicação |
| --- | --- | --- |
| `--red` | `#E3646E` | Destaque: nome no hero, subtítulos das seções, borda do avatar, ícone HTML |
| `--purple` | `#BB72E9` | Subtítulo de contato e ícone de serviços (*devices*) |
| `--blue` | `#3996DB` | Ícone CSS e *hover* dos links de contato |
| `--green` | `#82BC4F` | Ícone Node.js |
| `--yellow` | `#EABD5F` | Ícone JavaScript e *hard drives* |
| `--gray-100` | `#E2E4E9` | Títulos |
| `--gray-200` | `#C0C4CE` | Textos de apoio |
| `--gray-300` | `#878EA1` | Texto do hero e bordas de *hover* |
| `--gray-400` | `#292C34` | Fundo de cards, *tags* e links de contato |
| `--gray-500` | `#16181D` | Fundo da seção de projetos |
| `--gray-600` | `#0D0E11` | Fundo da seção de serviços |

### Tipografia

| Token | Fonte | Uso |
| --- | --- | --- |
| `--title-lg` | Asap 700 · 56px | Título principal do hero |
| `--title-md` | Asap 700 · 24px | Títulos de seção |
| `--title-sm` | Asap 700 · 16px | Títulos de cards |
| `--subtitle` | Inconsolata 400 · 20px | Sobretítulos (*Hello World!*, *Meu trabalho*, *Contato*) |
| `--text-md` | Maven Pro 400 · 16px | Textos médios |
| `--text-sm` | Maven Pro 400 · 14px | Descrições e textos curtos |

---

## Como executar

**Pré-requisitos:** apenas um navegador moderno (Chrome, Edge, Firefox ou Safari atualizados — o projeto utiliza *CSS Nesting* nativo).

```bash
# 1. Clone o repositório
git clone https://github.com/Francilandio07/Portfolio-dev.git

# 2. Acesse a pasta
cd Portfolio-dev
```

**Opção A — abrir diretamente:** dê um duplo clique em `index.html` ou arraste o arquivo para o navegador. Como todos os caminhos de assets são relativos, a página funciona via `file://`.

**Opção B — servidor local (recomendado):**

```bash
# Python 3
python -m http.server 5500

# ou com Node.js, sem instalar nada no projeto
npx serve .
```

Depois acesse `http://localhost:5500`.

**Opção C — VS Code:** instale a extensão **Live Server**, clique com o botão direito em `index.html` e escolha *Open with Live Server* (recarregamento automático ao salvar).

> Não há `npm install`, etapa de *build* ou variáveis de ambiente: o projeto não possui dependências de desenvolvimento.

---

## Deploy (GitHub Pages)

Por ser um site 100% estático, a publicação é feita sem qualquer processo de compilação:

1. Envie o projeto para o repositório `Portfolio-dev` no GitHub.
2. No repositório, acesse **Settings → Pages**.
3. Em **Source**, selecione **Deploy from a branch**.
4. Escolha a branch `master` (ou `main`) e a pasta `/ (root)`.
5. Clique em **Save** e aguarde a publicação.

A URL final seguirá o padrão:

```text
https://<usuario>.github.io/Portfolio-dev/
```

> Após o primeiro deploy, adicione o link na seção [Demonstração](#demonstração) deste README.

---

## Roadmap

- [x] Estrutura base em HTML5 semântico
- [x] Design system com *custom properties* e tipografia modular
- [x] Seção de apresentação com *tags* da stack
- [x] Seção de projetos com 15 cards e thumbnails
- [x] Seção de serviços
- [x] Rodapé de contato com ícones e estados de *hover*
- [ ] Publicação via GitHub Pages
- [ ] Links dos projetos **Zingen** e **Refund** (atualmente em `#`)
- [ ] Layout responsivo — hoje o grid de projetos (1040px) e os links de contato (400px) usam larguras fixas, sem `media queries`
- [ ] Revisão de acessibilidade: foco visível, `aria-label` nos links de ícone e contraste dos textos secundários
- [ ] Separação dos dados dos projetos em JSON, com renderização dinâmica
- [ ] Tema claro / escuro
- [ ] Limpeza do `<head>`: há três blocos de Google Fonts repetidos, `preconnect` duplicado e famílias que não são usadas (Alice, Archivo, Open Sans, Poppins)

---

## Autor

**Francilândio Lima** — Desenvolvedor Backend

[![LinkedIn](https://img.shields.io/badge/LinkedIn-francilandio--lima--dev-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/francilandio-lima-dev/)
[![GitHub](https://img.shields.io/badge/GitHub-Francilandio07-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Francilandio07)
[![Instagram](https://img.shields.io/badge/Instagram-francilandiolima__fls-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/francilandiolima_fls/)
[![E-mail](https://img.shields.io/badge/E--mail-francilandiolimaserafim832%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:francilandiolimaserafim832@gmail.com)

---

## Licença

Este repositório ainda não possui um arquivo de licença. O conteúdo é disponibilizado para fins de estudo e portfólio; para reutilização em outros contextos, entre em contato pelo e-mail acima.

Se desejar abrir o código para uso livre, uma boa opção é adicionar uma licença [MIT](https://choosealicense.com/licenses/mit/) criando o arquivo `LICENSE` na raiz do projeto.

