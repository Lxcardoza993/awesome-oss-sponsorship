<div align="center">

# awesome-oss-sponsorship

**Um guia prático para monetizar projetos de código aberto — patrocinadores, redes de anúncios, programas de afiliados e a abordagem que realmente fecha negócio.**

Plataformas selecionadas · referências de preços validadas · modelos prontos para copiar e colar · estudos de caso reais · plano de 7 dias para começar do zero.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Made for maintainers](https://img.shields.io/badge/for-100%2B%20%E2%86%92%2010k%2B%20star%20repos-blueviolet)](#para-quem-e-isso)

</div>

🌐 **Idiomas:** [English](README.md) · [中文](README.zh-CN.md) · [Español](README.es.md) · [日本語](README.ja.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português (Brasil)](README.pt-BR.md)

> **O patrocínio é um canal de vendas, não uma recompensa baseada na contagem de estrelas.** As estrelas são um
> indicador de popularidade — os verdadeiros fatores que determinam o preço são **visitantes únicos mensais**
> (tráfego no GitHub), **downloads do pacote** (npm / PyPI / Docker Hub) e a **afinidade entre o público e o
> patrocinador**. Este repositório é o guia prático para gerir esse canal de vendas de forma profissional:
> quais plataformas, quais espaços, qual preço, a quem contatar e o que enviar.

Tudo aqui pode ser **copiado e colado** e baseia-se em **fontes públicas verificadas** (documentos
oficiais, páginas no OpenCollective, blogs de mantenedores, páginas de preços de redes de anúncios).
Todos os preços são **apenas estimativas/referências** — nunca uma cotação, nunca uma promessa.
Veja o [responsabilidade](#responsabilidade).

---

## Agradecimentos

- **[Telegram OpenClaw 中文社区](https://t.me/OpenClaw_Group)** — comunidade do OpenClaw em chinês no Telegram, para suporte e discussões.
- **[Linux.do](https://linux.do)** — comunidade de desenvolvedores e tecnologia em chinês (baseada em Discourse), cujos membros e comentários moldaram as orientações sobre a distribuição na China presentes neste guia.

---

## Table of contents

- [Para quem é isso?](#para-quem-e-isso)
- [Início rápido (5 minutos)](#inicio-rapido-5-minutos)
- [Se você tem apenas 1.000 estrelas](#se-você-tem-apenas-1000-estrelas)
- [Comparação entre plataformas](#comparação-entre-plataformas)
- [Referência de preços (estimativa)](#referência-de-preços-estimativa)
- [Programas de afiliados que realmente pagam](#programas-de-afiliados-que-realmente-pagam)
- [Como encontrar patrocinadores](#como-encontrar-patrocinadores)
- [Plano de início do zero em 7 dias](#plano-de-início-do-zero-em-7-dias)
- [Modelos e ferramentas](#modelos-e-ferramentas)
- [Documentação](#documentação)
- [Referências de estudos de caso reais](#referências-de-estudos-de-caso-reais)
- [Contribuição](#Contribuiçao)
- [Histórico de estrelas](#historico-de-estrelas)
- [Responsabilidade](#responsabilidade)

---

## Para quem é isso?

| Onde você está | Comece aqui |
|---------|-----------|
| **100-star maintainer** (early CLI/SDK) | GitHub Sponsors (0% fee) + `.github/FUNDING.yml`. Focus on momentum, not money. → [100-star example](examples/100-stars-repo.md) |
| **1,000-star maintainer** (the sweet spot) | GitHub Sponsors + Open Collective + a rate card. Run the first-50-DMs plan. → [1000-star playbook](docs/1000-stars-playbook.md) · [example](examples/1000-stars-repo.md) |
| **10,000-star maintainer** | Tiered program + standalone sponsor page + EthicalAds on docs. → [10000-star example](examples/10000-stars-repo.md) |
| **Indie / solo dev** | GitHub Sponsors (recurring) + Buy Me a Coffee (one-off tips). Skip the fiscal host. |
| **Devtool / CLI / SDK maintainer** | GitHub Sponsors + thanks.dev (dependency-tree inbound) + affiliate hybrid. |
| **Newsletter-running mainter** | GitHub Sponsors + Paved (newsletter ads — highest $/impression). |
| **Maintainer shipping a paid SaaS/AI product** | Polar (Merchant-of-Record) — **not** for sponsorship. |

---

## Início rápido (5 minutos)

1. **Escolha uma plataforma.** Projeto individual → [GitHub Sponsors](docs/github-sponsors.md) (0% de taxa pessoal). Múltiplos colaboradores/fornecedores → [Open Collective](docs/open-collective.md) (hospedagem fiscal + registro público de transações).
2. **Adicione o arquivo `.github/FUNDING.yml`.** Isso configura o botão "Sponsor" (Patrocinar). Copie o [modelo comentado](templates/funding-yml-example.md) (12 chaves atuais; `otechie`, `givebutter` e `lfx_crowdfunding` **não** são suportados).
3. **Defina os níveis de patrocínio.** GitHub Sponsors: até 10 níveis de pagamento único e 10 mensais, com limite de US$ 12.000/mês; **o preço é imutável após a publicação** (é preciso desativar e recriar para alterar). Baseie-se em escalas reais — Vite (`$5/$15/$50/$150/$500`), Astro (`$10/$100/$200/$250/$1.000/$10.000`) — mas rotule os seus como **apenas estimativa/referência**.
4. **Liste seu inventário.** Você vende *exposição*, não estrelas. Taxonomia de espaços em [`data/sponsor-types.yml`](data/sponsor-types.yml): banner no topo do README, grade de logotipos no rodapé do README (o padrão dominante — SVG dinâmico, nunca edite o README manualmente), anúncio no site de documentação, nota de lançamento, newsletter.
5. **Comece a prospecção.** Crie uma página única com sua [tabela de preços](templates/rate-card.md) baseada no **seu** tráfego e, em seguida, envie o modelo de [e-mail de abordagem inicial](templates/cold-email.md) para empresas na sua árvore de dependências ou nas suas principais fontes de referência (*Popular Referrers*). Defina preços na faixa **mais baixa** até fechar 3 contratos.

> O roteiro de 5 minutos está detalhado em [docs/getting-started.md](docs/getting-started.md).

---

## Se você tem apenas 1.000 estrelas

1.000 estrelas são um ponto interessante: usuários reais, downloads reais e conversas reais com equipes de compras — mas o projeto ainda está próximo o suficiente da operação para que você consiga vender diretamente. A estratégia completa está no [playbook de 1.000 estrelas](docs/1000-stars-playbook.md); os pontos essenciais:

- **É comercialmente valioso** — mas somente se você vender. [komorebi (~10 mil estrelas) gerou apenas ~US$ 155/mês](https://lgug2z.com/articles/github-sponsorship-breakdown-for-2024/) sem vendas; [Caleb Porzio chegou a ~US$ 112.680/ano](https://calebporzio.com/i-just-hit-dollar-100000yr-on-github-sponsors-heres-how-i-did-it) vendendo ativamente em uma base maior.
- **Defina preços na faixa mais baixa** da [tabela de estimativas](#referência-de-preços-estimativa); aumente os preços após fechar 3 contratos.
- **Mantenha um pipeline com 50 prospects**, avaliados usando o [Sponsor Fit Score](tools/sponsor-fit-score.md), em uma cadência de 3 contatos antes do encerramento — veja o [plano dos primeiros 50 DMs](examples/1000-stars-repo.md#5-plano-dos-primeiros-50-dms).
- **Ofereça um teste no primeiro mês** com 50% de desconto (ou gratuitamente) para reduzir o risco para um patrocinador fundador.
- **Não prejudique o repositório.** Uma política de avaliação de patrocinadores + divulgação clara de afiliados + nenhuma prática de spam protege a reputação que torna o projeto patrocinável.

---

## Comparação entre plataformas

Status verificados em 29/06/2026 com base nos sites oficiais. As taxas são **apenas referências**.

| Plataforma | Tipo | Status | Taxa (apenas referência) | Melhor para |
|---|---|---|---|---|
| [GitHub Sponsors](docs/github-sponsors.md) | patrocínio | ✅ ativa | 0% pessoa física / ≤6% organização | mantenedores individuais; botão nativo do GitHub. ⚠ A China continental **não** é suportada |
| [Open Collective](docs/open-collective.md) | hospedagem fiscal | ✅ ativa | planos de US$ 0/60/320; ou 5% | transparência financeira; múltiplos colaboradores |
| Open Source Collective | hospedagem fiscal | ✅ ativa | via OC | estrutura americana 501(c)(6), com possibilidade de dedução fiscal |
| [Polar](docs/polar.md) | cobrança MoR | 🔄 mudou de foco | 5% + 50¢ → 3,40% + 30¢ | cobrança e impostos para SaaS/IA pagos. **Não é para patrocínio** |
| Buy Me a Coffee | doações | ✅ ativa | 5% + processamento Stripe | contribuições únicas |
| Ko-fi | doações | ⚠ não verificado | 0% em doações; Gold ~US$ 12/mês (verificar) | contribuições diretas via PayPal/Stripe |
| Patreon | assinatura | ✅ ativa | 10% | assinaturas recorrentes |
| thanks.dev | doações | ✅ ativa | 5% | financiar automaticamente sua árvore de dependências |
| StackAid | doações | ✅ ativa | assinaturas a partir de US$ 15/mês | financiar dependências diretas e transitivas |
| Tidelift | assinatura | ❌ adquirida | — | histórico; adquirida pela Sonar em dezembro de 2024 |
| IssueHunt | recompensas | ⚠ desatualizada | n/d | recompensas por issues — use **oss.issuehunt.io**, verificando se continua ativa |
| Algora | recrutamento | 🔄 mudou de foco | n/d | contratação em OSS + painel de recompensas |
| [EthicalAds](docs/ad-networks.md) | anúncios (CPM) | ✅ ativa | 70% da receita, ~US$ 2,50 CPM               | sites de documentação para desenvolvedores (50 mil+ pageviews) |
| Carbon Ads | anúncios (CPC) | ✅ ativa | vendas assistidas | sites de desenvolvimento selecionados (mínimo de US$ 5–10 mil para anunciantes) |
| BuySellAds | anúncios (diversos) | ✅ ativa | gerenciada | e-mail/nativo/patrocinado/podcast |
| Passionfroot | anúncios/marketplace  | 🔄 mudou de foco → Zest | 2% / 15% | acordos de marca para newsletters |
| Paved | anúncios (newsletter) | ✅ ativa | valor fixo + PPC | newsletters (25 mil assinantes / 1 milhão de pageviews) |

Banco de dados estruturado completo: [`data/platforms.yml`](data/platforms.yml).

---

## Referência de preços (estimativa)

> **Apenas estimativa/referência.** Não existe um mercado público padronizado que relacione
> US$/mês diretamente à quantidade de estrelas. A quantidade de estrelas é um indicador de
> popularidade, não uma métrica de preço. Recalcule os valores com base no **seu** tráfego:
> anúncio em documentação ≈ `pageviews_mensais / 1000 × ~US$ 2,50` (CPM de publisher da
> EthicalAds); newsletter ≈ `assinantes × taxa_de_abertura × CTR × CPC_alvo`, usando como
> referência os [US$ 3.590 por edição da JavaScript Weekly com 180 mil assinantes]
> (https://cooperpress.com/files/cooperpress-media-kit-q2-2024.pdf). Sem dados de tráfego/conversão,
> defina preços na faixa **mais baixa**; aumente após fechar 3 contratos.

Valores mensais em USD por faixa de estrelas × espaço (estimativa):

| Estrelas | Banner no topo do README | Logo no rodapé do README | Texto no rodapé do README | Anúncio no site de docs | Nota de lançamento | Newsletter / edição |
|------:|---:|---:|---:|---:|---:|---:|
| 100 | US$100–300 | US$50–150 | US$20–75 | US$10–40 | US$50–150 | US$30–100 |
| 500 | US$200–500 | US$100–300 | US$50–150 | US$25–80 | US$100–300 | US$100–250 |
| 1,000 | US$400–1,000 | US$200–600 | US$100–300 | US$50–200 | US$200–600 | US$200–500 |
| 5,000 | US$1,000–3,000 | US$500–1,500 | US$250–750 | US$150–600 | US$500–1,500 | US$500–1,500 |
| 10,000 | US$2,000–6,000 | US$1,000–3,000 | US$500–1,500 | US$300–1,500 | US$1,000–3,000 | US$1,000–2,500 |
| 50,000 | US$5,000–15,000 | US$3,000–10,000 | US$1,500–5,000 | US$1,000–5,000 | US$2,500–8,000 | US$2,500–7,000 |

Modificadores do modelo de negócio (estimativa): exibição única por 12 meses ≈ 8–10× o valor mensal (15–20% de desconto); contrato anual ≈ 10–12× o valor mensal (15–20% de desconto); afiliado puro = US$ 0 fixos + 10–30% recorrentes; **modelo híbrido fixo + afiliado** = retainer menor + comissão.
A tabela completa + faixa doméstica em RMB está em [`data/pricing-benchmarks.yml`](data/pricing-benchmarks.yml); o modelo de tabela de preços pronto para copiar está em [`templates/rate-card.md`](templates/rate-card.md).

---

## Programas de afiliados que realmente pagam

A maioria das empresas de ferramentas para desenvolvedores **não possui** um programa público de afiliados (OpenAI, Anthropic, GitHub, Supabase, Cloudflare e AWS — todos confirmados como ausentes). Os programas que possuem, verificados em 29/06/2026:

| Programa | Comissão (ref.) | Cookie | Pagamento | Adequação |
|---|---|---|---|---|
| [Railway](https://railway.com/affiliate-program) | 15% recorrente, 12 meses | n/d | GitHub Sponsors / BMC | ★★★ receita via Sponsors |
| [Neon](https://neon.com/programs/open-source) | US$ 20 em dinheiro / indicação | n/d | GitHub Sponsors | ★★★ programa para OSS |
| [ElevenLabs](https://elevenlabs.io/affiliates) | 22% recorrente, 12 meses | n/d | PartnerStack, US$ 5 | ★★★ voz por IA |
| [Apify](https://apify.com/partners/affiliate) | 20%→30%, limite de US$ 2.500/cliente | 45 dias | PayPal/banco, US$ 100 | ★★★ scraping |
| [Bright Data](https://brightdata.com/affiliate) | 50% até US$ 2.500 + 15% de segundo nível | 90 dias | PartnerStack | ★★★ proxies |
| [ScrapingBee](https://www.scrapingbee.com/affiliates/) | 25% recorrente vitalício | n/d | PayPal, US$ 50 | ★★★ scraping |
| [Browserless](https://www.browserless.io/affiliate) | 20–30% por níveis, 12 meses | 90 dias | PayPal/banco, US$ 50 | ★★★ navegador headless |
| [n8n](https://n8n.io/affiliates/) | 30% recorrente, 12 meses (Cloud) | n/d | PayPal, €100 | ★★★ automação |
| [Make](https://www.make.com/en/affiliate) | 35% recorrente, 12 meses | 30 dias | Wise, US$ 100 | ★★ automação |
| [Raycast](https://www.raycast.com/blog/affiliate-program) | 30% recorrente (Pro) | n/d | Wise, £50 | ★★ macOS |
| [Pluralsight](https://www.pluralsight.com/affiliate) | US$ 1/teste + 30%/10%/5% único | 7 dias  | CJ | ★★ aprendizado de desenvolvimento |
| [DigitalOcean](https://www.digitalocean.com/affiliates) | 10% recorrente, 12 meses | n/d | Awin/CJ | ★★ hospedagem |
| [Netlify](https://www.netlify.com/partners/) | 20% recorrente, 12–24 meses | n/d | PartnerStack | ★★ Jamstack |
| [Vercel / v0](https://partners.dub.co/v0) | 30% recorrente, 6 meses + US$ 5/lead | n/d | Dub | ★★ frontend |

Encerrados/inativos: Hetzner (encerrado em 15/06/2026), Notion (fechado para novos afiliados), ShareASale (encerrado → Awin), Heroku (encerrado).
Redes para entrar como publisher: **PartnerStack** (alta concentração de ferramentas para desenvolvedores, mínimo de US$ 5) e **Impact** (mais ampla, mínimo de US$ 10).
Banco de dados completo + lista de programas nos quais **não foi encontrado** um programa de afiliados estão em [`data/affiliate-programs.yml`](data/affiliate-programs.yml) e [`docs/affiliate-programs.md`](docs/affiliate-programs.md).

---

## Como encontrar patrocinadores

Não faça prospecção aleatória. Monte uma lista de 50 prospects e atribua uma pontuação a cada um. Fontes prioritárias (método completo em [docs/outreach.md](docs/outreach.md)):

1. **Empresas na sua árvore de dependências** — quem desenvolve software que *usa* seu projeto? As equipes de DevRel e Growth dessas empresas tendem a ter maior aderência.
2. **Stargazers/forkers que são empresas** — organizações do GitHub que deram estrela ou fizeram fork; encontre o contato de DevRel, fundador ou Growth pelo LinkedIn/X.
3. **Fornecedores adjacentes** — produtos que são utilizados *junto com* o seu (hospedagem, ORM, observabilidade, CI).
4. **Patrocinadores em espécie** — fornecedores de hospedagem/CI/secrets/monitoramento que oferecem créditos em troca de exposição de marca (padrão utilizado pelo Homebrew: MacStadium, 1Password).
5. **Usuários avançados que abriram issues** — peça uma apresentação ao empregador deles.

Avalie cada prospect usando o [Sponsor Fit Score](tools/sponsor-fit-score.md) (0–100). Priorize **61–100** e descarte **0–30**. Envie os modelos de [e-mail](templates/cold-email.md) / [DM](templates/dm-template.md) em uma cadência de 3 contatos antes do encerramento. Registre tudo no [checklist de prospecção](tools/outreach-checklist.md).

---

## Plano de início do zero em 7 dias

Uma semana para sair de "nenhum programa de patrocínio" para "primeiras propostas enviadas + repositório lançado". Cada dia possui um checklist em [docs/launch-plan.md](docs/launch-plan.md) e [docs/1000-stars-playbook.md](docs/1000-stars-playbook.md).

| Dia | Faça | Resultado |
|---|---|---|
| **1** | Escolha a plataforma; adicione `.github/FUNDING.yml`; configure 3–5 níveis na faixa mais baixa | Botão Sponsor ativo + estrutura de níveis |
| **2** | Liste os espaços disponíveis; crie uma [tabela de preços](templates/rate-card.md) de uma página | Tabela de preços (referência interna) |
| **3** | Colete GitHub Traffic + downloads do npm/PyPI/Docker; crie um [sponsor kit](templates/sponsor-kit.md) de uma página | Kit com ressalva sobre tráfego autodeclarado |
| **4** | Monte uma lista de 50 prospects (árvore de dependências, organizações que deram estrela, fornecedores adjacentes); avalie usando o [Sponsor Fit Score](tools/sponsor-fit-score.md) | Lista de prospects pontuada |
| **5** | Envie a primeira rodada (10 prospects) usando [e-mail](templates/cold-email.md) / [DM](templates/dm-template.md) | 10 contatos enviados e registrados |
| **6** | Envie a segunda rodada (10); prepare posts de lançamento (HN / Reddit / V2EX / X) | Materiais de lançamento prontos |
| **7** | Faça o lançamento + publique uma página independente de patrocinadores; registre tudo no [checklist de prospecção](tools/outreach-checklist.md) | Repositório lançado, pipeline ativo |

Após o dia 7: mantenha o pipeline contínuo de 50 prospects, execute cadências de 3 contatos e mantenha atualizações para crescimento orgânico de estrelas (consulte [docs/launch-plan.md](docs/launch-plan.md), seção 12).

---

## Modelos e ferramentas

Copie, cole, preencha os `[colchetes]` e publique.

| Arquivo | Descrição |
|---|---|
| [templates/funding-yml-example.md](templates/funding-yml-example.md) | `.github/FUNDING.yml` comentado — todas as 12 chaves, 3 exemplos completos |
| [templates/rate-card.md](templates/rate-card.md) | Tabela de preços de uma página (USD + RMB, matriz de estrelas × espaço) |
| [templates/cold-email.md](templates/cold-email.md) | E-mail de prospecção + follow-ups + respostas sim/não (EN + 中文) |
| [templates/dm-template.md](templates/dm-template.md) | DMs para LinkedIn / X / Discord / 微信 / V2EX-掘金 |
| [templates/sponsor-kit.md](templates/sponsor-kit.md) | Kit completo para patrocinadores (preenchível + exemplo) |
| [templates/media-kit.md](templates/media-kit.md) | Media kit no estilo TLDR (todos os componentes + exemplo) |
| [templates/readme-sponsor-block.md](templates/readme-sponsor-block.md) | Trechos de patrocínio para topo/rodapé/logo/texto/afiliados no README |
| [templates/affiliate-tracker.csv](templates/affiliate-tracker.csv) | CSV para acompanhar contratos de afiliados |
| [tools/sponsor-fit-score.md](tools/sponsor-fit-score.md) | Modelo de pontuação de prospects de 0–100 + exemplo |
| [tools/outreach-checklist.md](tools/outreach-checklist.md) | Rastreador do pipeline de 50 prospects (Markdown + CSV) |

---

## Documentação

| Documento | Conteúdo |
|---|---|
| [docs/getting-started.md](docs/getting-started.md) | Orientação + roteiro de 5 minutos + mapa de links |
| [docs/github-sponsors.md](docs/github-sponsors.md) | Elegibilidade, regiões (observação sobre a China), configuração, níveis, taxas e exibição no README |
| [docs/open-collective.md](docs/open-collective.md)| Hospedagem fiscal, OSC 501(c)(6), registro público, planos/taxas |
| [docs/polar.md](docs/polar.md)| Mudança de foco para cobrança de IA / MoR — quando utilizar e quando não utilizar |
| [docs/ad-networks.md](docs/ad-networks.md)| EthicalAds, Carbon, BuySellAds, Passionfroot, Paved |
| [docs/affiliate-programs.md](docs/affiliate-programs.md) | Programas de afiliados verificados + lista de programas não encontrados + redes |
| [docs/pricing.md](docs/pricing.md) | Como definir preços (tráfego, não estrelas) + tabela de estimativas |
| [docs/sponsor-kit.md](docs/sponsor-kit.md) | Como criar um sponsor kit (guia) + dados do GitHub Traffic |
| [docs/readme-monetization.md](docs/readme-monetization.md) | Monetização do README + espaços de exposição |
| [docs/outreach.md](docs/outreach.md) | Como encontrar patrocinadores de forma proativa |
| [docs/1000-stars-playbook.md](docs/1000-stars-playbook.md) | Playbook de 10 seções para projetos com 1 mil estrelas |
| [docs/launch-plan.md](docs/launch-plan.md) | Distribuição inicial (HN/Reddit/PH/V2EX/掘金/X) |
| [docs/case-studies.md](docs/case-studies.md) | Números divulgados e verificados (Astro/Vue/Vite/Tailwind/Sentry/…) |
| [docs/faq.md](docs/faq.md) | Mais de 15 perguntas e respostas |

Dados (fonte de verdade): [`data/platforms.yml`](data/platforms.yml) · [`data/pricing-benchmarks.yml`](data/pricing-benchmarks.yml) · [`data/sponsor-types.yml`](data/sponsor-types.yml) · [`data/affiliate-programs.yml`](data/affiliate-programs.yml).

🌐 **Idiomas:** [English](README.md) · [中文](README.zh-CN.md) · [Español](README.es.md) · [日本語](README.ja.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português (Brasil)](README.pt-BR.md)

---

## Referências de estudos de caso reais

Números divulgados publicamente (citados em [docs/case-studies.md](docs/case-studies.md)). Estimativas estão identificadas.

| Projeto | O que foi divulgado (fonte) | Conclusão |
|---|---|---|
| [Astro](https://opencollective.com/astrodotbuild) | US$ 836 mil acumulados no OC; níveis de até US$ 10.000/mês | Estrutura clara de níveis + página de patrocinadores + hospedagem fiscal |
| [Vue.js](https://opencollective.com/vuejs) | US$ 852 mil acumulados no OC | Página própria de patrocinadores + BACKERS. |
| [Vite](https://opencollective.com/vite) | US$ 162 mil acumulados no OC; Bronze US$ 50 → Gold US$ 500 | Uma estrutura de níveis mais simples também é utilizada |
| [Homebrew](https://opencollective.com/homebrew) | US$ 486 mil acumulados no OC | Combinação de contribuições em espécie (MacStadium/1Password) + dinheiro |
| [Tailwind CSS](https://tailwindcss.com/sponsor) | Parceiro US$ 5.000/mês (estimativa de ~US$ 200 mil/mês de ~70 empresas) | Níveis de patrocínio podem ser utilizados em escala; atividade comercial ≠ patrocínio |
| [Sentry](https://blog.sentry.io) | US$ 155 mil → US$ 750 mil/ano destinados a OSS; compromisso de US$ 2.000/engenheiro/ano | Exemplo de orçamento de um patrocinador |
| [Caleb Porzio](https://calebporzio.com/i-just-hit-dollar-100000yr-on-github-sponsors-heres-how-i-did-it) | US$ 112.680/ano no GitHub Sponsors | Venda ativa em uma base de usuários |
| [komorebi (~10k★)](https://lgug2z.com/articles/github-sponsorship-breakdown-for-2024/) | US$ 1.861/ano (~US$ 155/mês) | **10 mil estrelas não significam patrocínio sem vendas** |

---

## Contribuição

Correções e novas plataformas/programas são bem-vindos — **sempre acompanhados de uma fonte oficial citada**. Consulte [CONTRIBUTING.md](CONTRIBUTING.md). A única regra: **não publique fatos não verificados**; marque qualquer informação incerta como `unverified` em vez de tentar adivinhar.

---

## Histórico de estrelas

<a href="https://star-history.com/#irmacardozo993-lgtm/awesome-oss-sponsorship&Date">
  <img src="https://api.star-history.com/svg?repos=irmacardozo993-lgtm/awesome-oss-sponsorship&type=Date" alt="Histórico de estrelas">
</a>

---

## Responsabilidade

Todos os preços, taxas, percentuais de comissão e valores de receita deste repositório
são **apenas estimativas/referências**. Eles não são cotações, garantias nem aconselhamento
financeiro, jurídico ou tributário. Os preços reais dependem do setor, tráfego, qualidade
dos usuários, taxa de conversão, localização geográfica do público e orçamento do patrocinador.
**Verifique os termos atuais de cada plataforma antes de tomar decisões com base nessas
informações.** Os status das plataformas foram verificados em 29/06/2026 e podem mudar com
frequência. Este projeto não promete nenhum nível de ganhos e não é um esquema de
"enriquecimento rápido" — é um guia prático para mantenedores que desejam administrar
patrocínios de forma profissional.

Licença: [CC-BY-4.0](LICENSE) para o conteúdo; MIT para os trechos de código incorporados. Consulte [LICENSE](LICENSE).
