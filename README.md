# Curso HTML 5, CSS 3 e JS
## Por Curso em Vídeo 
PS: Repositório utilizado para treimento das linguagens <br />
Esse arquivo tem um resumão, espero que ajude <3 <br />
Obs: png é mais pesado <br />
Tons de cinza: #606060, #666666, #cecece <br />

### Formato do inicio do doc
`<!DOCTYPE html>` para identificar que o documento está em html5 <br />
`<html lang="pt-br">` <br />
    `<head>` Configurações comportamentais  <br />
        `<meta charset="UTF-8">` Para adicionar caracteres latinos <br />
        `<title></title>` título na barra do navegador <br />
        `<link rel="stylesheet" href="./_css/estilo.css">` importar arquivo css<br />
        `<script src="_javascript/funcoes.js"></script>` <br />
        `<script>` códigos `</script>` <br />
    `</head>` <br />
   `<body></body>` Visualmente tudo que vai aparecer
   `</html>
    
## Tags importantes

* `<meta>` define qualquer informação de metadados que não podem ser definidos por outros elementos html;
* `<hgroup>` tap semântica, nada visual. Grupo de títulos;
* `<br>` quebra de linha;
* `&nbsp;` espaço em branco;
* `<em>` tag de ênfase;
* `<nav>` area de navegação
* tag âncora `<a href=" " target="_blank">` href sempre usar http://

### Listas: <br />
ol - ordered list, ul - unordered list, li - list item <br />
`<ol type= " " start=" valor numerico">`
* type="1", type="i", type="a", type="I", type="A" <br /> <br />
`<ul type=" ">`
* type="square", type="circle", type="disc"

### Fonte personalizada
`@font-face {`<br /> 
`font-family: "nome que quer dar";`<br />
`src: url("aonde está na pasta") }`
* Aonde vai importar fonte: <br />
`font-family: "nome dado";`

### Uso do float
* Conteúdo precisa ser `display: block;`

### Table
`<table>` todo o conteúdo da tabela precisa ficar entre as tags <br />
`<caption>` título da tabela <br />
`<tr>` table rows <br />
`<td>` table data <br />
`<td rowspan=" ">` diz quantas linhas o dado vai ocupar <br />
colspan: mesma lógica para coluna <br />

### Mapas de imagem 
`<img src=" " usemap="#id">` <br />
`<map name="id">` <br />
`<area space=" " coords=" " href=" ">` <br />
`</map>` <br />

### Audio e vídeo
`<audio controls="controls">` <br />
`<source src=" " type="audio/mpeg">` para mp3<br />
`Mensagem para quem o nav não carregar o vídeo`<br />
`</audio>`<br />
Para vídeo é a mesma coisa tag<br /><br />
`<video></video>`

### Tag fieldset
![Image](https://www.w3docs.com/uploads/media/default/0001/01/342cfa016339a17d1a83af772115dae2aac7c9e4.png "icon") 

`<fieldset> <legend> texto </legend> conteúdo </fieldset>`
