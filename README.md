# 🖥️ Como a Internet Funciona? (DNS Unveiled)

Apresentação interativa desenvolvida para a matéria de **Introdução a ECI (Engenharia de Computação e Informação / Escola de Ciência da Informação)** na **UFRJ / UFMG**, abordando de forma didática, descomplicada e divertida os conceitos por trás da infraestrutura da internet mundial (cabos submarinos, endereços IP, DNS e o caso de apagão da Meta em 2021).

Este repositório contém os slides interativos em formato de arquivo único portável, configurados para hospedagem direta na web.

---

## 🔗 Links de Acesso
* **Slides Online (GitHub Pages):** [b.gpnobre.com/ieci/](https://b.gpnobre.com/ieci/)
* **Repositório do Projeto:** [github.com/cauzinnn/ieci](https://github.com/cauzinnn/ieci)

---

## 🛠️ Como a Apresentação foi Feita

Estes slides não utilizam softwares de apresentação tradicionais (como PowerPoint, Canva ou Google Slides). Em vez disso, foram **desenvolvidos do zero como uma aplicação front-end de página única (Single Page Application)**, utilizando apenas tecnologias web puras.

### Principais Pilares do Desenvolvimento:
1. **Zero Dependências (Vanilla Stack):** Toda a apresentação roda nativamente no navegador usando apenas um arquivo HTML (`index.html` ou `apresentacao_dns.html`), contendo folha de estilos (CSS3) e controlador lógico (JavaScript) totalmente embutidos (*inline*). Não há necessidade de rodar `npm install`, instalar bibliotecas pesadas ou usar ferramentas de compilação (*build tools*).
2. **Palco Fixo 16:9 (Non-Negotiable Scale):** O layout é projetado sobre uma resolução de design fixa de `1920x1080` pixels. O código JavaScript calcula e redimensiona o palco automaticamente de acordo com as dimensões da janela do navegador. Isso garante que a apresentação mantenha a mesma diagramação widescreen (16:9), sem quebras de parágrafo ou sobreposição de caixas, seja visualizada em um projetor, smartphone, monitor Ultrawide ou tablet.
3. **Estilo Visual Personalizado (8-Bit Orbit):** Inspirado na nostalgia digital dos fliperamas dos anos 90, o tema traz um visual retrô cyberpunk com as fontes *Tektur* (display), *Chakra Petch* (corpo) e *Space Mono* (terminal/dados), além de efeitos visuais simulando scanlines de monitores de tubo CRT, grade vetorial, estrelas em paralaxe e bordas baseadas em caixas de console retrô.

---

## ✨ Funcionalidades Especiais do Slide Interativo

### 1. Navegação Universal
Os slides possuem suporte a múltiplos métodos de navegação:
* **Teclado:** Use as setas direcionais (`Seta Direita` / `Seta Esquerda`), `Barra de Espaço` ou teclas `Page Up` / `Page Down`.
* **Dispositivos Móveis:** Suporte a toque com gestos de arrastar o dedo (**Swipe** para a esquerda ou direita).
* **Mouse:** Suporte a rolagem de slide utilizando a roda do mouse (**Scroll**).

### 2. Editor de Texto em Tempo Real (Inline Editor)
Os slides vêm integrados com um motor de edição interativo. 
* **Como ativar:** Pressione a tecla **`E`** do teclado (ou dê um duplo clique no canto superior esquerdo da tela).
* **Como usar:** O modo de edição será ativado, permitindo que você clique sobre qualquer texto, lista ou tabela e altere seu conteúdo diretamente na tela.
* **Salvamento Automático:** Pressionando **`E`** novamente ou utilizando **`Ctrl + S`** (ou `Cmd + S` no Mac), as suas alterações de texto são gravadas de forma persistente no banco de dados local do seu navegador (`localStorage`). Ao reabrir a página, suas edições estarão salvas!

### 3. Engine de Impressão de Alta Definição (PDF Printer)
Desenvolvemos uma folha de estilo de impressão nativa (`@media print`) que otimiza os slides para exportação:
* Desativa todas as animações dinâmicas e opacidades de transição (`.reveal`), exibindo o conteúdo de cada slide de forma estática e legível.
* Ajusta a dimensão da página para exatamente `1920x1080` por página de impressão, removendo margens, cabeçalhos ou rodapés inseridos pelo navegador.
* **Como imprimir:** Basta abrir o arquivo no navegador, pressionar **`Ctrl + P`** (ou `Cmd + P`), escolher "Salvar como PDF" e marcar a caixa "Gráficos de segundo plano"!

---

## ⚡ A Skill `frontend-slides`

Este projeto foi acelerado e refinado utilizando a poderosa inteligência e os padrões de design da skill **`frontend-slides`**. Esta ferramenta é especializada no desenvolvimento de experiências front-end imersivas e interfaces estéticas ricas, focando em:
* **Combate ao "AI Slop":** Garantia de que todos os layouts fujam de designs genéricos gerados por inteligência artificial (como gradientes roxos sem contexto), entregando ao invés disso soluções visuais marcantes, expressivas e coerentes com a proposta do projeto.
* **Tipografia Rígida:** Utilização de fontes modernas selecionadas a dedo do Google Fonts/Fontshare para garantir legibilidade e forte hierarquia visual.
* **Estrutura de Animação Otimizada:** reveals estagiados baseados em curvas de animação física exponencial (`cubic-bezier`), que criam micro-interações fluidas e agradáveis na transição dos dados na tela.

---

## 👥 Integrantes da Dupla
* **Gabriel Cauzin Nobre Pinto**
* **Douglas Avelino da Silva Sousa**

---

*Estude, edite, divirta-se e bom jogo! 🕹️*
