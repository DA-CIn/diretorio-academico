<div align="center" style="margin: 2rem 0 4rem">
  <img src=".github/assets/logo-dacin.svg" alt="Diretório Académico do CIn (UFPE) — DA-CIn" width="700" />
</div>

## 🎯 Propósito e Objetivos

O **Diretório Acadêmico (DA-CIn)** é a entidade de representação política e defesa dos direitos dos estudantes do Centro de Informática da UFPE. Ele atua de forma unificada para aumentar o poder de negociação da comunidade discente em pautas de infraestrutura, orçamento, acessibilidade e burocracia acadêmica.

Inativo desde 2024, o DA-CIn ressurge sob um novo paradigma: **Governança como Código**.

Este repositório é a nossa plataforma oficial. Aqui, adotamos a filosofia open source aplicada à política estudantil:

- **Transparência Absoluta:** Tudo é público e versionado.
- **Rastreabilidade:** Quem propôs, quem aprovou e quem bloqueou fica registrado para a posteridade.
- **Memória Imutável:** A regra fundamental do centro agora é: _"Se não tem commit, não aconteceu."_

## 🛠️ Como a comunidade pode agir (Issues e PRs)

Não existem "decisões de gabinete" ou negociações informais. A comunidade é a revisora e a aprovação de pautas segue um fluxo claro, assíncrono e auditável.

Para agir, basta seguir o protocolo:

| Você quer...                                                                    | Ação no GitHub                                                         |
| :------------------------------------------------------------------------------ | :--------------------------------------------------------------------- |
| **Denunciar um problema** (Ex: Falta de água, abuso acadêmico, Prograd travada) | 🐛 **Abra uma Issue** usando o template `Denúncia / Problema`          |
| **Sugerir um evento ou melhoria**                                               | 💡 **Abra uma Issue** usando o template `Proposta de Melhoria`         |
| **Votar em uma pauta**                                                          | 🗳️ Reaja com **👍 (a favor)** ou **👎 (contra)** na Issue em debate    |
| **Alterar as regras do DA**                                                     | 📜 Após debater na Issue, **Abra um Pull Request (PR)** Legislativo    |
| **Registrar uma Vitória**                                                       | 🏆 **Abra um PR de Conquista** para eternizar a resolução de uma Issue |

### 🤖 Automação e Votação

Nós não trancamos debates. Uma vez que uma pauta recebe a label `em-votação`, a janela para receber reações é de **7 dias úteis**. À meia-noite do 8º dia útil, o **Bot Escrivão (GitHub Action)** varre a issue, tira um "snapshot" dos votos e decreta se o quórum foi atingido e a pauta aprovada. Leia o [CONTRIBUTING.md](https://www.google.com/search?q=CONTRIBUTING.md) para os detalhes matemáticos do quórum.

## 🏛️ Estrutura e Governança do DA

Para ser ágil sem perder a representatividade, o DA-CIn atua com uma voz unificada, mas com uma estrutura capilarizada:

1.  **Diretoria Executiva:** O motor do DA. Atua na consolidação e execução das decisões através das Diretorias de Infraestrutura e Vivência, Comunicação, Soluções Tecnológicas (DevOps Cívico) e Ações de Ensino e Suporte Acadêmico.
2.  **Conselho de Representantes de Turma (CRT):** O DA-CIn exige representação obrigatória de **2 membros (Titular e Adjunto)** para cada um dos cursos: Ciência da Computação (CC), Engenharia da Computação (EC), Sistemas de Informação (SI) e Inteligência Artificial (IA). Eles são a ponte de demandas reais e garantem o combate a abusos acadêmicos sistêmicos.

## 🗺️ Mapa do repositório

Abaixo estão os documentos estruturais que compõem a nossa "Legislação em Código". Leia-os para entender seus direitos e o funcionamento do DA:

- **Governança e Regras**
  - ⚖️ [`CONTRIBUTING.md`](https://www.google.com/search?q=CONTRIBUTING.md) — As leis de votação, quórum, abertura de Issues e PRs.
  - 📜 [`estatudo_vigente.md`](https://www.google.com/search?q=estatudo_vigente.md) — O Estatuto oficial do Diretório.
  - 🛡️ [`CODE_OF_CONDUCT.md`](https://www.google.com/search?q=CODE_OF_CONDUCT.md) — Regras de respeito e convivência.
  - ❓ [`FAQ.md`](https://www.google.com/search?q=FAQ.md) — Dúvidas comuns sobre a entidade e a governança.
- **Cargos e Estrutura**
  - 🧩 [`diretorias_e_cargos.md`](https://www.google.com/search?q=diretorias_e_cargos.md) — Organograma e deveres da Diretoria Executiva.
  - 🧑‍🏫 [`representantes_curso.md`](https://www.google.com/search?q=representantes_curso.md) — Obrigações e escopo dos Titulares e Adjuntos.
- **Guias e Operações**
  - 🔧 [`guia_de_reativacao.md`](https://www.google.com/search?q=guia_de_reativacao.md) — Roadmap de emergência para a reativação (Fase atual).
  - 🧭 [`guia_apoio_academico.md`](https://www.google.com/search?q=guia_apoio_academico.md) — Como lidar com descaso institucional e Prograd.
  - 🗳️ [`regimento_eleitoral_base.md`](https://www.google.com/search?q=regimento_eleitoral_base.md) — Regras para garantir eleições livres, justas e sem conflito de interesse.
  - 🗓️ [`calendario_e_iniciativas.md`](https://www.google.com/search?q=calendario_e_iniciativas.md) — Log de atividades recorrentes e fomento a projetos de alunos.
- **Templates**
  - 📝 [`template_ata_reuniao.md`](https://www.google.com/search?q=template_ata_reuniao.md) — Padrão oficial para registrar decisões do Conselho e Diretoria.
  - 🔄 [`pull_request_template.md`](https://www.google.com/search?q=pull_request_template.md) — Checklist obrigatório para transformar debates em código.

## 🛡️ Código de Conduta

Este repositório é território público de toda a comunidade discente. Com acesso vem responsabilidade.

Esperamos respeito, decisões baseadas em evidências e foco exclusivo no **interesse coletivo dos estudantes do CIn**. Debates políticos sobre a educação pública são encorajados; no entanto, o **uso político-partidário** do espaço é estritamente proibido. Assédio, manipulação de votos ou má-fé técnica resultarão em suspensão imediata da organização.

Leia as regras e o processo de denúncia completo no nosso **[Código de Conduta](https://www.google.com/search?q=CODE_OF_CONDUCT.md)**.

## 🌐 Links Oficiais

- **Site Oficial (Linha do Tempo de Conquistas):** _(Em construção)_
- **Canal de Comunicação / Discord:** _(A definir na reativação)_
- **Ouvidoria UFPE:** [ufpe.br/ouvidoria](https://www.ufpe.br/ouvidoria)
