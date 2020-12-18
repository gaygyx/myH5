<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>CSS3实现旋转太极图效果</title>
		<style type="text/css">
			*{
				margin: 0;padding: 0;
			}
			.circlebox{
				width: 300px; 
				height: 300px;
				margin: 100px;
				position: relative;
				animation: move 2s infinite linear;
			}
			.circleblack{
				width: 300px;
				height: 300px;
				background: black;
				border-radius: 50%;
			}
			.circlewhite{
				width: 150px;
				height: 300px;
				background: white;
				border-top-right-radius:150px;
				border-bottom-right-radius: 150px;
				position: absolute;
				top: 0;
				right: 0;
			}
			.circlebb{
				width: 150px;
				height: 150px;
				background: black;
				border-radius: 50%;
				position: absolute;
				top: 0;
				left: 75px;
			}
			.circleww{
				width: 150px;
				height: 150px;
				background: white;
				border-radius: 50%;
				position: absolute;
				top: 150px;
				left: 75px;
			}
			.circlebbl{
				width: 40px;
				height: 40px;
				background: black;
				border-radius: 50%;
				position: absolute;
				top: 205px;
				left: 130px;
			}
			.circlewwl{
				width: 40px;
				height: 40px;
				background: white;
				border-radius: 50%;
				position: absolute;
				top: 55px;
				left: 130px;
			}
			@keyframes move{
				from{transform: rotate(0deg);}
				to{transform: rotate(360deg);}
			}
		</style>
	</head>
	<body>
		<div class="circlebox">
			<div class="circleblack"></div>
			<div class="circlewhite"></div>
			<div class="circlebb"></div>
			<div class="circleww"></div>
			<div class="circlebbl"></div>
			<div class="circlewwl"></div>
		</div>
	</body>
</html>





## Welcome to GitHub Pages这是我的第一个GitHub网页！！！

You can use the [editor on GitHub](https://github.com/gaygyx/myH5/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/gaygyx/myH5/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
