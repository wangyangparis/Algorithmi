## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/wangyangparis/Algorithmi/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

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

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/wangyangparis/Algorithmi/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <meta content="text/html; charset=UTF-8" http-equiv="Content-Type">
    <meta http-equiv=X-UA-Compatible content="IE=edge,chrome=1">
    <meta name=viewport content="width=device-width, initial-scale=1">
    <title>Savoga</title>
    <meta name="description" content="Welcome on my website!">
    <meta name="keywords" content="">
    <link rel="canonical" href="https://savoga.github.io/">
        <!-- Twitter Cards -->
    <meta name="twitter:title" content="Home">
    
    
    <meta name="twitter:card" content="summary">
    <meta name="twitter:image" content="https://savoga.github.io/assets/img/me.png">
    <!-- Open Graph -->
    <meta property="og:locale" content="en_US">
    <meta property="og:type" content="article">
    <meta property="og:title" content="Home">
    
    <meta property="og:url" content="https://savoga.github.io/">
    <meta property="og:site_name" content="Savoga">
    <meta property="og:image" content="https://savoga.github.io/assets/img/me.png">

    
    
    <!-- Handheld -->
    <meta name="HandheldFriendly" content="True">
    <meta name="MobileOptimized" content="320">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Favicons -->
    <link rel="shortcut icon" href="https://savoga.github.io/assets/img/favicon/favicon.ico" />
<link rel="icon" type="image/png" href="https://savoga.github.io/assets/img/favicon/favicon.png" />
    <!-- Feed -->
    <link rel="alternate" type="application/rss+xml" title="Savoga" href="https://savoga.github.io/feed.xml" />
    <!-- CSS -->
    <link rel="stylesheet" type="text/css" href="https://savoga.github.io/assets/css/main.css">
</head>

 <body>
    <script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script type="text/javascript">
      $(function() {
        i = 0;
        $('.menuAc').click(function(){

          $(this).next('.menuMobil').animate({width:'toggle'},350);
          if (i%2==0) {
            $('.baslik').css({
              'filter'         : 'blur(5px)'
            });
            $('.orta').css({
              'filter'         : 'blur(5px)'
            });
            $('.social-links').css({
              'filter'         : 'blur(5px)'
            });
            $('ul.menu').css({
              'animation-duration': '0.1s'
            });
            $(this).css({
              'color': 'rgba(52, 152, 219, 1)'
            });
            i++;
          }
          else {
            $('.baslik').css({
               'filter'         : 'blur(0px)'
            });
            $('.orta').css({
               'filter'         : 'blur(0px)'
            });
            $('.social-links').css({
               'filter'         : 'blur(0px)'
            });
            $(this).css({
              'color': '#ecf0f1'
            });
            i++;
          }

        });
      });
    </script>
    <div class="menuAc">
      <i class="fa fa-bars" aria-hidden="true"></i>
    </div>
    <div class="menuMobil">
          <nav class="nav-home">
      <ul class="menu">
            
				    
				    <li><a class="link" href="https://savoga.github.io/" >Home</a></li>
				
				    
				    <li><a class="link" href="https://savoga.github.io/machinelearning/" >ML</a></li>
				
				    
				    <li><a class="link" href="https://savoga.github.io/stats/" >Stats</a></li>
				
				    
				    <li><a class="link" href="https://savoga.github.io/projects/" >Projects</a></li>
				
				    
				    <li><a class="link" href="https://savoga.github.io/about/" >About</a></li>
				
        </ul>
    </nav>

    </div>
    <div class="baslik">
      Savoga
    </div>
    <div class="orta">
      <div class="ortala">
        <div class="resim">
          <img alt="Savoga" src="https://savoga.github.io/assets/img/me.png">
        </div>
        <div class="pc">
              <nav class="nav-home">
      <ul class="menu">
            
				    
				    <li><a class="link" href="https://savoga.github.io/" >Home</a></li>
				
				    
				    <li><a class="link" href="https://savoga.github.io/machinelearning/" >ML</a></li>
				
				    
				    <li><a class="link" href="https://savoga.github.io/stats/" >Stats</a></li>
				
				    
				    <li><a class="link" href="https://savoga.github.io/projects/" >Projects</a></li>
				
				    
				    <li><a class="link" href="https://savoga.github.io/about/" >About</a></li>
				
        </ul>
    </nav>

        </div>
        <div class="aciklamalar">
          Welcome on my website!
        </div>
      </div>
    </div>
  </body>
</html>

