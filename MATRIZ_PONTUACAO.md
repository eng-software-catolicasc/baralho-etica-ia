# MATRIZ DE PONTUAÇÃO — v1.5.4

Regra: em cada deck existem duas cartas de referência (+50 cada). As demais têm penalidade temática. O score do deck é a soma dos valores das cartas selecionadas, limitada entre 0% e 100%. Assim, a dupla de referência = 100%; cartas adicionais não ideais retiram pontos. O envio exige no mínimo 2 cartas por deck liberado.

## Valores por carta

### R
R01: +50 | R02: -10 | R03: -15 | R04: -15 | R05: +50 | R06: -10 | R07: -10 | R08: -15

### C
C01: +50 | C02: -10 | C03: -15 | C04: +50 | C05: -15 | C06: -10 | C07: -15 | C08: -10

### H
H01: +50 | H02: -10 | H03: +50 | H04: -15 | H05: -15 | H06: -10 | H07: -10 | H08: -15

### E
E01: +50 | E02: -10 | E03: -15 | E04: -10 | E05: +50 | E06: -10 | E07: -15 | E08: -15

### D
D01: +50 | D02: +50 | D03: -10 | D04: -10 | D05: -15 | D06: -15 | D07: -10 | D08: -10

### CO
CO01: +50 | CO02: -10 | CO03: -15 | CO04: -15 | CO05: -10 | CO06: +50 | CO07: -10 | CO08: -10

### RE
RE01: +50 | RE02: -10 | RE03: +50 | RE04: -10 | RE05: -15 | RE06: -10 | RE07: -15 | RE08: -10

### M
M01: +50 | M02: -10 | M03: -15 | M04: -15 | M05: -10 | M06: -10 | M07: +50 | M08: -10

## Cálculos

- Score do deck = clamp(soma dos valores selecionados, 0, 100).
- Score do encontro = média dos 4 scores dos decks submetidos naquele encontro.
- Score final = média dos 8 scores dos decks, somente quando houver submissão dos dois encontros.
- O painel do professor mostra códigos, valor de cada carta, score por deck, score do encontro e score final.
- Os estudantes não veem os valores nem o score durante a atividade.