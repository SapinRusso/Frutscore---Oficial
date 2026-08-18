# Frutscore — SFF Futebol

Repositório do projeto **Frutscore**, plataforma fictícia de resultados, estatísticas, clubes, jogadores e simulações de partidas do universo SFF Futebol, ambientado no futebol mundial real com o país fictício sul-americano **Frutil**.

## Conteúdo deste snapshot

Este pacote reúne o material disponível no projeto até agosto de 2065 no universo da simulação:

- código-fonte/protótipos do Frutscore;
- banco bruto de jogadores importado do Match Simulator;
- documentação e textos de simulação;
- simuladores 2D de partidas em HTML/CSS/JavaScript;
- imagens de referência de escalações.

## Estrutura

```text
frutscore/
├── README.md
├── site-source/
│   ├── Frutscore-Beta-V4.0.txt
│   └── README-starter.md
├── simulators/
│   ├── frutscore-campo-grande-benfica-2065-2d-completo.html
│   ├── frutscore-campo-grande-benfica-2065-2d-v2-corrigido.html
│   ├── frutscore-campo-grande-benfica-2065-2d-v3-tatico.html
│   ├── frutscore-campo-grande-benfica-2065-2d-v4-posse-tatica.html
│   ├── frutscore-campo-grande-benfica-2065-2d-v4-1-dinamico.html
│   ├── frutscore-campo-grande-benfica-2065-2d-v4-2-posse-eventos.html
│   ├── frutscore-bab-minnesota-2065-2d-v1-epico.html
│   └── frutscore-horizonte-sul-atalanta-2065-2d-v1.html
├── data/
│   └── jogadores-matchsimulator.md
├── docs/
│   ├── Simulacao-Frutil.txt
│   └── README-*.txt
└── assets/
    └── reference-images/
```

## Frutscore

Conceito: **Todo o futebol de Frutil. Em tempo real.**

Principais áreas planejadas:

- Início
- Jogos
- Competições
- Times
- Jogadores
- Mercado
- Rankings
- Seleção
- Notícias
- Dados

## Competições principais

- Frutileirão Série A
- Frutileirão Série B
- Copa do Frutil
- Regionais
- Amistosos
- Supercopa do Frutil
- Supercopa Eixo
- Superliga Eixo
- Pré-Temporada

## Observações técnicas

Os simuladores 2D são protótipos standalone em HTML, CSS e JavaScript. O produto principal segue direção de **Next.js + React + TypeScript**, com migração futura para PostgreSQL + Prisma e autenticação server-side.

A autenticação local usada em protótipos com `localStorage` não deve ser considerada autenticação de produção.

## Universo

Frutil é um país fictício localizado na América do Sul. Clubes, cidades, estados e instituições internas de Frutil são fictícios, coexistindo com o futebol mundial real dentro da simulação.
