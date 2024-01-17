# Explicação do Projeto HTML

## Estrutura Básica

### `<!DOCTYPE html>`
Define a versão do HTML que o documento está utilizando.

### `<html lang="pt-BR">`
Define o início e o fim do documento HTML, indicando que a linguagem utilizada é o português brasileiro.

## Cabeçalho (head)

### `<link rel="stylesheet" href="/style.css">`
Inclui o arquivo de estilo externo chamado "style.css" para estilizar a página.

### Fontes Google
- `<link rel="preconnect" href="https://fonts.googleapis.com">`
- `<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>`
- `<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Open+Sans:wght@400;700&display=swap" rel="stylesheet">`
Permite o uso de fontes do Google Fonts no projeto, fornecendo estilos específicos para a fonte Inter e Open Sans.

### `<meta charset="UTF-8">`
Define a codificação de caracteres como UTF-8, garantindo suporte a caracteres especiais.

### `<meta name="viewport" content="width=device-width, initial-scale=1.0">`
Controla a escala e largura da viewport, tornando o site responsivo para diferentes dispositivos.

### `<title>Projeto 01</title>`
Define o título da página exibido na aba do navegador.

## Corpo (body)

### `.page`
Div principal que contém todo o conteúdo da página.

### `.hero`
Seção destacada que provavelmente contém uma imagem e texto de destaque.

#### `#image`
Div que contém uma imagem com o caminho "./assets/image.png".

#### `#header-text`
Div que contém um título `<h1>` e um parágrafo `<p>`.

##### `<h1>`
Título principal da página com texto "Ambientes únicos para você!".

##### `<p>`
Parágrafo que descreve os serviços oferecidos, utilizando tags como `<strong>` para destacar palavras.

### `.footer`
Seção de rodapé da página.

#### `#line`
Elemento de linha provavelmente usado para separar visualmente o conteúdo.

#### `#social-media`
Div que contém links de redes sociais.

##### `<a>`
Links para Instagram e Fale Conosco com atributo `target="_blank"` para abrir em uma nova aba.

## Elemento Extra

### `.balls-decoration`
Div que contém uma imagem de decoração com o caminho "./assets/balls-decoration.svg".

##### `<img>`
Elemento de imagem que exibe uma decoração com o texto alternativo "yellow balls decoration".

