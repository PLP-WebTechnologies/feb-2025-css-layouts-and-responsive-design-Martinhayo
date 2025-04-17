# CSS Layouts and Responsive Design

## Objectives

Implement Flexbox and Grid for layout design.
Make the webpage responsive using media queries.
Ensure proper alignment and spacing.

## Instructions

- use Flexbox or CSS Grid.
- Add a navigation bar and structure the content.
- Use media queries to adjust layout for mobile, tablet, and desktop.

>[!NOTE]
>  - Include at least:
>  - navigation bar
>  - media queries

# Tasks

- Apply Flexbox or Grid for layout.
- -- index.html

- <!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="style.css">
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
        <meta name="description" content="responsive web design">
        <title></title>
        
    </head>
    <body>
        <nav class="navbar">
            <ul class="items" type="none">
                <li class="items"><a href=index.html>HOME</a></li>
                <li class="items"><a href=about.html>ABOUT ME</a></li>
                <li class="items"><a href=contact.html>CONTACT US</a></li>
            </ul>
        </nav>
        <h1 class="container">My story</h1>
        <p class="container">I am Martin hayo, a tech enthusiastic individual with 
            problem solving skills in data analytics and website development</p>
            <img src="geof.png" alt="computer">

    </body>
</html>

--style.css
@media(width:400){}
body{
    background-color: coral;
}
img{
    width:100%;
    height:auto;
}
.container{
    color: black;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 18px;
    font-weight: bold;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}
.container{
    display: grid;
    grid-template-columns: 1fr,2fr;
    grid-gap: 10px;
}

.navbar{
    display: block;
    background-color:black;
    padding: 0px;
    color:white;
    position: relative;
    
}
.navbar ul li{
    display:inline;
    margin-right: 20px;
}

- Make the page responsive.
- Test across different screen sizes.

Happy Coding! 💻✨
