## Mock up pizza shop website built from scratch

HTML
CSS
Wireframes
Git
Markdown

## HTML

Initial Commit

Started building the foundations of the landing page. Imported all images. 
Imported the desired font link. Started the navigation bar using lists.


```html

<head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>Jonny Boy's Pizza</title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link href='https://fonts.googleapis.com/css?family=Luckiest Guy' rel='stylesheet'>
        <link rel="stylesheet" href="css/styles.css">
    </head>
    <body>


      <header>
        <h1>Jonny Boy's</h1>
          <img src="images/burger icon.svg.png" width="50px" height="60px"> 
          <img src="images/pizza logo.jpeg" width="200px"> 

            <nav-bar>
              <ul>
                <li>About</li>
                <li>Menu</li>
                <li>Bookings</li>
              </ul>
            </nav-bar>      
      </header>

```


## CSS

Chose the background colour for the body and the header. 
Began styling the header's font, font size, colour and margin. 

```css

body {
    background-color: #F2EFDE;
    margin: 0;
}

header {
    background-color: #F2EFDE;
    margin: 0;
    
}

header h1 {
    color: #5F8661;
    margin-left: 15px;
    font-family: 'Luckiest Guy'; 
    font-size: 28px;
}


```

Second Commit

Used flex box to arrange all headers, main section and footer. Styled header text and burger. Inserted main description in body and styled. Styled icons for footer. Inserted font styles.

## HTML

```html

<header>
      <div class="top-header">
        <h1>Jonny Boy's</h1>
        <img src="images/burger icon.svg.png" alt="burger icon" class="burger"> 
      </div>
        
      <div class="pizza-logo-section">
        <img src="images/pizza logo.jpeg" alt="pizza logo" width="250px"> 
      </div>

      <div class="nav-bar">
        <ul>
          <li>About</li>
          <li>Menu</li>
          <li>Bookings</li>
        </ul>
      <div>      
    </header>

    <main-section>
      <div class="main-section">
        <p>Jonny Boy’s pizza strictly use only the freshest ingredients when making your pizza because we believe that perfect toppings make the Perfect Pizza.</p><br>  
        <p>If you want more then just great tasting pizza, look no further as Jonny Boy's also create a range of the richest and popular entree's, pasta, ribs & wings, deserts and supply the most popular soft drinks.</p><br>
        <p>Wait no longer, give us a call and have a Jonny Boy's experience tonight! Now stocking gluten free pizza bases.</p><br>
      </div>

      <div class="ph-number">
        <p>0412 345 678</p>
      </div>

      <div class="email-address">
        <p>jonnyboys@pizza.com</p>     
      </div>
        <br>
        <hr>
    </main-section>
      
    </body>

    <footer>
      <div class="footer">
        <img src="images/facebook icon.png" alt="facebook icon">
        <img src="images/instagram icon.png" alt="instagram icon">
        <img src="images/phone icon.png" alt="phone icon">
        <img src="images/mail icon.png" alt="mail icon">
      </div>
    </footer>
```

## CSS

```css
* {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

body {
    background-color: #F2EFDE;
    margin: 0;
}

.top-header {
    background-color: #F2EFDE;
    margin: 0;
    display: flex;
    justify-content: space-between;
    /* border: 2px solid#5F8661; */
}

h1 {
    color: #5F8661;
    margin-left: 15px;
    font-family: 'Luckiest Guy'; 
    font-size: 38px;
    margin-top: 22px;
}

.burger {
    width: 60px; 
    margin-right: 20px;
    margin-top: 10px;
    filter: invert(55%) sepia(22%) saturate(571%) hue-rotate(73deg) brightness(84%) contrast(85%);
}

.pizza-logo-section {
    display: flex;
    justify-content: center;
    padding-top: 8px;
    /* border: 2px solid#5F8661; */
}

.nav-bar ul {
    display: flex;
    justify-content: center;
    justify-content: space-around;
    /* border: 2px solid#5F8661; */
    list-style: none;
    font-family: 'Luckiest Guy'; 
    font-size: 25px;
    color: #5F8661;
    padding-bottom: 15px;
    text-decoration: none;
    box-shadow: 0 8px 8px -4px #707070;
}

.main-section {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    align-items: center;
    text-align: center;
    /* border: 2px solid#5F8661; */
    padding-top: 40px;
    padding-left: 43px;
    padding-right: 43px;
    font-family: 'Lusitana';font-size: 19px;
}

.main-section p {
   color: #323232;
}

.footer {
    display: flex;
    justify-content: space-around;
    /* border: 2px solid#5F8661; */
    height: 88px;
    position: fixed;
    bottom: 0;
    width: 100%;
    padding-top: 15px;
}

footer img {
    width: 50px;
    height: 50px;
    filter: invert(55%) sepia(22%) saturate(571%) hue-rotate(73deg) brightness(84%) contrast(85%);
}

.ph-number {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    align-items: center;
    text-align: center;
    font-family: 'Lusitana';font-size: 19px;
    color: #323232;
    padding-left: 40px;
    padding-right: 40px;
}

.email-address {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    align-items: center;
    text-align: center;
    font-family: 'Lusitana';font-size: 19px;
    color: #323232;
    padding-left: 40px;
    padding-right: 40px;
    padding-top: 15px;
}

hr {
    height: 1px;
    width: 300px;
    background-color: #323232;
    border: none;
    margin: auto;
}
```


## Wireframes



