# Practice your HTML: Build a blog mockup

## Instructions

Imagine you are designing, or redesigning, your personal web site. Create a graphical mockup of your site, and then write down the HTML markup you would use to build out the various elements of the site. You can do this on paper, and scan it, or use software of your choice, just make sure to hand-code the HTML markup.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content = "width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family:Arial, Helvetica, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #ffffff;
            color: #000000;
            text-align: center;
        }

        nav {
            background-color: #9c3030;
            padding: 10px;
        }

        nav a {
            color: #000000;
            text-decoration: none;
            padding: 10px;
            margin-right: 10px;
            display: inline-block;
            font-weight: bold;
        }
        .container { 
			display: flex; 
			justify-content: space-between; 
			max-width: 95%; 
			margin: 0 auto; 
			padding: 20px; 
		} 

		article p { 
			text-align: justify; 
		} 

		main { 
			flex: 2; 
		} 

		article { 
			margin-bottom: 20px; 
			padding: 10px 20px; 
			border: 1px solid rgb(149, 209, 206); 
			margin-right: 10px; 
		} 

		aside { 
			flex: 1; 
			background-color: #a3cff3; 
			padding: 10px; 
		} 

		footer { 
			background-color: #242424; 
			color: #fff; 
			text-align: center; 
			position: fixed; 
			bottom: 0; 
			width: 100%; 
		} 
    </style>
    <title>Welcome</title>
</head>

<body>
    <header>
        <h1>My Projects</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Terrarium</a>
        <a href="#">Typing Game</a>
        <a href="#">WIP</a>
    </nav>

    <div class="container">
        <main>
            <article>
                <h2>Terrarium</h2>
                <p class="post-meta">
                    Last editted on May 5, 2025 by Haochen Min
                </p>
                <p>
                    placeholder text for terrarium info
                </p>
            </article>
            <article>
                <h2>Typing Game</h2>
                <p class="post-meta">
                    Last editted on May 5, 2025 by Haochen Min
                </p>
                <p>
                    placeholder text for typing game info
                </p>
            </article>
            <article>
                <h2>WIP</h2>
                <p class="post-meta">
                    Last editted on May 5, 2025 by Haochen Min
                </p>
                <p>
                    placeholder text for wip info
                </p>
            </article>
        </main>
        <aside>
            <h2>Recently Updated</h2>
            <ul>
                <li><a href="#">Terrarium</a></li>
                <li><a href="#">Typing Game</a></li>
                <li><a href="#">WIP</a></li>
            </ul>
        </aside>
    </div>

    <footer>
        <p>2025 Haochen's Website</p>
    </footer>
</body>

</html>
```

## Rubric

| Criteria | Exemplary                                                                           | Adequate                                                                         | Needs Improvement                                                                 |
| -------- | ----------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- |
|          | A blog layout is represented visually with at least 10 elements of markup displayed | A blog layout is represented visually with around 5 elements of markup displayed | A blog layout is represented visually with at most 3 elements of markup displayed |
