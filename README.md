# Jogo-dos-Numeros-JavaScript

Joguinho de adivinhação em JS criado como prática no curso da Alura.  

## Visão Geral  
Usuário tenta acertar número de 1 a 10. Feedback visual e por voz guiam o jogo.

## Estrutura de Arquivos  
- index.html: layout (título, mensagem, input, botões “Chutar”/“Novo jogo”), importa app.js e style.css.  
- style.css: gradient de fundo, container flexível, botões arredondados, responsivo com media queries.  
- app.js: gera número aleatório sem repetição, recebe chute, dá dica “maior”/“menor”, conta tentativas, usa ResponsiveVoice para falar, reinicia jogo.

## Funcionalidades  
- Sorteio sem repetir até esgotar  
- Dicas de voz e texto em PT-BR  
- Contador de tentativas com plural correto  
- “Novo jogo” reinicia estado

## Tecnologias  
JavaScript (ES6), ResponsiveVoice.js, HTML5, CSS3 (Flexbox, Media Queries)

## Como Executar  
1. git clone
2. Abra index.html no navegador  
3. Jogue até acertar  

## License  
MIT 
