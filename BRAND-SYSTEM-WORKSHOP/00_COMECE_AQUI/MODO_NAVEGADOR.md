# Modo navegador

Para quem não tem um agente lendo a pasta e vai usar o ChatGPT ou o Claude pelo navegador. Funciona bem, inclusive em conta gratuita.

A diferença não é de qualidade da conversa, é de gravação: no navegador a IA **não escreve nos seus arquivos**. Ela lê o que você subiu e devolve o conteúdo pronto. Quem salva é você, no fim.

## Passo 1, suba os arquivos

No ChatGPT, crie um Projeto e suba todos os arquivos `.md` da pasta do kit. Se a sua conta não tiver Projetos, ou se você estiver no Claude, anexe os mesmos arquivos numa conversa só e trabalhe ali.

Inclua o `AGENTS.md`. É ele que contém as instruções e transforma a conversa no agente.

## Passo 2, abra assim

```
Subi os arquivos de um kit de marca. Leia AGENTS.md e siga aquelas instruções
como se você fosse o agente que trabalha dentro dessa pasta.

Uma diferença importante: aqui você não edita os arquivos que eu subi, eles
são só leitura. Sempre que as instruções mandarem gravar algo, registre na
conversa e mantenha um registro acumulado do que já foi aprovado, sem me
fazer repetir. No fim eu peço o conteúdo completo de cada arquivo e salvo.

Em três linhas: o que vamos construir aqui e por onde começamos?

Depois me entreviste, uma pergunta por vez, como está nas instruções.
Antes da primeira pergunta, pergunte o nome da empresa e o meu nome e papel.
Não cite números de perguntas, não anuncie o que fica para depois e não fale
do tempo.
```

Daqui em diante a conversa é igual à de quem está no agente local. Os mesmos critérios de escuta valem, porque estão nos arquivos que você subiu.

## Passo 3, no fim, extraia

```
Agora vamos salvar. Me entregue o conteúdo completo de um arquivo por vez,
nesta ordem: 01_ENTRADA/comece-pela-sua-marca.md, 02_PRINCIPIOS, 03_ESTRATEGIA,
04_LINGUAGEM, 05_COMPORTAMENTO, 06_EXPRESSAO e 07_SISTEMA.

Um arquivo por mensagem, em bloco de código, com o conteúdo inteiro e não só
o que mudou. Preserve as minhas palavras como eu disse.

Espere eu confirmar que salvei antes de passar para o próximo.

Se você conseguir gerar o arquivo .md para download, melhor ainda.
```

Pedir tudo de uma vez corta conteúdo no meio. Um por vez demora um pouco mais e não perde nada.

## Passo 4, salve

Cole cada conteúdo no arquivo correspondente da sua pasta, ou baixe os `.md` gerados e substitua os da pasta.

Se estiver numa máquina compartilhada, encerre a sessão da sua conta e apague a pasta da máquina depois de copiá-la para o seu armazenamento.

## Quando migrar para o agente local

Se um dia você instalar o Codex ou o Claude Code, é só abrir a pasta e continuar. A base é a mesma, e a partir dali a gravação passa a ser automática.
