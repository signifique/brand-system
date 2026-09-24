# Brand System

Uma estrutura mínima para começar a base de marca de uma empresa e usá-la no dia a dia, com pessoas e com IA.

Não é um brandbook em PDF que ninguém abre. É uma pasta de arquivos de texto que um agente lê antes de escrever, propor ou decidir em nome da empresa, e que a equipe atualiza conforme aprende.

Material do workshop **Brand System vivo**, da [Signifique](https://signifique.com.br).

## Como usar

**Baixe** o kit em [Releases](../../releases/latest), descompacte e abra a pasta no Codex ou no Claude Code. Diga que quer começar.

O agente lê as instruções que vêm dentro da pasta, pergunta o nome da empresa, conduz uma entrevista uma pergunta por vez e para em cada ponto que precisa de aprovação humana. Você não precisa abrir nenhum arquivo nem decorar comando.

**Sem agente local?** O kit funciona no ChatGPT ou no Claude pelo navegador. Veja `00_COMECE_AQUI/MODO_NAVEGADOR.md`.

## O que tem dentro

| Pasta | Conteúdo |
|---|---|
| `00_COMECE_AQUI` | Ordem de leitura, método, checkpoints, modo navegador |
| `01_ENTRADA` | As perguntas que originam a base |
| `02` a `06` | As quatro camadas: princípios, linguagem, comportamento, expressão |
| `07_SISTEMA` | A síntese, com versão, responsável e pendências |
| `EXEMPLO` | Uma base fictícia preenchida, para mostrar o padrão de resposta |
| `AGENTS.md`, `CLAUDE.md` | As instruções que o agente carrega |
| `CRITERIOS.md` | Como o agente escuta: o que aprofundar e quando parar |

## O princípio

A IA organiza, questiona e consulta. Uma pessoa decide.

Tudo que entra na base é classificado como `[fato]`, `[intenção]`, `[hipótese]`, `[aprovado]` ou `[a investigar]`. Lacuna nunca vira conclusão, e nada é registrado como decisão sem alguém aprovar. É essa disciplina que separa uma base confiável de um texto plausível.

## Atualizações

Cada versão nova é publicada em Releases. O arquivo mantém sempre o mesmo nome, então links e QR Codes antigos continuam funcionando.

## Autoria

A metodologia INCAS é proprietária da Signifique, de autoria de Ethel Shuña. O kit é compartilhado para uso na própria empresa de quem o baixa. A metodologia, seu nome e sua aplicação em serviços de consultoria são de titularidade da Signifique.

© 2026 Signifique · [signifique.com.br](https://signifique.com.br)
