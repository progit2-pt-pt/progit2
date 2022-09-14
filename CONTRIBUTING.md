# Contribuindo com o Pro Git (2ª Edição)


## Licença

Ao abrires um pull request neste repositório, concordas em fornecer o teu trabalho sob a [licença do projeto](LICENSE.asc).
Além disso, concordas em conceder tal licença no teu trabalho, se for necessário para o objetivo de futuras edições impressas, para o @ben e o @schacon.
Caso as tuas alterações apareçam numa versão impressa, serás incluído na [lista de contribuidores](book/contributors.asc).

## Sinalizar um Problema

Antes de sinalizar um problema, verifica se não existe um similar no sistema de rastreamento de bugs.

Além disso, se este problema foi detectado no site git-scm.com, verifica novamente se ainda está presente na versão em pdf.
O problema pode já ter sido corrigido, mas as alterações ainda não foram implantadas.

## Pequenas Correções

Erratas e esclarecimentos básicos serão aceites se nós concordarmos que melhorarão o conteúdo. Tu também podes abrir uma discussão (issue), desta forma poderemos descobrir como, ou se, ela precisa de tratamento.

Se nunca tiveres feito isto, este [guia de fluxo](https://guides.github.com/introduction/flow/) pode ser útil.

## Grandes Reescritas

Abre uma issue para discussão antes de começar. 
Estas alterações tendem a ser bem subjetivas, frequentemente esclarecendo coisas apenas para uma pequena prrcentagem de pessoas e, raramente, valem a pena depois de tudo. 
Editores profissionais já revistos este conteúdo múltiplas vezes, assim, mesmo que tu tenhas, de alguma forma, um gosto superior ou uma melhor gramática do que a nossa, dificilmente o teu texto venha a ser *tão* melhor que até valha a pena mudar grandes partes do projeto.

## Figuras

As imagens neste livro foram geradas usando o [Sketch 3](http://bohemiancoding.com/sketch/), com este [arquivo de  sketchbook](diagram-source/progit.sketch).

Para adicionar uma figura:

1. Adiciona uma página no sketchbook. 
Tenta usar os símbolos incluídos sempre que possível.
2. Adiciona um "slice" na tua página.
Dá-lhe um nome que corresponda ao arquivo PNG destino, relativo à raiz do diretório fonte.
1. Garante que o teu "slice" está configurado para exportação como "800w"


## Tranduções

As traduções para outros idiomas são fortemente encorajadas, mas tratadas de forma um pouco diferente da primeira edição. Agora, mantemos cada tradução num repositório separado e compilamos os arquivos de saída automaticamente usando a ferramenta Atlas. Isto era algo bem difícil de fazer na última edição.

Como as traduções estão num repositório diferente, também podemos ter mantenedores diferentes para cada projeto. A equipa do Pro Git simplesmente junta-os e compila tudo para as equipas de tradução. Para sofrer compilação automática, os repositórios das traduções precisam de estar dentro de git-scm.com website.

### Projetos existentes

Se pretendes ajudar a traduzir a edição 2 da Progit para o teu
idioma, primeiro verifica os projetos já existentes e entra em contato com
as pessoas que se encontram ao cargo deles se já existir uma.

Os projetos existentes incluem:

  Idiomas   |   Projetos
------------ | -------------
Беларуская  | [progit/progit2-be](https://github.com/progit/progit2-be)
Čeština    | [progit-cs/progit2-cs](https://github.com/progit-cs/progit2-cs)
English    | [progit/progit2](https://github.com/progit/progit2)
Español    | [progit/progit2-es](https://github.com/progit/progit2-es)
Français   | [progit/progit2-fr](https://github.com/progit/progit2-fr)
Deutsch    | [progit-de/progit2](https://github.com/progit-de/progit2)
Ελληνικά   | [progit2-gr/progit2](https://github.com/progit2-gr/progit2)
Indonesian | [progit/progit2-id](https://github.com/progit/progit2-id)
Italiano   | [progit/progit2-it](https://github.com/progit/progit2-it)
日本語   | [progit/progit2-ja](https://github.com/progit/progit2-ja)
한국어   | [progit/progit2-ko](https://github.com/progit/progit2-ko)
Nederlands | [progit/progit2-nl](https://github.com/progit/progit2-nl)
Polski | [progit2-pl/progit2-pl](https://github.com/progit2-pl/progit2-pl)
Português (Brasil) | [progit2-pt-br/progit2](https://github.com/progit2-pt-br/progit2)
Русский   | [progit/progit2-ru](https://github.com/progit/progit2-ru)
Slovenščina  | [progit/progit2-sl](https://github.com/progit/progit2-sl)
Српски   | [progit/progit2-sr](https://github.com/progit/progit2-sr)
Tagalog   | [progit2-tl/progit2](https://github.com/progit2-tl/progit2)
Türkçe   | [progit/progit2-tr](https://github.com/progit/progit2-tr)
Українська| [progit/progit2-uk](https://github.com/progit/progit2-uk)
Ўзбекча  | [progit/progit2-uz](https://github.com/progit/progit2-uz)
简体中文  | [progit/progit2-zh](https://github.com/progit/progit2-zh)
正體中文  | [progit/progit2-zh-tw](https://github.com/progit/progit2-zh-tw)

### A Tua Linguagem Não Existe

Então estas com sorte! Tu serás o que vai iniciar um novo projeto de tradução!

Tu podes começar a fazer a tua própria versão com a segunda edição em inglês, disponível aqui. Para fazer isso,

 1. Escolhe o teu [ISO 639 code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) e cria uma organização GitHub, que diga `progit2-[your code]` no github
 2. Cria um projeto progit2
 3. Copia a estrutura do progit/progit2 (este projeto) no teu projeto e começa a traduzir. Podes reutilizar algum material da primeira edição, mas tem cuidado com isto:
    1. o texto foi reformulado em várias partes
    2. a marcação mudou de markdown para [asciidoc](http://asciidoc.org)
 4. pressiona para o novo repo alguns capítulos traduzidos
 5. Segue um organizador para que a segunda edição do Lucro no teu idioma seja pressionada git-scm.com.
