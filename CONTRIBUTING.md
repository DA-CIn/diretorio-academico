# 🛠️ CONTRIBUTING.md — Guia de Contribuição do DA-CIn UFPE

> *"Este repositório é uma assembleia permanente. Cada Issue é um microfone aberto. Cada Pull Request é uma proposta de lei."*

Este documento define as regras que regem toda a participação nos repositórios da organização `@da-cin-ufpe`. Leia antes de abrir sua primeira Issue ou PR.

---

## 1. 🧭 Filosofia: Open Source como Política Estudantil

Diretórios Académicos historicamente morrem da mesma doença: **memória institucional zero**. Decisões tomadas em reuniões fechadas, sem registo. Gestões que chegam sem saber o que a anterior prometeu. Alunos sem acesso às atas. Transparência que existe no papel e não na prática.

Este repositório existe para matar esse problema na raiz. Adotamos a filosofia dos projetos de software livre e aplicamo-la integralmente à política estudantil:

- **Tudo é público e versionado:** Nenhuma decisão relevante existe fora do Git. Se não tem commit, não aconteceu.
- **Toda mudança tem autoria:** O histórico de contribuições é imutável. Quem propôs, quem aprovou, quem bloqueou — tudo fica registado para a posteridade.
- **A comunidade é a revisora:** Não existe decisão de gabinete. Propostas que afetam os estudantes são debatidas pelos estudantes antes de virar realidade.
- **O processo é a garantia:** Não confiamos em pessoas — confiamos no processo. Mesmo que a diretoria mude, as regras permanecem.

---

## 2. 🗣️ Regras para Issues — O Debate

### 2.1. Como Abrir uma Issue
**O uso de templates é obrigatório.** Escolha o template adequado: `Denúncia / Problema`, `Proposta de Melhoria`, `Alteração de Documento Oficial` ou `Pauta para Assembleia`. Issues mal-formatadas serão fechadas.

### 2.2. Ciclo de Vida e Votação (Automatizada)
1. **Debate Aberto:** Começa no momento da abertura. Todos podem comentar e sugerir ajustes.
2. **Triagem:** A diretoria tem 5 dias úteis para validar as labels e o escopo.
3. **Votação:** Quando o debate amadurece, a diretoria aplica a label `em-votação`.
   - A votação ocorre apenas pelas reações na mensagem principal: **👍 (a favor)** e **👎 (contra)**.
   - O encerramento é feito pelo **Bot do DA** após **7 dias úteis**.

---

## 3. 🗳️ Regras de Votação — Quórum e Maioria

### 3.1. Critério I — Quórum Mínimo
O total de reações (👍 + 👎) deve ser igual ou superior a **X% dos estudantes ativos** (atualmente definido provisoriamente em **5%**).
`Total de Votos ≥ ⌈ X% × N ⌉`

### 3.2. Critério II — Maioria Absoluta Positiva
As reações positivas devem superar as negativas: `👍 > 👎`.

### 3.3. A Regra do Snapshot
Exatamente às 00:00 do 8º dia útil, o Bot publica um comentário com o extrato dos votos. **Este registo é a Ata Oficial.** Reações adicionadas após este comentário são juridicamente nulas.

---

## 4. 🔀 Regras para Pull Requests — A Ação

### 4.1. Regra de Ouro
**Todo PR deve estar vinculado a uma Issue aprovada.** O corpo do PR deve conter: `Resolves #<número-da-issue>`.

### 4.2. PR de Conquista
Quando um problema do mundo real é resolvido (ex: ar condicionado consertado), deve ser aberto um PR criando um ficheiro em `/conquistas/`. O Merge deste PR fecha a Issue oficialmente e gera o crédito histórico.

### 4.3. Maturação
Todo PR deve ficar aberto para revisão por no mínimo **7 dias úteis** (14 dias para alterações no Estatuto).

---

## 5. 📋 Resumo Rápido

| Ação | Regra Principal |
|---|---|
| **Abrir Issue** | Usar template + label de categoria |
| **Janela de Votação** | 7 dias úteis após label `em-votação` |
| **Encerramento** | Snapshot automático pelo Bot às 00:00 do 8º dia |
| **Aprovação** | Quórum atingido + 👍 > 👎 no Snapshot |
| **Fechar Issue** | Via PR de Conquista em `/conquistas/` |