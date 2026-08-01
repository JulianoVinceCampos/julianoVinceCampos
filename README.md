<!--
  Juliano Vince de Campos - GitHub Profile README
  Staff Principal Software Architect, Engineering Manager, Cybersecurity Engineer,
  AI Engineering Lead, SRE, DevSecOps, AppSec, IAM, IGA, SailPoint, Zero Trust,
  OAuth2, OIDC, SAML, PAM, RBAC, ABAC, SoD, threat modeling, SSDLC, SAST, DAST, SCA,
  Semgrep, SonarQube, CodeQL, GenAI, LLM, RAG, MCP, AI Agents, LLMOps, MLOps,
  prompt injection, guardrails, AWS Bedrock, OpenAI, Anthropic, LangChain, n8n,
  AWS, Azure, Kubernetes, Docker, Terraform, Datadog, observability, SLI, SLO,
  incident response, postmortem, MTTR, DORA metrics, Java, Kotlin, Spring, Python,
  Android, iOS, Clean Architecture, Hexagonal, DDD, microservices, event-driven,
  fintech, banking, payments, PCI-DSS, ISO 27001, LGPD, NIST CSF, BACEN, COBIT, ITIL,
  engineering management, tech lead, technical leadership, Brazil, Sao Paulo, Goiania.
-->

<h1 align="left">Juliano Vince de Campos</h1>

<p align="left">
  <strong>Staff / Principal Architect · Engineering Manager · Cibersegurança · AI Engineering</strong><br/>
  18+ anos em tecnologia, 9 deles em cibersegurança. Fintech e banking, em ambiente regulado.<br/>
  Aqui ficam as <strong>provas executáveis</strong> do que o meu currículo afirma.
</p>

<p align="left">
  <sub>✡︎ &nbsp;<strong>אֱמֶת</strong> — <em>emet</em>, verdade. O que um sistema precisa dizer quando ninguém está olhando.</sub>
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

## Por que este perfil existe

Currículo afirma. Código prova.

Cada repositório aqui foi construído para tornar **verificável** uma competência que a minha
trajetória sustenta: leitura de causa raiz em sistema legado, segurança como propriedade da
arquitetura, e IA aplicada com régua em vez de entusiasmo. Todos rodam com um comando, em máquina
limpa, sem chave de API e sem conta em nuvem.

---

## Provas públicas

