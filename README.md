# Arquivo CSS que cria um balão de dica

## Para implementar:

Em um projeto HTML, pode fazer a cópia do arquivo [balloon.css](https://github.com/mateuslph/balloon/blob/main/balloon.css) no diretírio do projeto. Em seguida importa-se no index.html. \
Outra opção é importar via CDN: ```<link rel="stylesheet" href="https://unpkg.com/balloon-css/balloon.min.css">```

## Para usar:

Código HTML:

```<button aria-label="Whats up!" data-balloon-pos="up">Hover me!</button>```

*  Onde ```aria-label``` é o texto a ser exibido, ```data-balloon-pos``` é a posição. \
*  Quando conter um texto maior, pode-se formatar a caixa de texto para quebrar linhas, então deve usar ```data-balloon-length```, passando-se o tamanho. \
*  Se queseres deixar sempre visível, deve utilizar apenas ```data-balloon-visible```.

## O resultado final fica assim:

![](https://github.com/mateuslph/balloon/blob/main/dica-balloon.png)

### Imagem extraído do site oficial, [kazzkiq.github.io/balloon.css](https://kazzkiq.github.io/balloon.css/):

![](https://github.com/mateuslph/balloon/blob/main/kazzkiq-github-io-balloon-css.png)
