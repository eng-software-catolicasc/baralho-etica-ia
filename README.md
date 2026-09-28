# Ética na Inteligência Artificial — v1.5.3 Local

Correções no painel do professor:
- resultados expandidos permanecem abertos durante a atualização automática;
- Total E1 soma as cartas selecionadas nos decks 1–4;
- Total E2 soma as cartas selecionadas nos decks 5–8;
- cada submissão mostra o total de cartas do encontro e a quantidade por deck.

# Ética na Inteligência Artificial — v1.5.2 Local

Versão local com SQLite. Preserva o visual da v1.4.4 e acrescenta 9 grupos, QR por grupo, bloqueio/liberação de decks, favoritos persistentes, validação de envio e snapshots das submissões.

## Executar

1. Abra esta pasta inteira no VS Code.
2. Terminal > New Terminal.
3. Execute `npm install` (somente na primeira vez).
4. Execute `npm start`.
5. Professor: http://localhost:3000/professor
   - usuário: `professor`
   - senha: `etica2026`
6. Grupo 01: http://localhost:3000/g/grupo-01-etica-ia-2026

## Importante sobre QR local

Um QR que contém `localhost` funciona no mesmo computador. Para abrir o QR em um celular durante teste local, o servidor precisará ser exposto na rede local ou em uma URL pública. No Render, o QR usará a URL pública normalmente.

## Submissões

O painel do professor mostra um card por submissão. `VER RESULTADO` exibe os códigos das cartas escolhidas em cada deck. O registro é um snapshot do momento do envio.


## v1.5.4 — pontuação
A pontuação oculta foi implementada. Consulte `MATRIZ_PONTUACAO.md`. O envio exige no mínimo 2 cartas em cada deck liberado. O painel do professor mostra valores, score por deck, score do encontro e score final quando os dois encontros forem submetidos.