| Repositório | O que comprova | Resultado medido |
|---|---|---|
| **[postmortem-miner](https://github.com/JulianoVinceCampos/postmortem-miner)** | SRE de verdade: transformar histórico de incidente em decisão de triagem, o mesmo método que sustenta redução de MTTR | **8 padrões explicam 90% de 20 incidentes em 15 ms**, triagem de profundidade 4 · 93 testes · cobertura 99% |
| **[shomer-oncall](https://github.com/JulianoVinceCampos/shomer-oncall)** | Calendário hebraico aplicado a escala de plantão: fronteiras por *zmanim* astronômicos (não tabela chumbada) e repartição justa entre quem observa e quem não | **Observantes carregam a mesma weighted load sem pegar nenhum Shabat** (Jain 0.9998, spread 1.0, 0 violations em 92 dias) · calendário hebraico e *zmanim* do zero, zero dependências de runtime · 77 testes · cobertura 96% |
| **[iam-governance-lab-web](https://github.com/JulianoVinceCampos/iam-governance-lab-web)** | IAM e IGA, o eixo de 9 anos: SoD, privilege reachability cross-account, ciclo JML e recertification, tudo read-only com procedência | **37 violações de SoD em 4 severidades, 12 caminhos de escalonamento cross-account, 9 targets sensíveis** · RBAC e ABAC lado a lado com procedência · dashboard interativo e [demo no ar](https://iam-governance-lab-web.onrender.com) · 64 testes em Python 3.11 a 3.13 · CI com Semgrep, CodeQL e pip-audit |

**Em construção**, cada um ligado a uma competência específica:

| Repositório | Comprova | Conteúdo |
|---|---|---|
| `llm-eval-gate` | LLMOps e guardrails de IA generativa | Gate de CI que reprova o PR quando a qualidade da saída do LLM regride. Spec executável, variância entre execuções, orçamento de custo e latência, e comparação honesta contra baseline determinístico |
| `ledger-forensics` | Criptografia aplicada e ambiente de Autoridade Certificadora | Detecção de fraude em escrituração com ground truth injetado, cadeia de hash tamper-evident, validação de XMLDSig e PKI de teste própria |
| `dora-lens` | Gestão de engenharia com dado, não com percepção | Calcula as quatro métricas DORA direto da API do GitHub, com cada definição e cada caso de borda documentados. Porque "lead time caiu" sem definição escrita é anedota |
| `bulk-ingest-lab` | Performance engineering em stack legada | Ingestão monolítica virando streaming com chunking transacional, medida em JMH e com gate de regressão de memória |

Todo repo nasce com a mesma esteira de 10 camadas: sanitização, lint, testes em matriz, cobertura com
ratchet que só sobe, Semgrep, CodeQL bloqueante, SCA, quality gate, SBOM e atestação de proveniência.
Commits assinados e histórico linear, sempre.

---

## Resultados em produção

O que foi entregue em ambiente real, com número. O detalhe de cada contexto está no
[LinkedIn](https://www.linkedin.com/in/julianovincecampos/).

| Frente | Resultado |
|---|---|
| **Pagamentos** (PagoNxt / Santander) | taxa de sucesso transacional de **65% → 92%** em 8 meses · MTTR de **2h40 → 18 min** · falhas críticas −60% |
| **Engenharia e DORA** (Luby) | cobertura de teste **0 → 82% em 3 meses** · lead time **14 dias → 2 dias** · cycle time **5 dias → 8h** · change failure rate **25% → 5%** |
| **IAM e IGA** (Creditas) | **−45%** acessos acima do necessário · provisionamento de dias para horas (**−60%**) · **−28%** incidentes de autenticação e permissão |
| **Segurança em banking** (Itaú Unibanco) | **−42%** privilégios excessivos · remoção de acesso de 5 dias para **<48h** · **−33%** esforço de auditoria BACEN e LGPD |
| **Mobile em escala LATAM** (Mercado Pago) | falhas críticas **−55%** · MTTR **−60%** · incidentes em produção **−40%** em 4 países |
| **FinOps e arquitetura** (Compass UOL) | custo de cloud **−20% a −35%** mantendo alta disponibilidade |

---

## Trajetória

**Hoje** — Engineering Staff, AI Engineering Lead, SRE e Cibersegurança na **Luby**: fábrica de
software com agentes de IA auditáveis, spec-driven development, guardrails por hook, MCP federando
ferramentas, RAG e LLMOps. Threat modeling para LLM: prompt injection, data leakage, exfiltração.

**Antes** — Creditas · Compass UOL · PicPay · PagoNxt (Santander) · Mercado Pago · Itaú Unibanco ·
Foursys · Soluti (Autoridade Certificadora).

**A origem importa.** Comecei em suporte N1/N2/N3 em telecom, passei por gestão de infraestrutura
on-premise, desenvolvimento backend, mobile Android e iOS, e entrei em cibersegurança numa
Autoridade Certificadora — onde confiança, criptografia e conformidade *são* o produto. Do hardware
ao código à governança, camada por camada. É de onde vem a leitura de ponta a ponta.

---

## Competência técnica

**Cibersegurança** — IAM e IGA (SailPoint, ciclo JML, RBAC, ABAC, SoD, PAM) · SSO com SAML, OAuth
2.0 e OIDC · AppSec e SSDLC com SAST, DAST e SCA como gate de merge · Zero Trust · threat modeling ·
TLS 1.3, mTLS, certificate pinning · ISO 27001, PCI-DSS, LGPD, NIST CSF, BACEN.

**IA aplicada** — Agentes com orquestração auditável · RAG · MCP · LLMOps e MLOps · prompt
engineering seguro e segurança de LLM · AWS Bedrock, OpenAI, Anthropic, LangChain · Python.

**Plataforma e confiabilidade** — SLI, SLO, incident response e postmortem · Datadog (APM, logs,
métricas) · AWS e Azure · Kubernetes, Docker · Terraform · GitHub Actions e SonarQube como quality
gate · deploy canary e blue-green com rollback.

**Arquitetura** — Clean Architecture, Hexagonal, DDD, SOLID · microsserviços e event-driven · Java e
Java EE, Kotlin, Spring, Python · mobile nativo Android e iOS.

**Engenharia de gestão** — times de 10 a 15 pessoas · OKR e métricas DORA reportadas a C-Level ·
1:1, PDI, trilha de carreira, recrutamento e code review.

---

## Formação e certificações

**Cambridge AI Leadership Programme** (University of Cambridge, 2026) · **Pós em Cibersegurança e
Governança de Dados** (PUC Minas) · **MBA em IA, Data Science e Big Data** (PUC-RS) ·
**Especialização em Gestão de Engenharia** (PUC Minas) · **Bacharelado em Sistemas de Informação**
(PUC Goiás).

AWS Certified AI Practitioner · Oracle Certified Java Programmer · ITIL v3 Foundation ·
EXIN ISO/IEC 27002 · COBIT.

---

## Como eu trabalho

Quatro coisas aparecem em tudo que eu construo, e são o que eu levo para um time:

**Baseline determinístico antes de qualquer IA.** Primeiro a solução explicável, depois a medição de
se o modelo agrega. Nessa ordem, sempre. Num incidente às 3h você precisa de uma conclusão com a
qual possa discutir, não de um score em que precise acreditar.

**Ground truth que permite medir.** Se não dá para calcular precisão e recall, é opinião. Meus
geradores de dado sintético plantam o problema de propósito, justamente para que a detecção seja
verificável.

**O número do README é defendido por CI.** Benchmark, cobertura e qualidade de LLM entram como gate
de regressão. Número que ninguém defende envelhece em silêncio.

**Segurança é propriedade da arquitetura.** Não etapa, não checklist, não gate no fim. Se ela só
aparece antes do deploy, já é tarde.

---

## Áreas de atuação

Cibersegurança · AppSec · IAM e IGA · Zero Trust · DevSecOps · SSDLC · threat modeling ·
SAST, DAST e SCA · Semgrep · SonarQube · CodeQL · SailPoint · OAuth 2.0 · OIDC · SAML · PAM ·
RBAC e ABAC · segregação de funções · PCI-DSS · ISO 27001 · LGPD · NIST CSF · BACEN · COBIT · ITIL

IA generativa · LLM · RAG · MCP · agentes de IA · LLMOps e MLOps · guardrails · prompt injection ·
AWS Bedrock · OpenAI · Anthropic · LangChain · n8n · spec-driven development

SRE e confiabilidade · SLI e SLO · incident response · postmortem · MTTR · métricas DORA ·
observabilidade · Datadog · AWS · Azure · Kubernetes · Docker · Terraform · GitHub Actions

Arquitetura de software · Clean Architecture · Hexagonal · DDD · SOLID · microsserviços ·
event-driven · Java · Java EE · Kotlin · Spring · Python · Android · iOS

Engineering management · liderança técnica · tech lead · staff e principal engineer ·
gestão de time · OKR · fintech · banking · pagamentos · payments

---

## Contato

Brasil (SP/GO) · [julianovincedecampos.com](https://julianovincedecampos.com/) ·
[LinkedIn](https://www.linkedin.com/in/julianovincecampos/)

<sub>✡︎ &nbsp;בְּעֶזְרַת הַשֵּׁם &nbsp;·&nbsp; Perfil anterior: <a href="https://github.com/JulianoVince">@JulianoVince</a></sub>
