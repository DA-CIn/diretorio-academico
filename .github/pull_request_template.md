# Pull Request — DA-CIn UFPE

> Leia o [CONTRIBUTING.md](../CONTRIBUTING.md) antes de preencher. PRs mal preenchidos ou sem Issue vinculada serão **fechados sem análise de mérito**.

---

## 📋 Tipo de PR

<!-- Marque exatamente um tipo. Se marcar mais de um, justifique no campo de descrição. -->

- [ ] 📜 **Legislativo** — altera Estatuto, Regimento ou documentos de cargo (`/estatuto/`, `/eleicoes/`, `/cargos/`)
- [ ] 🏆 **Conquista** — registra resolução de uma demanda do mundo real (arquivo em `/conquistas/` gerado automaticamente pela Action)
- [ ] 🔧 **Correção Trivial** — erro tipográfico ou gramatical em documento não-oficial (`README.md`, etc.)
- [ ] ⚙️ **Infraestrutura do Repositório** — templates, automações, configurações do `.github/`

---

## 🔗 Issue Vinculada

<!-- OBRIGATÓRIO para todos os tipos, exceto Correção Trivial.
     Use exatamente a sintaxe abaixo — o GitHub a reconhece e fecha a Issue automaticamente após o Merge.
     Substituia o número pelo ID real. Não remova a palavra "Resolves". -->

Resolves #

> ⚠️ PRs sem esta linha (exceto Correções Triviais com label `correção-trivial`) serão fechados imediatamente.

---

## 📝 Descrição da Mudança

### O que este PR faz?

<!-- Descreva de forma objetiva o que está sendo alterado, criado ou documentado.
     Para PRs Legislativos: explique a mudança no texto e o impacto normativo.
     Para PRs de Conquista: descreva o que foi resolvido no mundo real e como. -->

### Por que esta mudança é necessária?

<!-- Resuma o problema ou demanda que motivou este PR, complementando o que já está na Issue. -->

### O que este PR NÃO faz?

<!-- Delimite o escopo. Deixe claro o que foi intencionalmente deixado de fora para evitar interpretações equivocadas durante a revisão. -->

---

## ✅ Checklist de Validação

<!-- Marque apenas o que for verdadeiro e verificável. Não marque para "passar" — cada item não marcado é uma informação útil para os revisores. -->

### Processo e Governança

- [ ] Este PR está vinculado a uma Issue existente com a sintaxe `Resolves #ID`
- [ ] A Issue vinculada passou por debate aberto na comunidade antes deste PR ser aberto
- [ ] A Issue vinculada atingiu quórum mínimo de engajamento `(👍 + 👎) ≥ ⌈X% × N⌉`
- [ ] A Issue vinculada possui maioria absoluta positiva `👍 > 👎`
- [ ] Este PR ficará aberto pelo prazo mínimo de maturação exigido (7 dias úteis para PRs gerais / 14 dias úteis para `/estatuto/` e `/eleicoes/`)
- [ ] Não tenho conflito de interesses com o conteúdo deste PR — ou o declarei publicamente em comentário

### Conteúdo

- [ ] A mudança proposta não contradiz nem viola nenhum artigo do Estatuto vigente
- [ ] Os arquivos modificados ou criados estão nas pastas corretas conforme o tipo de PR
- [ ] O Markdown gerado é válido e foi revisado (títulos, listas, links)

### Para PRs Legislativos — ignore se não aplicável

- [ ] As alterações passaram pela revisão obrigatória do grupo definido no `CODEOWNERS` para a pasta afetada
- [ ] O PR não altera mais de um documento estrutural por vez (se alterar, justifique abaixo)

---

## 🗒️ Notas para os Revisores

<!-- Opcional, mas recomendado. Sinalize trechos que merecem atenção especial, decisões de redação que foram deliberadas, ou contexto que não está evidente no diff. -->

---


*Ao submeter este PR, o autor confirma que leu o [CONTRIBUTING.md](../CONTRIBUTING.md) e que as informações acima são verdadeiras e verificáveis.*
