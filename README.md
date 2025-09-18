# Discord Clone - Projeto Responsivo

## Descrição do Projeto
Este é um **clone responsivo da página inicial do Discord**, construído utilizando **HTML e CSS puro**. O objetivo do projeto é recriar a experiência visual e a estrutura da página principal do Discord, com foco em responsividade para diferentes tamanhos de tela, incluindo mobile, tablet e desktop.

O site possui seções destacadas que mostram funcionalidades do Discord, um **hero** chamativo, botões de ação, e um **footer** estilizado.

---

## Funcionalidades
- Layout **responsivo** utilizando `flexbox` e media queries.
- Hero principal com **imagem de fundo** e CTA (Call To Action) com botões.
- Seções alternadas com imagens e textos, usando `nth-child(even)` para inverter a ordem em telas maiores.
- Botões estilizados com efeito hover.
- Footer com logo e informações.
- Uso de **fontes do Google Fonts** para estética próxima do design original.

---

## Tecnologias Utilizadas
- **HTML5** – Estrutura semântica do site.
- **CSS3** – Estilização, layout com Flexbox e responsividade.
- **Google Fonts** – Tipografias: Luckiest Guy, Raleway, Roboto, Open Sans.
- Imagens utilizadas como placeholders para simular a interface do Discord.

---

## Estrutura de Pastas
discord-clone/
│
├── discord.html # Página principal
├── discord.css # Arquivo de estilos
├── img/ # Imagens utilizadas no projeto
│ ├── Header Background.png
│ ├── Header.png
│ ├── Section Image1.png
│ ├── Section Image2.png
│ ├── Section Image3.png
│ ├── Section Image4.png
│ └── Discord-footer.png
└── README.md # Este arquivo

---

## Como Rodar o Projeto
1. Clone o repositório:
```bash
git clone git@github.com:Islania-Silva/Pagina-Discord-Responsiva.git
Navegue até a pasta do projeto:

bash
Copiar código
cd discord-clone
Abra o arquivo discord.html no seu navegador preferido.

Não é necessário servidor, pois o projeto é apenas front-end.

Responsividade
Mobile (default): layout em coluna, imagens acima do texto.

Tablet (≥768px): layout em linha (flex-direction: row), seções pares invertidas (row-reverse).

Desktop (≥1024px): hero maior, fontes maiores, mais espaçamento entre seções e botões, hover nos botões com animação.

Créditos
Clone inspirado na página oficial do Discord.

Fontes do Google Fonts.

Imagens usadas como placeholders.