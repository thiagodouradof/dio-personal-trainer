<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-️-tipos-de-exercícios)
- [🎯 Objetivo do Treino](#-objetivo-do-treino)
- [🧗 Nível de Treino](#-nível-de-treino)
- [🔧 Equipamentos Disponíveis](#-equipamentos-disponíveis)
- [⏳ Tempo de Treino](#-tempo-de-treino)
- [⚠️ Preferências e Restrições](#️-preferências-e-restrições)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [📖 Material de Apoio](#-material-de-apoio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🎯 Objetivo do Treino

| **Imagem**                                                   | **Objetivo**              | **Descrição**                                                  |
| ------------------------------------------------------------ | ------------------------- | -------------------------------------------------------------- |
| <img src=".github/assets/goal.png" width="50" height="50%">  | **Ganho de Massa Muscular**| Foco em exercícios compostos e progressão de carga.             |
| <img src=".github/assets/goal.png" width="50" height="50%">  | **Perda de Gordura**       | Foco em exercícios de alta intensidade e circuitos.             |
| <img src=".github/assets/goal.png" width="50" height="50%">  | **Aumento de Resistência** | Foco em exercícios de resistência e volume.                    |

---

## 🧗 Nível de Treino

| **Imagem**                                                   | **Nível de Treino** | **Descrição**                                                  |
| ------------------------------------------------------------ | ------------------- | -------------------------------------------------------------- |
| <img src=".github/assets/level.png" width="50" height="50%"> | **Iniciante**       | Exercícios básicos com foco em técnica.                         |
| <img src=".github/assets/level.png" width="50" height="50%"> | **Intermediário**   | Exercícios com maior volume e intensidade.                      |
| <img src=".github/assets/level.png" width="50" height="50%"> | **Avançado**        | Exercícios complexos e de alta intensidade.                     |

---

## 🔧 Equipamentos Disponíveis

| **Imagem**                                                   | **Equipamento**   | **Descrição**                                                                                                  |
| ------------------------------------------------------------ | ----------------- | -------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/halter.png" width="50" height="50%"> | **Halteres**       | Exercícios que utilizam halteres, com movimentos variados e liberdade de carga.                                 |
| <img src=".github/assets/halter.png" width="50" height="50%"> | **Barras**         | Exercícios com barras, focando em força e progressão de carga.                                                  |

---

## ⏳ Tempo de Treino

| **Imagem**                                                     | **Tempo de Treino** | **Descrição**                                                          |
| -------------------------------------------------------------- | ------------------- | ---------------------------------------------------------------------- |
| <img src=".github/assets/clock.png" width="50" height="50%">   | **30 minutos**      | Treinos rápidos e intensos.                                             |
| <img src=".github/assets/clock.png" width="50" height="50%">   | **60 minutos**      | Treinos completos com aquecimento, exercícios principais e alongamento. |

---

## ⚠️ Preferências e Restrições

| **Imagem**                                                     | **Preferência/Restrição** | **Descrição**                                                                                         |
| -------------------------------------------------------------- | ------------------------- | ----------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/preference.png" width="50" height="50%">    | **Evitar Agachamentos**   | Preferência por evitar agachamentos devido a lesão ou desconforto nos joelhos.                         |
| <img src=".github/assets/preference.png" width="50" height="50%"> | **Outras Preferências**    | Outras preferências que possam ser especificadas, como exercícios de baixo impacto ou com modificações. |

---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. **Defina seu objetivo de treino** para direcionar a escolha dos exercícios.
5. **Identifique seu nível** para garantir que o treino seja ajustado à sua capacidade.
6. **Informe os equipamentos disponíveis** que vão guiar o tipo de exercício que pode ser feito.
7. **Determine o tempo disponível por treino**, para ajustar o volume e a estrutura do treino.
8. **Informe suas preferências e restrições**, para adaptar os exercícios e garantir sua segurança.

---

## 📖 Material de Apoio

Aqui estão alguns recursos adicionais que podem ser úteis para entender melhor o projeto e as práticas de prompt engineering:

- [Fundamentos de Engenharia de prompt](https://elidianaandrade.gitbook.io/fundamentos-de-engenharia-de-prompts-com-claude-3)
- [Boas práticas de prompt](https://aline-antunes.gitbook.io/otimize-seus-prompts-e-aprenda-mais-usando-ias-1)

---

## 🎯 Prompt de Resposta Proposto

Com base nas variáveis fornecidas pelo usuário, aqui está um exemplo de prompt para criar um plano de treino personalizado:

---

**Prompt:**

```markdown
Olá, você pode criar um treino novo para mim?

Minhas informações:

- Biotipo: Ectomorfo (corpo mais magro, com dificuldade para ganhar massa muscular)
- Dias de Treino: 5 dias por semana
- Tipo de Exercício: Peso Livre e Funcional
- Objetivo: Ganho de Massa Muscular
- Nível: Intermediário
- Equipamentos: Halteres e Barras
- Tempo Disponível: 60 minutos por treino
- Preferências: Evitar agachamentos devido a lesão no joelho
