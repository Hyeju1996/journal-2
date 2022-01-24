# journal-2

# Jan 19,2022 - Colour, typography and visual hierarchy

We learn about colours strecture on css. Tony show us simple html and putting css codes and what color code works on background on codepen.

After Tony show us how to adding fontawesome on codepen.  

**You can see fontawesome website**

[google-search](https://www.google.com/search?q=best+google+font+combinations);

[google font awesome](https://fonts.google.com/);


## example of html and css code:

**html**


```
<section class="top">

<h1></h1>

<p></p>
</section>
```

**css**

```csharp-interactive
@import url("https://fonts.googleapis.com/css?family=Merriweather:400,400i,700");

body {
  margin: 0;
/*   display: grid; */
/*   place-items: center; */
}

.top {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  background-color: hsl(50, 93%, 45%);
}

.bottom {
  background-color: hsl(350, 93%, 45%);
}

section {
  margin: 0;
  height: 50vh;
}

h1, h2 {
  margin: 0;
  text-align: center;
  padding: 1rem;
}
h1 {
  font-size: 64px;
  font-family: ont-family: 'Lobster', cursive;
}
h2{
  font-size: 36px;
  font-family:'Teko', sans-serif;
}
p {
  
}
```

Learn more here:

[codepen](https://codepen.io/hyeju1996/pen/OJxYgEZ)

## about import in css:
 
 @import is in css adding fonts.

 How can you do it:

- Go to google font awesome I link in to

- slect any font style you like and adding in to css.


# Jan 20,2021- Into to HTML

Ashlyn show intruction about html. Also, we are talking about  Basic html.

- Webpage strecture

- Why, how, and when to use smantic html

Therefore, we are talking about web Design too when we use codepen Ashlyn show us Navigation style and fonts container of Article.

[testpage](https://codepen.io/hyeju1996/pen/PoJrqMb);

## code:

   - Navigation code:
   ```
   <!-- learge black tobbar -->
<nav>
  <!-- horzonal links without bullets-->
  <ul class="nav-links">
    <li>link 1</li>
    <li>link 2</li>
    <li>link 3</li>
  </ul>
</nav>
   ```

- header code:

```
  <!-- Our site is about web developerment-->
<header class="text-container margin-auto">
  <h1>Into to Web Developerment</h1>
  <p>The languages of the web</p>
  <div class="img-wrapper">
    <img src="https://images.pexels.com/photos/7988756/pexels-photo-7988756.jpeg?cs=srgb&dl=pexels-mikhail-nilov-7988756.jpg&fm=jpg" alt="">
  </div>
</header>
<main class="page-wrapper">
  <header class="text-center">
    <h2>Basic HTML Information</h2>
    <p>html5 specification</p>
  </header>
```

- css code:
```

   /* ********************* */
/* **** base styles **** */
/* ********************* */

body {
  background-color: whitesmkoe;
  box-sizing:border-box;
}

header {
  margin-top:50px;
}
header > * {
  margin:0 auto;
  padding: 5px 0;
}
footer {
  background-color: black;
  color: whitesmoke;
  height: 20%;
  margin-top:flex;
  /* These are dependent on the flex direction */
  justify-content: center;
  align-items: center;
}

nav {
  background-color: black;
  color:white;
  display:flex;
}
.nav-links{
  display: flex;
  justify-content: Space-around;
  
  list-style-type: none;
  width:100%;
}
/* images */
img {
  width: 100%;
  height:auto;
}

* Fonts */
h1,
h2,
h3,
h4{
  font-family: 'Montserrat', sans-serif;
}

h1 {
  font-size: clamp(2.5rem, 10vw, 4.5rem);
  font-weight: 900;
}
h2 {
  font-size: clamp(2rem, 5vw, 3rem);
}
h3 {
  font-size: clamp(1.5rem, 5vw, 2rem);
}
h4 {
  font-size: clamp(1.4rem, 5vw, 1.8rem);
  margin: 1;
}
p,
li,
a {
  max-width: 75ch;
  font-family: 'Open Sans', sans-serif;
  font-size: clamp(1.2rem, 5vw, 1.4rem);
  line-height: 1.3;
}

/* ******************** */
/* **** containers **** */
/* ******************** */
.page-wrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
}
.article-container {
  border: 5px solid;
  padding: 20px 10px;
  margin: 20px 20px;
}

.img-wrapper {
  max-width: 800px;
}

.text-box {
  width: 15ch;
  border: 3px solid blue;
  padding: 20px 25px;
}

/* ******************* */
/* **** utilities **** */
/* ******************* */

/* colors */
.bg-red {
  background-color: lightgray;
}
.bg-blue {
  background-color:  lightblue;
}

/* layout */
.margin-auto {
  margin: 0 auto;
}
.text-center {
  text-align: center;
}

.rounded-corners {
  border-radius: 3px;
}
/* text */
.underline {
  text-decoration: underline;
}

.list-style-none {
  list-style-type: none;

```

## problem:

 - I had issues about fonts changing fonts but later that I tried again to adding font.

 ## How I solve it

 I sloved it with refreshing the browser after I keep adding fonts and I compared with Ashlyn's work and mine work that I did wrong. 




