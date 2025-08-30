+++
date = '2025-08-30T00:06:51-03:00'
draft = false
title = 'Apresentando, Verse'
thumbnail = 'verseweb'
+++

Verse é um editor de Markdown web leve, local-first e de código aberto, construído com foco na objetividade e agilidade. Você pode testar em [verse.p4cs.com.br](https://verse.p4cs.com.br).

# Por que Markdown?

Há muito tempo eu detesto usar programas cheios de _bloat_ para escrever – estou falando de você, Microsoft Word –, então por um longo tempo venho procurando alternativas que sejam simples, rápidas e fáceis de usar.

{{< lead >}}
E então veio o markdown.
{{< /lead >}}

Com a ascensão da IA nos últimos anos, o markdown inevitavelmente ganhou popularidade, já que é a "linguagem" em que as IAs nos respondem. Quando comecei a usá-lo, fiquei impressionado com sua simplicidade e eficácia. Para mim, ele lembrava o poder do HTML ou LaTeX, mas com uma curva de aprendizado muito mais suave e menor complexidade. Então, decidi adotá-lo como meu formato principal de escrita.T00:06:51-03:00'
draft = false
title = 'Apresentando, Verse'
thumbnail = 'verseweb'
+++

# O que é o Verse?

{{< figure src="/img/verseweb.png" alt="Verse Web App Screenshot" >}}

Verse is a lightweight, local-first open source Markdown editor web app, built with objectivity and swiftness in mind. You can try it out at [verse.p4cs.com.br](https://verse.p4cs.com.br).

# Why Markdown?

I have long disliked using bloated applications for writing – I'm looking at you, Microsoft Word –, so for a long time I've been looking for alternatives that are simple, fast, and effortless to use.

{{< lead >}}
And then came markdown.
{{< /lead >}}

With the rise of AI in the last few years, markdown inevitably gained some popularity, since it's the "language" AI answers us in. When I first started using it, I was amazed by how simple and effective it was. To me, it reminded me of the power of HTML or LaTeX, but with a much gentler learning curve, and lower complexity. So, I decided to adopt it as my main writing format.

# O problema

Agora que decidi banir de minha vida os processadores de texto tradicionais, cheios de botões e menus, eu precisava de uma ferramenta para escrever em markdown. Então comecei minha busca por não apenas um editor de markdown, mas uma ferramenta que me permitisse converter meu conteúdo markdown em documentos compartilháveis.

## Ferramenta #1

A primeira ferramenta que testei foi o [Notion](https://www.notion.so/). Não me entendam mal, o Notion é uma ferramenta realmente poderosa, mas não era o que eu estava procurando. Ele permite exportar seu markdown para PDF, mas as muitas outras features que oferece eram um pouco demais para mim, era fácil de se perder na navegação do app.

Eu só queria uma ferramenta de escrita simples, e o Notion parecia mais uma ferramenta de gerenciamento de projetos que também permitia escrever.

## Ferramenta #2

Depois, testei o [Obsidian](https://obsidian.md/). Diferente do Notion, o Obsidian de fato se apresenta como um editor de markdown, e faz um ótimo trabalho nesse papel. Então qual foi o problema dessa vez? Novamente, muitos recursos.

O Obsidian é uma ferramenta incrível por todas as suas capacidades de gerenciamento de conhecimento e plugins da comunidade. Além disso, me permitia exportar anotações como PDF, e até personalizar o CSS do documento exportado (mesmo que eu não tenha conseguido fazer funcionar – muito provavelmente skill issue). E o fato de ter que organizar minhas anotações em um _vault_ (uma estrutura de pastas) me desanimou um pouco.

## Ferramenta #3

[Visual Studio Code](https://code.visualstudio.com/) foi minha próxima tentativa. Eu já usava o VS Code para programar, então por que não usá-lo para escrever também? Ele tem o recurso de Preview do Markdown (que aliás inspirou muito o design do Verse), e com a extensão certa – neste caso [markdownpdf](https://github.com/yzane/vscode-markdown-pdf) do YZane – eu podia exportar meus arquivos markdown em formatos compartilháveis (PDF e imagens), além disso, personalizar o estilo do documento era tão simples quanto criar um arquivo CSS e apontar a extensão para ele nas configurações. Até conseguia usar IA, através do GitHub Copilot, para ajudar na escrita e estilização de documentos.

Então, por que parei de usá-lo? Features. Demais. O VS Code é um software incrível, as coisas que você pode fazer com ele são verdadeiramente infinitas. Mas não é uma ferramenta de escrita. É uma ferramenta de programação que pode ser usada para escrever.

# O _Insight_

Cansei de procurar a ferramenta perfeita por aí. E mesmo que ela possa muito bem existir, por que não construí-la eu mesmo? Afinal de contas, eu tinha alguns requisitos bem inflexíveis pra minha ferramenta de escrita ideal:

- Tinha que ser rápida.
- Tinha que ser simples.
- Tinha que ser fácil.

E assim, minha jornada para construir o Verse começou.

# A Solução (desenvolvendo o Verse)

No início, estava desenvolvendo o Verse como um app nativo para macOS de código fechado, usando SwiftUI. Simplesmente porque queria aprender SwiftUI – e usar liquid glass kkkkk – e pensei que seria uma boa oportunidade para isso. Aqui está uma print de como ficou:

{{< figure src="/img/versemacos.png" alt="Captura de tela 1 do app Verse para macOS" >}}

Bem legal, não é? Era simples e fácil de usar. Não tão rápido, mas rápido o suficiente. Até consegui implementar os recursos de IA e personalização de CSS via interface gráfica – mesmo que ainda fosse um pouco desajeitado.

Então, por que não lançar o Verse assim? Porque percebi que quanto mais pessoas pudessem usá-lo e mais pessoas pudessem contribuir, o Verse se tornaria uma ferramenta melhor.

E bem nessa época, li o [artigo](https://newsletter.posthog.com/p/the-hidden-benefits-of-being-an-open) do PostHog sobre os benefícios do código aberto, e cheguei à conclusão de que tinha que construir o Verse do zero, com código aberto, e de uma forma que pudesse ser usado por qualquer pessoa, em qualquer lugar – o que inevitavelmente me levou à web.

# O Futuro do Verse

O app ainda está nos seus estágios iniciais, e há muito trabalho a ser feito. Mas estou animado com a jornada à frente, e espero que você se junte a mim nela! Confira o [repositório do github](https://github.com/p4cs-974/verse-editor), e sinta-se à vontade para contribuir com o projeto.

No futuro próximo, planejo implementar personalização de CSS e suporte para mais recursos do markdown (ex: mermaid).

Depois disso, quero implementar alguns recursos de IA para auxiliar na escrita e estilização dos documentos (como [o que eu costumava fazer no VS Code](#ferramenta-3) com o Copilot).
