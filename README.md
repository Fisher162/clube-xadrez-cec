# Clube de Xadrez do CEC Diocesano Janaúba

Site do clube com ranking geral, cadastro de jogadores, registro de partidas, cálculo automático de rating Elo e organização de torneios.

## Primeira versão

O site é uma aplicação estática: abra `index.html` em um navegador para testar.

### Recursos disponíveis
- Cadastro e remoção de jogadores.
- Ranking geral ordenado por rating.
- Rating Elo inicial de 1000 pontos e fator K = 32.
- Registro de vitórias, derrotas e empates.
- Histórico de partidas.
- Cadastro de torneios e associação de partidas.

## Publicação

O repositório contém um workflow em `.github/workflows/pages.yml` para publicação pelo GitHub Pages a cada atualização da branch `main`.

No GitHub, acesse **Settings → Pages** e selecione **GitHub Actions** como origem de publicação, caso ainda não esteja selecionado. Depois, acompanhe a execução em **Actions**.

## Limitações importantes desta versão

Os dados ficam salvos no armazenamento local do navegador. Portanto, não são compartilhados entre dispositivos ou usuários e podem ser apagados se os dados do navegador forem limpos. Ainda não há autenticação nem permissões reais para administrador e monitores. Antes do uso oficial, será necessário integrar banco de dados e autenticação, além de restringir o registro de resultados aos usuários autorizados.

## Tecnologias

HTML, CSS e JavaScript puro.