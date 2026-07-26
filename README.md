<h1 align="left">Juliano Vince de Campos</h1>

<p align="left">
  <strong>Staff Engineer / SRE — confiabilidade e segurança em sistemas financeiros regulados</strong><br/>
  Acho a causa raiz onde ela está, mede o resultado, e transforma a medição em gate de CI.
</p>

<p align="left">
  <a href="https://julianovincedecampos.com/" target="_blank">
    <img src="https://img.shields.io/badge/Bio-julianovincedecampos.com-black?style=for-the-badge" alt="Bio" />
  </a>
  <a href="https://www.linkedin.com/in/julianovincecampos/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-julianovincecampos-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
</p>

---

## O que eu faço

14 anos em fintechs, bancos e plataformas digitais. Hoje atuo em **infraestrutura de registradora
de ativos** sob supervisão do Banco Central: monolito Java EE sobre DB2, microsserviços em EKS,
AWS multi-conta, e a esteira de qualidade de mais de 300 repositórios.

O trabalho que me interessa é o que aparece nos três lugares abaixo, nesta ordem:

- **Causa raiz, não sintoma.** Ler o código de quem já foi embora, encontrar por que o incidente
  volta, e provar a correção com número antes de propô-la.
- **Segurança aplicada, não checklist.** DevSecOps que bloqueia merge, IAM que fecha caminho de
  privilégio, e chave que rotaciona com procedimento testado — não com intenção documentada.
- **IA com régua.** LLM perto de produção com baseline determinístico, avaliação medida,
  aprovação humana e teto de custo. A parte difícil nunca é chamar o modelo.

---

## Projetos

| Projeto | O que é | Resultado |
|---|---|---|
| **[postmortem-miner](https://github.com/JulianoVinceCampos/postmortem-miner)** | Transforma uma pilha de postmortems em árvore de decisão de triagem. Zero dependência de runtime, determinístico, explicável | **8 padrões explicam 90% de 20 incidentes em 15 ms**, com triagem de profundidade 4 |

Cada repo carrega esteira de 10 camadas: sanitização, lint, testes em matriz, cobertura com ratchet
que só sobe, Semgrep, CodeQL bloqueante, SCA, quality gate, SBOM e atestação de proveniência.
Commits assinados, histórico linear.

**Em construção**, na ordem:

- `llm-eval-gate` — gate de CI que reprova o PR quando a qualidade de saída do LLM regride. Spec
  executável, variância entre execuções, orçamento de custo e latência.
- `ledger-forensics` — detecção de fraude em escrituração contábil com cadeia de hash
  tamper-evident e validação de assinatura de documento fiscal.
- `bulk-ingest-lab` — ingestão monolítica virando streaming com chunking transacional, medido em
  JMH e com gate de regressão de memória.

---

## Como eu trabalho

Quatro coisas aparecem em tudo que eu construo, e são o que eu levo para um time:

**Baseline determinístico antes de qualquer IA.** Primeiro a solução explicável, depois a medição
de se o modelo agrega. Nessa ordem, sempre.

**Ground truth que permite medir.** Se não dá para calcular precisão e recall, é opinião. Meus
geradores de dado sintético plantam o problema de propósito, justamente para que a detecção seja
verificável.

**O número do README é defendido por CI.** Benchmark, cobertura e qualidade de LLM entram como gate
de regressão. Número que ninguém defende envelhece em silêncio.

**Reprodutibilidade em máquina limpa.** Um comando, sem chave de API, sem conta em nuvem. "Funciona
aqui" não é resultado.

---

## Trajetória técnica

**Plataforma e confiabilidade** — AWS multi-conta com Terraform, Terragrunt e Atlantis · EKS ·
Datadog com SLI/SLO e resposta a incidente · resposta a P1 em produção financeira · DB2 e WildFly em
carga real.

**Segurança** — Secure SDLC e DevSecOps em escala de organização · SAST e SCA como gate de merge ·
IAM Identity Center, KMS e gestão de certificado · Resolução BCB 304, ISO 20000, LGPD.

**Backend** — Java e Java EE · Spring · Python · arquitetura orientada a evento · Clean Architecture,
DDD e Hexagonal.

**Mobile** — Kotlin, Android, Swift, iOS e Flutter. Origem da carreira e o acervo mais antigo aqui no
perfil.

---

## Contato

Brasil (SP/GO) · [julianovincedecampos.com](https://julianovincedecampos.com/) ·
[LinkedIn](https://www.linkedin.com/in/julianovincecampos/)

<sub>Perfil anterior: <a href="https://github.com/JulianoVince">@JulianoVince</a></sub>
