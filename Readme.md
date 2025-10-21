# Jogo de Adivinhação de Números

Um jogo interativo de adivinhação de números desenvolvido com HTML, CSS e JavaScript. O computador escolhe um número aleatório e o jogador deve adivinhar qual é, recebendo dicas se o palpite é maior ou menor que o número secreto.

## Funcionalidades

- Geração aleatória de números entre 1 e 100
- Sistema de dicas (maior/menor) após cada palpite
- Contador de tentativas
- Histórico de palpites com feedback visual
- Sistema de recordes (melhor pontuação)
- Opção de dica que divide o intervalo pela metade
- Design responsivo e moderno
- Armazenamento local do recorde

## Como Jogar

1. Abra o arquivo `index.html` em um navegador web
2. Digite um número entre 1 e 100 no campo de entrada
3. Clique em "Adivinhar" ou pressione Enter para enviar seu palpite
4. Use as dicas ("maior" ou "menor") para refinar seus próximos palpites
5. Tente adivinhar o número no menor número de tentativas possível
6. Use o botão "Dica" para obter uma ajuda sobre o intervalo do número
7. Clique em "Novo Jogo" para reiniciar com um novo número secreto

## Regras do Jogo

- O número secreto é sempre um inteiro entre 1 e 100
- Cada palpite conta como uma tentativa
- O objetivo é adivinhar o número com o menor número de tentativas
- O recorde é armazenado localmente no navegador

## Estrutura do Projeto

- `index.html` - Estrutura principal do jogo
- CSS incorporado - Estilos modernos com gradientes e design responsivo
- JavaScript incorporado - Lógica do jogo e interações

## Personalização

O código é facilmente personalizável. Você pode:

- Alterar o intervalo de números (modificando `minRange` e `maxRange`)
- Ajustar as cores e o tema visual modificando as variáveis CSS
- Adicionar níveis de dificuldade com diferentes intervalos
- Modificar o número máximo de tentativas permitidas

## Tecnologias Utilizadas

- HTML5
- CSS3 (Flexbox, Gradients, Media Queries)
- JavaScript (ES6)
- Local Storage para persistência de dados
