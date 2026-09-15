# Movita

Movita foi meu Trabalho de Conclusão de Curso (TCC), desenvolvido ao longo de ~6 meses na
**Fundação Matias Machline**. O projeto foi premiado na Feira de Inovação da instituição, na
categoria **"Cidades Inteligentes"**.

A proposta era um app de mobilidade urbana com um diferencial: usar **realidade aumentada** para
guiar o usuário até pontos de ônibus e destinos, além de um painel web e um app mobile para
consulta de rotas.

Este repositório não tem código — é só um índice explicando o que cada parte do projeto faz,
já que o trabalho ficou espalhado em 5 repositórios.

## Stack

| Camada | Tecnologias |
|---|---|
| Backend | Nest.js, PostgreSQL, Prisma |
| Web | Next.js |
| Mobile | React Native |
| Realidade Aumentada | Three.js, WebXR |

## Repositórios

- **[movita-backend](https://github.com/AlexandreJr16/movita-backend)** — API em Nest.js com
  Prisma/PostgreSQL. Autenticação, rotas, pontos de ônibus e dados consumidos pelo web e pelo
  mobile.
- **[movita-web](https://github.com/AlexandreJr16/movita-web)** — painel web em Next.js para
  consulta de rotas e gestão de dados.
- **[movita-app](https://github.com/AlexandreJr16/movita-app)** — aplicativo mobile em React
  Native, versão do Movita para o usuário final consultar rotas e pontos.
- **[movita-ar](https://github.com/AlexandreJr16/movita-ar)** — módulo de realidade aumentada em
  Three.js/WebXR: sobrepõe indicações de rota e pontos de ônibus na câmera do dispositivo.
- **[Movita-lp](https://github.com/AlexandreJr16/Movita-lp)** — landing page do projeto.

## Contexto

Trabalho de conclusão de curso técnico em Computação, individual, com ~6 meses de
desenvolvimento (levantamento de requisitos, backend, apps web/mobile e o módulo de AR). O
projeto foi um dos premiados na Feira de Inovação da Fundação Matias Machline.

---

<details>
<summary><b>English</b></summary>

Movita was my capstone project (~6 months) at Fundação Matias Machline, a technical school in
Manaus, Brazil. It won an award at the school's Innovation Fair, in the "Smart Cities" category.

The idea was an urban mobility app with augmented reality guidance to bus stops and
destinations, plus a web dashboard and a mobile app for route lookup.

This repository has no code — it's an index explaining what each of the 5 repositories that
make up the project does. See the table and repo list above (stack: Nest.js + PostgreSQL +
Prisma on the backend, Next.js for web, React Native for mobile, Three.js/WebXR for AR).

</details>
