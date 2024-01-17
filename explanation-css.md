# Explicação do CSS

## Estilo CSS

### Reset de Estilos Globais
* {
    margin: 0;
    padding: 0;
    border: 0;
}

O seletor * representa todos os elementos da página e define margens, preenchimentos e bordas como zero. Isso é comumente usado como uma técnica de "reset" para evitar estilos padrão do navegador.

### Estilo da Página Principal
.page {
    text-align: center;
    font-family: 'Open Sans', sans-serif;
}
O seletor .page define estilos para a página principal, centralizando o texto e usando a fonte 'Open Sans' como a fonte principal.

### Estilo do Hero (Destaque)
.hero {
    width: 592px;
    height: 579px;
    margin: 0px auto 72px;
}
O seletor .hero define o estilo para um elemento com a classe hero, estabelecendo largura, altura e uma margem inferior.

### Estilo da Imagem
#image {
    margin-bottom: 72px;
}
O seletor #image define a margem inferior para um elemento com o ID image.

### Estilo do Texto do Cabeçalho
#header-text h1 {
    font-family: 'Inter', sans-serif;
    font-size: 49px;
    font-weight: normal;
    line-height: 56px;
    margin-bottom: 32px;
}
O seletor #header-text h1 define estilos para os elementos h1 dentro do elemento com o ID header-text, especificando a fonte, tamanho, peso, altura da linha e margem inferior.

#header-text h1 span {
    font-weight: bold;
    color: #FF9900;
}
Estilos adicionais para o elemento span dentro do h1, ajustando o peso da fonte e a cor.

#header-text p {
    font-size: 14px;
    line-height: 28px;
    color: #7D7987;
}
Estilos para os elementos p dentro de #header-text, especificando tamanho da fonte, altura da linha e cor.

#header-text p span {
    color: #FF9900;
}
Estilos adicionais para o elemento span dentro do p, alterando a cor.

### Linha Decorativa
#line {
    width: 568px;
    height: 0px;
    margin: 0px auto 8px;
    border: 1px #ECEFF2 solid;
}
O seletor #line define estilos para uma linha decorativa, especificando largura, altura, margem inferior e uma borda sólida.

### Estilo das Redes Sociais
#social-media {
    font-size: 14px;
    line-height: 28px;
}
O seletor #social-media define estilos para um elemento com o ID social-media, ajustando o tamanho da fonte e a altura da linha.

#social-media a {
    color: #FF9900;
}
Estilos para os links dentro de #social-media, alterando a cor.

#social-media a + a {
    margin-left: 8px;
}
Adiciona uma margem à esquerda para links adjacentes dentro de #social-media.

### Decoração de Bolas
.balls-decoration {
    position: fixed;
    bottom: 180px;
    right: 0px;
}
O seletor .balls-decoration define a posição fixa de um elemento decorativo com bolas, fixando-o na parte inferior direita da página.