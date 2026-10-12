# 🎮 Jornada Geodinâmica — Explorando o Brasil e o Mundo

Jogo de tabuleiro educativo para o 9º ano, feito em um único arquivo HTML (sem dependências, exceto as fontes do Google Fonts).

## Como jogar
1. Abra o `index.html` no navegador.
2. Escolha de 2 a 4 jogadores e digite os nomes.
3. Jogue o dado e responda à pergunta da casa (30 segundos).
4. Acertou: ganha pontos e fica na casa. Errou ou o tempo acabou: volta 2 casas.
5. Vence quem chegar à casa 49 e acertar a pergunta final.

## Fases
- Casas 2–16: Fácil (10 pts)
- Casas 17–32: Médio (20 pts)
- Casas 33–49: Difícil (30 pts)

## Publicar no GitHub Pages
Em **Settings → Pages**, selecione a branch `main` e a pasta `/ (root)`.

## Adicionar perguntas
No `index.html`, edite o objeto `DATA`. Cada pergunta é um array:
`[pergunta, resposta correta, errada 1, errada 2, errada 3, explicação]`
