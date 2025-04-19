# Jogo-dos-Numeros-JavaScript

Joguinho simples feito como uma prática de JavaScript do curso da Alura.

## 💡 Visão Geral

Jogo de adivinhação onde o usuário tenta acertar um número de 1 a 10. Dicas visuais e por voz guiam o jogador até o acerto.

## ⚙️ Estrutura de Arquivos

- **index.html**  
  Carrega o layout principal:  
  - Área de título e mensagem (`<h1>`, `<p>`)  
  - Campo de entrada numérica (`<input type="number">`)  
  - Botões “Chutar” e “Novo jogo”  
  - Importa `app.js` e `style.css` :contentReference[oaicite:0]{index=0}&#8203;:contentReference[oaicite:1]{index=1}

- **style.css**  
  Estilização completa:  
  - Fundo em gradiente e textura com imagem de código  
  - Container centralizado, flexível e responsivo  
  - Botões arredondados e input destacado  
  - Media queries para ajustar em telas menores :contentReference[oaicite:2]{index=2}&#8203;:contentReference[oaicite:3]{index=3}

- **app.js**  
  Lógica do jogo:  
  1. Gera número secreto aleatório (1–10), sem repetir até esgotar a lista  
  2. Recebe chute do usuário e compara com o número secreto  
  3. Exibe dica (“maior” ou “menor”) e conta tentativas  
  4. Usa ResponsiveVoice para falar mensagens em português brasileiro  
  5. Habilita reinício após acerto :contentReference[oaicite:4]{index=4}&#8203;:contentReference[oaicite:5]{index=5}

## ➕ Funcionalidades Principais

- Sorteio sem repetição até consumir todas as opções  
- Feedback de voz e texto em tempo real  
- Contagem de tentativas com pluralização correta  
- Botão de “Novo jogo” que zera estado e gera novo número

## 🚀 Tecnologias

- JavaScript (ES6)  
- [ResponsiveVoice.js](https://responsivevoice.org/) para síntese de voz  
- HTML5 semântico  
- CSS3 (Flexbox, Media Queries)

## ▶️ Como Executar

1. Clone este repositório  
2. Abra `index.html` em qualquer navegador moderno  
3. Chute números até acertar e divirta‑se  
