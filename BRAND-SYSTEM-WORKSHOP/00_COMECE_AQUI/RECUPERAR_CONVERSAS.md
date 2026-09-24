# Recuperar o que você já tem

Opcional, e vale muito a pena.

Se você já conversou com o ChatGPT ou o Claude sobre a sua empresa, existe material seu espalhado por lá: textos de site, propostas, bios, posts, histórias que você contou, decisões que explicou. Dá para recuperar isso e começar de um lugar bem melhor do que a página em branco.

O cuidado: essas conversas também estão cheias de texto que a IA inventou e você nunca validou. Propósito bonito, posicionamento redondo, valores de parede. Por isso a recuperação separa o que veio de você do que veio da máquina.

## Passo 1, no ChatGPT ou no Claude, no navegador

Cole este pedido na ferramenta onde estão as suas conversas antigas.

```
Você vai me ajudar a recuperar o que já conversamos sobre a minha empresa.

Procure nas nossas conversas anteriores tudo que eu já te contei sobre o meu
negócio: o que eu vendo e para quem, como a empresa começou, decisões que
tomei, clientes, problemas reais, textos que te pedi (site, bio, proposta,
post, anúncio, e-mail) e qualquer coisa que eu tenha dito sobre como a
empresa fala ou se comporta.

Organize em cinco blocos:

1. O que EU te contei sobre a empresa. Fatos, histórias, exemplos, números,
   nomes, situações reais, nas minhas palavras.
2. O que VOCÊ propôs e eu aprovei ou usei. Textos e ideias que eu confirmei,
   ou que pedi para seguir em frente.
3. O que VOCÊ propôs e eu nunca confirmei. Sugestões soltas, versões que eu
   não comentei, propósito ou posicionamento que saiu de você e não de mim.
4. Palavras e expressões que EU uso quando falo da empresa.
5. O que ficou em aberto. Perguntas que você me fez e eu não respondi, e
   coisas que eu disse que ia confirmar depois.

Regras:
Não invente nada. Se um bloco ficar vazio, escreva "nada encontrado".
Não reescreva em linguagem de marketing. Prefira as minhas palavras às suas.
Cite a frase original quando ela for específica.
Não conclua posicionamento, propósito nem diferencial. Só organize o que existe.

Ao final, gere o resultado como um arquivo .md para download, com o nome
recuperado-de-conversas.md, começando exatamente por este cabeçalho:

# Recuperado de conversas anteriores

Origem: conversa com [ferramenta], recuperado em [data].
Nada aqui foi validado pela empresa.
Blocos 1, 2 e 4 vieram de mim ou foram aprovados por mim.
Bloco 3 foi proposto por IA sem a minha confirmação. Tratar como hipótese.
Bloco 5 são pontos em aberto.

Se você não conseguir gerar arquivo para download, entregue o conteúdo
inteiro em um único bloco de código para eu copiar.

Se você não tiver acesso ao histórico das nossas conversas, me diga isso
e eu colo os textos manualmente.
```

## Passo 2, salvar o arquivo

Salve o arquivo baixado dentro da pasta `01_ENTRADA`.

Se você salvar em outro lugar da pasta do kit, tudo bem: o agente encontra e move sozinho.

Se ele foi parar em Downloads, mova para dentro da pasta do kit e apague o que sobrar em Downloads. Em máquina compartilhada, nada seu deve ficar fora da sua pasta.

Se a ferramenta não gerou arquivo e você só tem o texto, crie um arquivo chamado `recuperado-de-conversas.md` dentro de `01_ENTRADA` e cole o conteúdo lá.

## Passo 3, entregar ao agente

```
Estou enviando o arquivo `recuperado-de-conversas.md`, mova-o para a pasta `01_ENTRADA`.

Leia e respeite as origens marcadas nele. Registre no arquivo de entrada
apenas o que veio de mim ou que eu aprovei. O que foi proposto por IA sem
a minha confirmação, trate como hipótese a investigar, nunca como fato.

Me pergunte sobre os dois ou três pontos mais importantes que ficaram em
aberto, um de cada vez.

Depois me diga em poucas linhas o que esse material já responde e o que
continua faltando.
```

A partir daí o encontro deixa de ser lembrar do zero e passa a ser corrigir e refinar, que rende muito mais em vinte minutos.
