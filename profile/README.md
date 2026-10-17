# Percepta

**Entenda o que a sua postura e a sua roupa comunicam, em cada contexto.**

A Percepta ajuda jovens a perceber como a postura e a roupa são lidas pelos outros em situações diferentes, como uma entrevista, uma apresentação na faculdade ou um encontro com amigos. O objetivo é dar clareza e pequenos passos práticos, para que cada pessoa escolha com mais consciência como quer se apresentar.

Projeto desenvolvido em equipe no curso **PROA PROPROFISSÃO**.

---

## O problema

Muitas vezes existe uma diferença entre a imagem que queremos passar e a imagem que os outros percebem. Chamamos isso de **ruído de percepção**. Para quem está começando a entrar no mercado de trabalho, essa diferença pode pesar sem que a pessoa saiba que ela existe.

A Percepta mostra esse ruído de forma simples e acolhedora, sem julgar a pessoa.

## Como funciona

1. **Escolha o contexto:** situações profissionais, acadêmicas ou sociais.
2. **Escolha o objetivo:** o que você quer comunicar nessa situação.
3. **Envie uma foto:** pela câmera ou pela galeria.
4. **Receba a análise:** uma inteligência artificial avalia como a sua roupa e a sua postura tendem a ser percebidas naquele contexto e escreve um feedback para você.
5. **Cumpra missões:** pequenas ações práticas, criadas a partir do seu feedback, para evoluir aos poucos.
6. **Reavalie:** envie uma nova foto e compare com a sua última análise ou com a primeira, para ver o seu antes e depois.

## Nossos princípios

- **Percepção, não julgamento.** O resultado mostra como roupa e postura tendem a ser percebidas, e não quem a pessoa é.
- **Só roupa e postura.** A análise não comenta corpo, rosto, idade, etnia ou deficiência.
- **Privacidade primeiro.** A foto é usada apenas para gerar a análise e não é guardada. O que fica salvo é o resultado.
- **Sem a sua imagem no antes e depois.** A evolução é mostrada com métricas e ilustrações, nunca com fotos da pessoa.
- **Transparência.** O resultado é uma avaliação feita por um sistema, e serve como orientação, não como veredito.

## Tecnologias

| Camada | Tecnologia |
|---|---|
| App | Jetpack Compose (Android) |
| API | Spring Boot |
| Banco de dados | MongoDB |
| Análise | Integração com modelo de inteligência artificial |

## Repositórios

| Repositório | Descrição |
|---|---|
| `percepta-app` | Aplicativo Android |
| `percepta-api` | API que recebe a foto, chama a IA e guarda o resultado |

## Status

Projeto acadêmico em desenvolvimento. O foco atual é o MVP: fluxo de preparação, análise com feedback, missões e reavaliação.
