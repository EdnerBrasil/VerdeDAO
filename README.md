# VerdeDAO — Projeto (Documentação)

Projeto conceitual de uma DAO fictícia criado para o desafio da DIO.  
O objetivo é materializar a **ideia** da DAO (nome, missão, governança, comunidade, tesouraria e entregas de valor) — sem precisar criar Discord, token, multisig etc. na prática.

---

## Sumário
1. [Identidade e Propósito](#1-identidade-e-propósito)
2. [Entrega de Valor](#2-entrega-de-valor)
3. [Design Organizacional e Governança](#3-design-organizacional-e-governança)
4. [Gestão de Comunidade e Contribuição](#4-gestão-de-comunidade-e-contribuição)
5. [Tesouraria e Financiamento](#5-tesouraria-e-financiamento)
6. [Arquitetura e Implementação (Visão Conceitual)](#6-arquitetura-e-implementação-visão-conceitual)
7. [Roadmap Inicial (90 dias)](#7-roadmap-inicial-90-dias)
8. [Métricas de Sucesso](#8-métricas-de-sucesso)
9. [Como Contribuir](#9-como-contribuir)
10. [Templates](#10-templates)
11. [Licença](#11-licença)

---

## 1. Identidade e Propósito
Conforme definido em "Arquitetura e Implementação", este é o passo zero.

- **Nome da DAO:** VerdeDAO  
- **Missão (North Star):** Combater as ilhas de calor urbanas e a insegurança alimentar através da descentralização do plantio e manutenção de ecossistemas regenerativos em periferias.  
- **Entrega de Valor (Social/Public Goods):** A VerdeDAO entrega **Protocolos de Regeneração Urbano-Ambientais**, financiando mudas, ferramentas e educação para comunidades locais, transformando terrenos baldios em **ativos ambientais auditáveis pela blockchain**.

### Princípios
- **Descentralização com método:** autonomia local com padrões mínimos.
- **Evidência auditável:** sem evidência, sem pagamento (e sem “greenwashing”).
- **Co-benefícios:** redução de temperatura local + alimento + biodiversidade + vínculo comunitário.
- **Transparência radical:** orçamento, resultados e falhas registrados e aprendidos.

---

## 2. Entrega de Valor
**Categoria:** Social / Public Goods

A VerdeDAO entrega valor por meio de três linhas principais:

### 2.1 Protocolos de Regeneração Urbano-Ambientais (Padrões Abertos)
Conjunto aberto e versionado de:
- guias de seleção e preparo de áreas (terrenos baldios, praças, corredores);
- protocolos de plantio (espécies, espaçamento, consórcio, cobertura do solo);
- protocolos de manutenção (irrigação, compostagem, poda, manejo agroecológico);
- protocolos de segurança e governança local (responsabilidades, permissões, gestão de conflitos);
- checklist de evidências e auditoria (o que provar, como provar, quando atualizar).

### 2.2 Programa de Bounties e Microgrants
- **Bounties:** tarefas objetivas (materiais, mapeamentos, revisões, documentação, mutirões com evidências).
- **Microgrants:** apoio financeiro e material para implantação e manutenção de núcleos regenerativos comunitários.

### 2.3 Ativos Ambientais Auditáveis (Conceito)
Cada área regenerada gera um “ativo” com:
- **ID do Núcleo Verde** (identificador),
- **metadados** (local aproximado, área, tipo de intervenção),
- **evidências** (fotos, logs de manutenção, checklists),
- **indicadores** (sobrevivência de mudas, sombra/área verde, produção alimentar),
- **histórico** (versões e alterações).

> Observação: este projeto é conceitual. “Auditável pela blockchain” significa que o **registro** das evidências e do histórico é verificável, com integridade e transparência.

---

## 3. Design Organizacional e Governança

### 3.1 Estrutura de Grupos de Trabalho (Pods/Workstreams)
Para evitar “desorganização descentralizada”, a VerdeDAO opera por Pods com escopo claro:

1. **Pod Protocolos & Padrões**
   - mantém e evolui os Protocolos de Regeneração (qualidade, versões, revisões).

2. **Pod Implantação & Manutenção**
   - desenha playbooks operacionais (mutirões, rotinas, calendário) e apoia núcleos locais.

3. **Pod Educação & Comunidade**
   - onboarding, trilhas de aprendizagem, facilitação de governança local e comunicação.

4. **Pod Tesouraria & Transparência**
   - estrutura de orçamento, pagamentos, trilha de auditoria e relatórios.

5. **Pod Dados & Auditoria**
   - define o padrão de evidências, validações mínimas, métricas e auditorias amostrais.

**Regras mínimas por Pod:**
- backlog público (issues),
- metas trimestrais,
- facilitação rotativa,
- relatório mensal curto (entregas, gastos, próximos passos, lições).

### 3.2 Mecanismo de Votação (Conceitual)
- **Sinalização (Off-chain):** votação para medir o sentimento e priorização de iniciativas.
- **Execução (On-chain):** tesouraria em multiassinatura para aprovar e executar repasses, condicionados à aprovação e às evidências.

### 3.3 Ciclo de Vida de uma Proposta
1. **Discussão:** proposta rascunho (problema → solução → custo → riscos → evidências).
2. **Temperature Check:** votação rápida (prioridade/viabilidade).
3. **Proposta formal:** escopo fechado, entregáveis e critérios de aceite.
4. **Execução:** repasse condicionado (por marcos e evidências).
5. **Prestação de contas:** evidências + relatório e atualização do “ativo ambiental”.

---

## 4. Gestão de Comunidade e Contribuição

### 4.1 Ferramentas de Comunicação
- **Discord:** governança interna, canais por Pod e suporte ao onboarding.
- **X (Twitter):** divulgação, transparência pública e chamadas de bounties/microgrants.
- **GitHub:** repositório oficial (issues, PRs, releases, histórico).

### 4.2 Jornada do Colaborador (do visitante ao guardião do núcleo)
1. **Visitante**
   - lê o Manifesto + “Como contribuir” + visão dos Protocolos.
2. **Contribuidor inicial**
   - executa bounties simples: revisão de texto, desenho de checklist, tradução, formatação.
3. **Agente de Campo (Núcleo Local)**
   - participa de implantação/manutenção e registra evidências conforme protocolo.
4. **Guardião do Núcleo**
   - coordena rotina local (irrigação, compostagem, mutirões), reporta indicadores e conduz governança local.
5. **Core contributor**
   - facilita ritos, revisa propostas e lidera evoluções dos Protocolos.

### 4.3 Compensação e Incentivos
Modelo híbrido (recomendado):
- **Bounties fixas:** valores definidos por tarefa/entregável.
- **Microgrants por marcos:** repasse em etapas (implantação, 30/60/90 dias) condicionado a evidências.
- **Reconhecimento por impacto:** ciclos mensais de distribuição por contribuição/impacto (peer-based).

> Política de pagamento: **sem evidência, sem pagamento** (links para PR/Doc/Relatório + checklist de aceite preenchido).

---

## 5. Tesouraria e Financiamento

### 5.1 Carteira (Conceitual)
- **Multiassinatura:** reduz risco de chave única e melhora governança dos repasses.

### 5.2 Gestão e Transparência
- Orçamento por categorias:
  - mudas e insumos,
  - ferramentas e infraestrutura leve (ex.: irrigação simples),
  - educação e materiais,
  - operação e comunicação,
  - auditoria e dados,
  - contingência.
- Prestação de contas com relatórios periódicos e evidências anexadas.

### 5.3 Fontes de Financiamento (Opções)
1. Doações recorrentes e campanhas
2. Grants externos (impacto socioambiental / bens públicos)
3. Parcerias locais (organizações, coletivos, comércio)
4. Serviços complementares (sem capturar o commons)
   - oficinas, consultorias de implantação, capacitação, replicação do protocolo

---

## 6. Arquitetura e Implementação (Visão Conceitual)

### 6.1 Fluxo de Governança → Execução → Evidências
```mermaid
flowchart LR
  A[Comunidade e Nucleos Locais] --> B[Proposta: Nucleo Verde ou Bounty]
  B --> C[Votacao offchain]
  C -->|Aprovada| D[Tesouraria multisig]
  D --> E[Repasse por marcos]
  E --> F[Implantacao e manutencao]
  F --> G[Evidencias e indicadores]
  G --> H[Registro auditavel]
  H --> I[Relatorio publico e metricas]
  C -->|Reprovada| J[Revisar proposta]
  J --> B
