## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/JonathanGoncalvesDeOliveira/gameTest/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/JonathanGoncalvesDeOliveira/gameTest/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" xml:lang="pt" lang="pt">
	<head>
		<title>Jogo Snake em HTML5</title>
		<meta http-equiv="content-language" content="pt-br" />
		<meta http-equiv="content-type" content="text/html; charset=ISO-8859-1" />		
		<link rel="stylesheet" href="default.css" type="text/css"/>
		<meta name="author" content="Danilo Augusto - maktuiu@gmail.com" />
		<meta name="description" content="Jogo simples para demonstração de funcionamento de canvas em HTML5" />
		<!--[if IE]> <script type="text/javascript" src="js/excanvas.compiled.js"></script>	<![endif]-->
		<script type="text/javascript" src="snake.js"></script>		
	</head>
	<body>
		<div id="container">
			<canvas id="canvas" width="405" height="405">
				Seu browser não suporta canvas
			</canvas>
		</div>
		<div id="box_score">
			<h1> <span id="pontos"> 0 </span>&nbsp;pontos </h1>
		</div>
		
		<div class="legenda">
			<h1>Comandos</h1>
			<p><strong>I</strong> - Iniciar;</p>
			<p><strong>P</strong> - pause;</p>
		</div>
		
	</body>
</html>
