<div align="center">

<a href="./README.md"><img src="https://img.shields.io/badge/EN-English-0D1117?style=for-the-badge&labelColor=212E38"></a>
<a href="./README.pt-BR.md"><img src="https://img.shields.io/badge/PT--BR-Portugu%C3%AAs-0D1117?style=for-the-badge&labelColor=E5813E"></a>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=190&color=0:0D1117,55:212E38,100:E5813E&text=Lucas%20Manoel&fontColor=E2EAF1&fontSize=52&fontAlignY=34&desc=AI%20Systems%20Engineer&descSize=16&descAlignY=52&section=header" />

<img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=21&duration=3200&pause=900&color=E5813E&center=true&vCenter=true&width=780&height=44&lines=I+build+AI+agents+that+run+in+production;Construo+agentes+de+IA+que+rodam+em+produ%C3%A7%C3%A3o;Multi-agent+orchestration+%C2%B7+WhatsApp+%C2%B7+Voice+%C2%B7+RAG;Not+demos.+Systems+that+invoice." />

</div>

---

> **Eu transformo operação manual e dependente de gente em sistema de IA que roda sozinho.**
>
> Agentes que prospectam e agendam. Pipelines que leem documento regulado e citam a fonte. Automação de mídia que escala produção de conteúdo sem precisar de um editor por vídeo.
>
> Não é demo. Não é prova de conceito. É arquitetura feita para sobreviver ao contato com usuário real.

---

## O que eu construo

<table>
<tr>
<td width="33%" valign="top">

### 🗣 Agentes conversacionais

Agentes autônomos que prospectam, qualificam e agendam por WhatsApp e DM do Instagram — com roteamento que decide qual agente atende cada conversa.

`Agentes-Avos` · `sistema-mentores`

</td>
<td width="33%" valign="top">

### 🧠 Inteligência aplicada

Sistemas que leem, classificam e pontuam — transformando realidade desestruturada em decisão acionável, com citação de fonte no lugar de alucinação.

`processia` · `ai-first` · `ragia`

</td>
<td width="33%" valign="top">

### ⚙️ Mídia e automação de operação

Pipelines que eliminam trabalho manual em escala: legendagem de vídeo, clonagem de voz e análise de funil comercial.

`pycaps-api` · `qwentts` · `dash-kommo`

</td>
</tr>
</table>

---

## Trabalhos selecionados

<table>
<tr>
<td width="50%" valign="top">

#### 🔺 ai-first — Triagem automática de bugs
Agentes Mastra que classificam bugs no ClickUp: severidade (P0–P3), módulo afetado, canal de origem e responsável sugerido — depois postam o raciocínio estruturado e movem o card.

Opera com **exigência de 100% de recall na detecção de dado sensível (LGPD)** — um falso negativo ali é incidente de conformidade, não bug.

`Multi-agent` `Mastra` `ClickUp` `LGPD`

[→ Repositório](https://github.com/lucas-ai-max/ai-first)

</td>
<td width="50%" valign="top">

#### 🔺 Agentes-Avos — Dois agentes, um processo
Um agente de SDR e um de agendamento registrados no mesmo runtime Mastra, dividindo uma única porta de webhook da Meta.

Um roteador consulta whitelist no Postgres para decidir quem atende cada DM — **sem salto HTTP entre processos**, então não existe um segundo serviço para subir, monitorar ou perder.

`Multi-agent` `Instagram DM` `Google Calendar` `Postgres`

[→ Repositório](https://github.com/lucas-ai-max/Agentes-Avos)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔺 processia — Análise de processos jurídicos
Lê os autos completos com Docling e responde perguntas sobre eles via LLM — **toda resposta carrega a página e o arquivo de onde veio.**

Em domínio regulado, resposta que você não consegue rastrear é pior que resposta nenhuma.

`Document AI` `Docling` `Streamlit` `Supabase`

[→ Repositório](https://github.com/lucas-ai-max/processia)

</td>
<td width="50%" valign="top">

#### 🔺 sistema-mentores — Debate como arquitetura
Uma mesa de mentores de IA no WhatsApp. Um orquestrador aprova ou recusa a pergunta, os mentores debatem em duas rodadas fixas e o sistema entrega uma única resposta sintetizada.

Discordância estruturada no lugar do primeiro chute de um modelo só.

`Multi-agent` `FastAPI` `Evolution API` `WhatsApp`

[→ Repositório](https://github.com/lucas-ai-max/sistema-mentores)

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🔺 pycaps-api — Legendagem de vídeo em escala
Serviço FastAPI que recebe o vídeo cru e devolve com legenda animada embutida — containerizado, então escala na horizontal em vez de esperar um editor.

`FastAPI` `Docker` `Video processing`

[→ Repositório](https://github.com/lucas-ai-max/pycaps-api)

</td>
<td width="50%" valign="top">

#### 🔺 ragia — RAG do zero
Entra conversa de suporte, sai par de pergunta e resposta: a OpenAI gera os pares, os embeddings são calculados por par e tudo aterrissa no Supabase com pgvector.

Pequeno de propósito — é a camada de retrieval, legível de ponta a ponta.

`RAG` `Embeddings` `pgvector` `Python`

[→ Repositório](https://github.com/lucas-ai-max/ragia)

</td>
</tr>
</table>

---

## Stack

<div align="center">

**Agentes e orquestração**

<img src="https://skillicons.dev/icons?i=typescript,python,fastapi&theme=dark" height="42">
<img src="https://img.shields.io/badge/Mastra-0D1117?style=for-the-badge&logoColor=E5813E">
<img src="https://img.shields.io/badge/CrewAI-0D1117?style=for-the-badge&logoColor=E5813E">
<img src="https://img.shields.io/badge/n8n-0D1117?style=for-the-badge&logo=n8n&logoColor=E5813E">

**Modelos e retrieval**

<img src="https://img.shields.io/badge/OpenAI-0D1117?style=for-the-badge&logo=openai&logoColor=E5813E">
<img src="https://img.shields.io/badge/Claude-0D1117?style=for-the-badge&logo=anthropic&logoColor=E5813E">
<img src="https://img.shields.io/badge/Gemini-0D1117?style=for-the-badge&logo=googlegemini&logoColor=E5813E">
<img src="https://img.shields.io/badge/pgvector-0D1117?style=for-the-badge&logo=postgresql&logoColor=E5813E">

**Dados e infra**

<img src="https://skillicons.dev/icons?i=supabase,postgres,docker,redis,vercel,nextjs&theme=dark" height="42">

</div>

---

## Ritmo de engenharia

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lucas-ai-max/lucas-ai-max/output/snake-dark.svg">
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/lucas-ai-max/lucas-ai-max/output/snake-light.svg">
</picture>

</div>

---

<div align="center">

### Tem um processo manual que não deveria ser manual?

<a href="https://www.linkedin.com/in/lucas-manoel-9066a31a9/"><img src="https://img.shields.io/badge/LinkedIn-Lucas%20Manoel-0D1117?style=for-the-badge&logo=linkedin&logoColor=E5813E"></a>

<sub>Resposta em até 24h</sub>

</div>
