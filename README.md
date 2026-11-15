<div align="center">

# Bruno Ramos

**Desenvolvedor full stack · Ciência da Computação na UFRGS · IA aplicada a produto**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square)](https://www.linkedin.com/in/bruno-andrade-ramos-7a7844267/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/brunoramos09)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/brunoandraderamos)
[![Checkpointd](https://img.shields.io/badge/checkpointd.com-0F4C81?style=flat-square)](https://www.checkpointd.com)

</div>

Estagiei 1 ano e 10 meses como full stack e, em paralelo, criei sozinho uma rede social de jogos que hoje está na web, na Play Store e na App Store. Agora estou aprofundando em machine learning e em como colocar IA em produto de um jeito que dê para medir.

## Projetos

### [Checkpointd](https://www.checkpointd.com)

Rede social para registrar, avaliar e organizar jogos, com site, API e apps Android e iOS.

- Next.js 16, React 19 e TypeScript no site; PostgreSQL com SQL direto e migrations; app em React Native com Expo
- Crons e deploy na Vercel, monitoramento com Sentry
- 1.589 commits e 465 arquivos de teste (Vitest, Playwright e Jest)
- O código é privado, mas a parte de IA está aberta no repositório abaixo

### [game-similarity](https://github.com/brunoramos09/game-similarity)

A recomendação de jogos parecidos do Checkpointd, medida antes de ir para produção.

- Embeddings `voyage-4-lite` com pgvector sobre 31.749 jogos, atualizados por um cron que só refaz o que mudou
- **precision@5 de 0,180**, contra 0,053 de um modelo aberto e 0,047 de um baseline por gêneros, com intervalos bootstrap
- Fine-tuning de um modelo aberto com 24 mil pares: melhorou no teste do IGDB, mas não no gabarito, então ficou de fora
- [Demo](https://huggingface.co/spaces/brunoramos09/game-similarity-demo) · [Modelo no Hugging Face](https://huggingface.co/brunoramos09/game-similarity-bge-small)

### [Housing Prices no Kaggle](https://www.kaggle.com/code/brunoandraderamos/house-prices-xgboost-com-one-hot-e-early-stopping)

- XGBoost com one-hot encoding e early stopping
- Erro médio de **US$ 15,4 mil**, contra 21,2 mil da random forest do curso

## Experiência

**Sys-On Softwares** · Estagiário full stack · set/2024 a jul/2026

Telas, funcionalidades e correções em sistemas web com Java, JSF, PrimeFaces e SQL Server.

## Tecnologias

<table>
  <tr>
    <td><b>Linguagens</b></td>
    <td>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">&nbsp;<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">&nbsp;<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">&nbsp;<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java">&nbsp;<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square" alt="SQL">
    </td>
  </tr>
  <tr>
    <td><b>Web e mobile</b></td>
    <td>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js">&nbsp;<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React">&nbsp;<img src="https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native">&nbsp;<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">&nbsp;<img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
    </td>
  </tr>
  <tr>
    <td><b>Banco e infra</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">&nbsp;<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">&nbsp;<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel">&nbsp;<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
    </td>
  </tr>
  <tr>
    <td><b>Dados e ML</b></td>
    <td>
      <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas">&nbsp;<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn">&nbsp;<img src="https://img.shields.io/badge/XGBoost-337AB7?style=flat-square" alt="XGBoost">&nbsp;<img src="https://img.shields.io/badge/sentence--transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="sentence-transformers">
    </td>
  </tr>
</table>
