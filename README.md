# TDM-READY

**Checklist de avaliação da prontidão organizacional para adoção do gerenciamento de dívida técnica.**

Acesse o instrumento em: **https://iurycavalcante.github.io/tdm-ready/**

---

## O que é

O TDM-READY é um instrumento de diagnóstico que avalia se uma organização reúne as condições necessárias para adotar o gerenciamento de dívida técnica (GDT). Ele não mede a dívida técnica existente, nem avalia a maturidade de um processo já em operação: seu objeto são as **condições anteriores à adoção**, aquelas cuja ausência costuma fazer iniciativas de GDT fracassarem antes de produzirem resultado.

O instrumento foi desenvolvido no âmbito de uma dissertação de mestrado do Programa de Pós-Graduação em Informática (PPGI) da Universidade Federal do Estado do Rio de Janeiro (UNIRIO), sob a abordagem da *Design Science Research*.

## Estrutura do instrumento

São **21 itens**, distribuídos em três dimensões:

| Dimensão | Itens |
|---|---|
| Pessoas | 9 |
| Processos | 9 |
| Tecnologia | 3 |

Cada item enuncia uma **condição avaliada**, explicita **por que ela importa** e oferece **questões de apoio** que orientam a deliberação do grupo. As questões de apoio não são uma lista a pontuar: elas dão concretude à discussão e sugerem onde procurar evidência, mas a resposta decorre da condição enunciada na formulação do item.

Cada item indica também o seu **escopo avaliado**, isto é, se a condição diz respeito à organização como um todo ou apenas à área de tecnologia. A distribuição é desigual e isso é deliberado: **13 dos 21 itens avaliam a organização** e apenas 8 a área. É uma característica estrutural do instrumento, e a razão pela qual a composição do grupo participante importa tanto quanto o preenchimento em si.

## Como usar

A aplicação é **coletiva** e ocupa entre **45 minutos e 1h30**, conforme o tamanho do grupo e a profundidade do debate. O esforço não está em operar o checklist, e sim em deliberar até uma resposta única por item.

Orientações completas sobre condução, composição do grupo, papel do mediador e tratamento dos itens sem resposta estão disponíveis no próprio instrumento, no botão **?** do canto superior direito.

Três pontos merecem destaque:

- **Designe um mediador da própria organização**, que percorra o checklist sozinho antes de reunir o grupo, em preenchimento simulado, para conhecer os itens e as questões de apoio.
- **Deixar um item em branco é legítimo.** No panorama, itens sem resposta aparecem em cinza, distintos das condições ausentes. Não conseguir avaliar uma condição já é um resultado, e costuma indicar que ela não está clara, visível ou governada na organização.
- **Reúna participantes que cubram os papéis** entre os quais o conhecimento sobre as condições está distribuído — não apenas a área de tecnologia.

## Privacidade dos dados

O instrumento é um **arquivo HTML único e autocontido**. Ele não carrega recursos externos, não faz requisições de rede e não envia respostas a servidor algum. As respostas são gravadas exclusivamente no `localStorage` do navegador de quem preenche, permanecendo naquele dispositivo.

Como a persistência depende da origem de onde a página é servida, **recomenda-se aplicar o checklist pela URL acima**, e não abrindo o arquivo baixado diretamente do disco, onde o comportamento varia entre navegadores.

## Versões

O TDM-READY não é um produto acabado no momento da sua concepção, e sim o resultado de ciclos sucessivos de construção e avaliação, conforme o caráter iterativo da *Design Science Research*.

| Versão | Origem dos refinamentos |
|---|---|
| 1 | Concepção do artefato e estudo de viabilidade |
| 2 | Refinamentos decorrentes das entrevistas |
| 3 | Refinamentos decorrentes do estudo de caso |

A versão 3, publicada neste repositório, incorpora as decisões de refinamento consolidadas após o estudo de caso: explicitação do escopo avaliado por item, painel de orientações de condução, tratamento visual distinto para condições não avaliadas e revisão da numeração dos itens.

## Como citar

Se você utilizar o TDM-READY, cite a versão arquivada no Zenodo:

> CAVALCANTE, Iury. *TDM-READY: Technical Debt Management Adoption Readiness Checklist* (version 3). Zenodo, 2026.

O registro arquivado adota título e descrição em inglês, por ser a língua franca dos repositórios de artefatos de pesquisa. O conteúdo do instrumento permanece em português.

O registro no Zenodo oferece dois identificadores. O **DOI de versão** aponta para a versão 3 exatamente como avaliada, e é o que deve ser citado em trabalhos que se refiram a esta versão. O **DOI de conceito** agrega todas as versões e resolve sempre para a mais recente, sendo preferível quando a referência é ao instrumento em geral.

O arquivo [`CITATION.cff`](CITATION.cff) contém os metadados em formato legível por máquina, e é lido tanto pelo GitHub, no botão *Cite this repository*, quanto pelo Zenodo no momento do arquivamento.

## Trabalho relacionado

CAVALCANTE, Iury; MEDEIROS DOS SANTOS, Paulo Sergio. **How Far From the Metaphor? The Diverse Understandings of Technical Debt in GitHub Issues**. In: Anais do XXIV Simpósio Brasileiro de Qualidade de Software. São José dos Campos, 2025. p. 67-77. DOI: [10.5753/sbqs.2025.14872](https://doi.org/10.5753/sbqs.2025.14872)

## Licença

Distribuído sob a licença [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Veja [`LICENSE`](LICENSE).
