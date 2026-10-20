<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:161b22,100:7c9fd4&height=220&section=header&text=Paulo%20Muniz&fontSize=52&fontColor=e8eaf0&fontAlignY=35&desc=UI/UX%20•%20Full%20Stack%20•%20IA&descSize=18&descAlignY=55&animation=fadeIn" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=7C9FD4&center=true&vCenter=true&multiline=true&repeat=true&width=640&height=70&lines=Interfaces+bonitas+que+resolvem+problema+de+verdade+%F0%9F%8E%A8;Do+Figma+ao+deploy%2C+com+IA+no+meio+do+caminho+%F0%9F%A4%96)](https://git.io/typing-svg)

**Dev Full Stack e suporte de TI. Faço apps web que o pessoal usa de verdade no dia a dia:**
**minigames pro escritório, PDV de cafeteria, ferramentas de suporte e gestão de clínica.**

![Ciência da Computação](https://img.shields.io/badge/Ci%C3%AAncia%20da%20Computa%C3%A7%C3%A3o-7%C2%BA%2F8%C2%BA%20semestre-7c9fd4?style=for-the-badge&labelColor=0d1117)
![Trabalho](https://img.shields.io/badge/hoje-Suporte%20TI%20%2B%20Dev-79c4a4?style=for-the-badge&labelColor=0d1117)
![Foco](https://img.shields.io/badge/foco-UI%2FUX%20premium-8b5cf6?style=for-the-badge&labelColor=0d1117)
<br>
<img src="https://komarev.com/ghpvc/?username=PainN04&label=visitas&color=7c9fd4&style=for-the-badge" alt="Visitas" />
<img src="https://img.shields.io/github/followers/PainN04?label=seguidores&style=for-the-badge&color=7c9fd4&labelColor=0d1117" alt="Seguidores" />

</div>

<br>

## 📑 Sumário

- [✨ Em poucas linhas](#-em-poucas-linhas)
- [🚀 Projetos em destaque](#-projetos-em-destaque)
- [🔭 No forno agora](#-no-forno-agora)
- [🧭 Como eu construo](#-como-eu-construo)
- [🛠️ Tech stack](#️-tech-stack)
- [📊 Números do GitHub](#-números-do-github)
- [📬 Bora conversar](#-bora-conversar)

<br>

## ✨ Em poucas linhas

| | |
| --- | --- |
| 🎨 **UI/UX em primeiro lugar** | Design systems, glassmorphism, cards 3D e microinterações. Se é pra usar todo dia, tem que ser gostoso de usar. |
| 🧱 **Full stack de ponta a ponta** | Do front em JS puro ou React até API em Node, banco (Postgres, SQLite, Firebase) e deploy na Vercel. |
| 🤖 **IA no fluxo de trabalho** | Gemini, Claude e Ollama tanto pra construir mais rápido quanto dentro dos próprios apps. |
| 🛎️ **Visão de suporte** | Trabalho no suporte de TI, então sei onde o usuário trava. Isso vira decisão de produto. |
| 📚 **Sempre aprendendo** | TypeScript, GraphQL e SQL avançado no momento. |

<br>

## 🚀 Projetos em destaque

### 🎮 [MicroGames](https://github.com/PainN04/MicroGames) &nbsp;·&nbsp; [jogar online ↗](https://microgames-ten.vercel.app)

> **27 minigames de navegador pra jogar com o pessoal do trabalho.** Ranking compartilhado, desafio do dia, torneio semanal, duelos, duplas e 43 conquistas.

<div align="center">
<img src="https://raw.githubusercontent.com/PainN04/MicroGames/main/docs/img/menu.png" alt="Menu do MicroGames" width="860">
</div>

<br>

![Jogos](https://img.shields.io/badge/jogos-27-8b5cf6?style=flat-square)
![Conquistas](https://img.shields.io/badge/conquistas-43-f59e0b?style=flat-square)
![Testes](https://img.shields.io/badge/testes-33%20passando-22c55e?style=flat-square)
![Sem build](https://img.shields.io/badge/front-JS%20puro%2C%20sem%20build-f7df1e?style=flat-square)
![Phaser](https://img.shields.io/badge/Phaser-3.90-8a2be2?style=flat-square)
![Neon](https://img.shields.io/badge/Neon-Postgres-00e599?style=flat-square&logo=postgresql&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-deploy-000000?style=flat-square&logo=vercel&logoColor=white)

| O que tem | Como fiz |
| --- | --- |
| 🕹️ **27 jogos**: reflexo, cabeça e arcade (Termo, Sudoku, 2048, Cobrinha, Come-Come, Ritmo…) | Um arquivo JS por jogo. Phaser só baixa quando alguém abre um jogo que precisa dele. |
| 🏅 **Ranking anti-trapaça** | O servidor confere faixas válidas e tem trava anti-autoclicker antes de gravar. |
| 📅 **Desafio do dia + torneio semanal** | Sorteio determinístico compartilhado entre cliente e servidor, então os dois sempre concordam. |
| 🚦 **Integração com o Geiko** | Quem está com a fila de tickets cheia fica sem jogar até resolver alguns. Regra editável no painel admin. |
| 🧪 **Mesmo código no PC e na produção** | Um único `router.js`; só o banco muda (SQLite local, Neon na Vercel). |

<div align="center">
<img src="https://raw.githubusercontent.com/PainN04/MicroGames/main/docs/img/2048.png" alt="2048 com ranking" width="420">
&nbsp;
<img src="https://raw.githubusercontent.com/PainN04/MicroGames/main/docs/img/termo.png" alt="Termo" width="420">
</div>

<br>

### ☕ [PDV Grão e Fubá](https://github.com/PainN04/Gr-o-Fub-)

> **Ponto de venda web pra uma cafeteria de verdade**, feito pra rodar no tablet do balcão, até sem internet.

![React](https://img.shields.io/badge/React-18-61dafb?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646cff?style=flat-square&logo=vite&logoColor=white)
![Zustand](https://img.shields.io/badge/estado-Zustand-6b3f2a?style=flat-square)
![PWA](https://img.shields.io/badge/PWA-offline--first-d98a3d?style=flat-square&logo=pwa&logoColor=white)

| | |
| --- | --- |
| 🧾 **Venda rápida** | Catálogo por categoria, tamanhos e adicionais, comanda com quantidade e desconto (R$ ou %). |
| 💳 **4 formas de pagamento** | PIX, cartão, dinheiro com troco automático e divisão da conta entre várias pessoas. |
| 🖨️ **Cupom térmico 80mm** | Impressão direto do navegador, com senha do pedido em destaque. |
| 💾 **Comandas salvas** | Fica tudo no aparelho e dá pra retomar depois. |
| 🎨 **Design system próprio** | Paleta café/caramelo, Playfair Display + Montserrat, layout que se adapta a desktop, tablet e celular. |

<br>

## 🔭 No forno agora

<table>
<tr>
<td width="50%" valign="top">

### 🛎️ Geiko Workspaces
Ferramenta de suporte N1 com **React + Firebase** e interface em glassmorphism. É dela que vem a integração de fila de tickets usada no MicroGames.

</td>
<td width="50%" valign="top">

### 🧘 Agenda Fisio
Sistema de gestão pra **estúdios de fisioterapia e pilates**: agenda, pacientes e o dia a dia do estúdio num lugar só.

</td>
</tr>
</table>

<br>

## 🧭 Como eu construo

```mermaid
flowchart LR
    A[💡 Problema real<br/>do dia a dia] --> B[🎨 UI/UX<br/>Figma e protótipo]
    B --> C[⚡ Front<br/>JS puro ou React]
    C --> D[🔧 API e banco<br/>Node · Postgres · Firebase]
    D --> E[🧪 Testes]
    E --> F[☁️ Deploy<br/>Vercel]
    F --> G[🗣️ Feedback<br/>de quem usa]
    G --> B
```

Começo sempre por quem vai usar. Ajudo no suporte, então muita ideia nasce de ver alguém travando numa tela. Depois desenho, construo, testo e ponho no ar rápido pra ouvir o pessoal e melhorar.

<br>

## 🛠️ Tech stack

<div align="center">

| Área | Ferramentas |
| :---: | :---: |
| 💻 **Linguagens** | <img src="https://skillicons.dev/icons?i=js,ts,py,c,cs&theme=dark" alt="Linguagens" /> |
| ⚡ **Frontend** | <img src="https://skillicons.dev/icons?i=react,vite,html,css,bootstrap,flutter&theme=dark" alt="Frontend" /> |
| 🎨 **Design** | <img src="https://skillicons.dev/icons?i=figma,photoshop&theme=dark" alt="Design" /> |
| 🔧 **Backend e banco** | <img src="https://skillicons.dev/icons?i=nodejs,firebase,postgres,mysql,sqlite&theme=dark" alt="Backend" /> |
| ☁️ **Deploy e ferramentas** | <img src="https://skillicons.dev/icons?i=vercel,git,github,linux,vscode,arduino&theme=dark" alt="Ferramentas" /> |
| 🤖 **IA e LLMs** | <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=google-gemini&logoColor=white" alt="Gemini" /> <img src="https://img.shields.io/badge/Claude-191919?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude" /> <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" /> |

</div>

<details>
<summary><b>📚 Estudando agora</b></summary>
<br>

| Tema | Por quê |
| --- | --- |
| **TypeScript** | Tipagem forte no front pra projetos que crescem (como o MicroGames). |
| **GraphQL** | Buscar só o que a tela precisa. |
| **SQL avançado** | Dominar a camada de dados: índices, window functions e consultas de relatório. |
| **IA em produção** | Integrar LLMs nos apps com custo e latência sob controle. |

</details>

<br>

## 📊 Números do GitHub

<div align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=PainN04&show_icons=true&include_all_commits=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=7c9fd4&icon_color=79c4a4&text_color=c9d1d9&ring_color=7c9fd4" alt="GitHub Stats" />
  <img height="170" src="https://streak-stats.demolab.com?user=PainN04&theme=github-dark-blue&hide_border=true&background=0d1117&ring=7c9fd4&fire=79c4a4&currStreakLabel=7c9fd4&sideLabels=c9d1d9&dates=6e7681" alt="Sequência" />
</div>

<div align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=PainN04&bg_color=0d1117&color=7c9fd4&line=79c4a4&point=e8eaf0&area=true&area_color=7c9fd4&hide_border=true&custom_title=Contribui%C3%A7%C3%B5es" alt="Gráfico de contribuições" />
</div>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/PainN04/PainN04/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/PainN04/PainN04/output/github-snake.svg" />
    <img alt="Cobrinha comendo as contribuições" src="https://raw.githubusercontent.com/PainN04/PainN04/output/github-snake-dark.svg" />
  </picture>
</div>

<br>

## 📬 Bora conversar

<div align="center">

Topo projeto open source, SaaS com UX caprichado e integração criativa com IA.
Pode me chamar pra falar de **React, Node, Firebase, design systems ou APIs de IA**.

<br>

<a href="mailto:Paulogustavom04@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
<a href="https://linkedin.com/in/paulogustavo-sousa"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://instagram.com/paulog_04"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
<a href="https://discord.gg/painn04"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>

<br><br>

Feito com café, Figma e alguns minigames no intervalo. ☕🎮

</div>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7c9fd4,50:161b22,100:0d1117&height=120&section=footer" />
