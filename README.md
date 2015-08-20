#guide.html

##Skeleton html structure
This structure should be used for the html of your project where possible:

```html
<!DOCTYPE html>
<!--[if IE]><![endif]-->
<!--[if lt IE 7 ]> <html lang="en" class="ie6"> <![endif]-->
<!--[if IE 7 ]>    <html lang="en" class="ie7"> <![endif]-->
<!--[if IE 8 ]>    <html lang="en" class="ie8"> <![endif]-->
<!--[if IE 9 ]>    <html lang="en" class="ie9"> <![endif]-->
<!--[if (gt IE 9)|!(IE)]><!--> <html lang="en" class=""> <!--<![endif]-->
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">

	<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1.0, user-scalable=no">
	
	<title>Page title</title>
	<!-- bower:css -->
	<!-- endbower -->

	<!--site css-->
	<link rel="stylesheet" href="assets/css/site.css">
	
	<link rel="apple-touch-icon" sizes="57x57" href="/assets/favicons/apple-touch-icon-57x57.png">
	<link rel="apple-touch-icon" sizes="60x60" href="/assets/favicons/apple-touch-icon-60x60.png">
	<link rel="apple-touch-icon" sizes="72x72" href="/assets/favicons/apple-touch-icon-72x72.png">
	<link rel="apple-touch-icon" sizes="76x76" href="/assets/favicons/apple-touch-icon-76x76.png">
	<link rel="apple-touch-icon" sizes="114x114" href="/assets/favicons/apple-touch-icon-114x114.png">
	<link rel="apple-touch-icon" sizes="120x120" href="/assets/favicons/apple-touch-icon-120x120.png">
	<link rel="apple-touch-icon" sizes="144x144" href="/assets/favicons/apple-touch-icon-144x144.png">
	<link rel="apple-touch-icon" sizes="152x152" href="/assets/favicons/apple-touch-icon-152x152.png">
	<link rel="apple-touch-icon" sizes="180x180" href="/assets/favicons/apple-touch-icon-180x180.png">
	<meta name="msapplication-TileColor" content="#ffffff">
	<meta name="msapplication-TileImage" content="/assets/favicons/mstile-144x144.png">
	<meta name="msapplication-config" content="/assets/favicons/browserconfig.xml"></head></html>
</head>
	
<body>

	<div class="page">
		
		<nav role="navigation" class="page__nav" data-position="top" data-reveal-type="push">
			<button class="page__nav-close">Close</button>
			<ul class="nav-menu">
				<li class="nav-menu__item">
					<a class="nav-menu__link" href="">Home</a>
				</li>
				<li class="nav-menu__item">
					<a class="nav-menu__link" href="">News</a>
				</li>
				<li class="nav-menu__item">
					<a class="nav-menu__link" href="">Media</a>
				</li>
				<li class="nav-menu__item">
					<a class="nav-menu__link" href="">About</a>
				</li>
			</ul>
		</nav>

		<div class="page__body">
			<header class="header" role="banner">
				<h1>Page header</h1>
				<nav role="navigation" class="header__nav">
					<ul class="nav-menu">
						<li class="nav-menu__item">
							<a class="nav-menu__link" href="">Home</a>
						</li>
						<li class="nav-menu__item">
							<a class="nav-menu__link" href="">News</a>
						</li>
						<li class="nav-menu__item">
							<a class="nav-menu__link" href="">Media</a>
						</li>
						<li class="nav-menu__item">
							<a class="nav-menu__link" href="">About</a>
						</li>
					</ul>
				</nav>
			</header>
		
			<main class="main" role="main">
				
			</main>
		
			<aside class="sidebar" role="complementary">
			</aside>
			
			<footer class="footer" role="contentinfo">
			</footer>
		</div>
	
	<!--site js-->
	<script src="assets/js/app.js"></script>
	<!--analytics-->

	</div>

</body>
</html>
```


##Helper classes
These classes are included in the default css and should be used where possible to avoid duplicate classes/styles.

###lists
####To define a list
```css
.list
```

####To make the list inline (horizontal) then add the following class also:
```css
.list-inline
```

###Aligning elements
Use the following classes to align elements horizontally:
```css
.align--left
.align--right
.align--top
```

Use the following markup to centrally align elements:
```html
<div class="valign">
	<p class="align--vertical">text align</p>
</div>
```

###Hiding elements
To hide an element use the following class if possible instead of inline styles:
```css
.hide
```
To hide an element at a breakpoint then use the following classes:
```css
.hide-small
.hide-med
.hide-large
.hide-small-med
.hide-med-large
```
Where the bit after '.hide-' defines when the element should be hidden (Relies on breakpoints being set).
S
##Truncating single lines of text
To truncate any content on a single line use the foolowing class:
```css
.truncate
```
>The element will need to have an explicit width set for the truncation to work.

