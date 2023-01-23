![banner](https://github.com/z-bj/the-keyboardio-model100/blob/master/product-landing-page-banner.webp)



![html](https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge&logo=HTML5&logoColor=white)
![css](https://img.shields.io/badge/CSS3-1572B6.svg?style=for-the-badge&logo=CSS3&logoColor=white)
![figma](https://img.shields.io/badge/Figma-F24E1E.svg?style=for-the-badge&logo=Figma&logoColor=white)
![githubPages](https://img.shields.io/badge/GitHub%20Pages-222222.svg?style=for-the-badge&logo=GitHub-Pages&logoColor=white)
![freecodecamp](https://img.shields.io/badge/freeCodeCamp-0A0A23.svg?style=for-the-badge&logo=freeCodeCamp&logoColor=white)
![kickstarter](https://img.shields.io/badge/Kickstarter-05CE78.svg?style=for-the-badge&logo=Kickstarter&logoColor=white)

<br>
<br>

# ➪ Read the [user story](https://www.freecodecamp.org/learn/2022/responsive-web-design/build-a-product-landing-page-project/build-a-product-landing-page)
"For this project, you will build a product landing page to market a product of your choice."

<br>

## Implementation of the “Raise the Curtains” Effect in CSS. 

<img src="https://github.com/z-bj/the-keyboardio-model100/blob/master/Wunder-mobility.gif" width="350" height="auto" />
➪ Link to [Wunder Mobility](https://www.wundermobility.com/sharing-ready-vehicles/)

### MIX-BLEND-MODE | SCROLLING | STICKY  👇

```html

<section class="feel-it">
   <div class="content-feel-it">
       <h2 class="h2-feel-it"><span>FEEL IT.</span> MASTER IT.</h2>
   </div>
</section>

````

```css

.feel-it {
    background-image: linear-gradient(to bottom, var(--clr-shark) 50%, var(--clr-romance) 50%);
}


.feel-it::after {
    content: "";
    display: block;
    min-height: 100vh;
}

.content-feel-it {
    min-height: 100vh;
    padding: 0 3rem;
    position: sticky;
    top: 0;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    mix-blend-mode: difference;
}

/* exclusion subtracts the darkest color from the lightest */

.h2-feel-it {
    color: var(--clr-romance);
    font-size: clamp(40px, 7vw, 140px);
    font-weight: 500;
}
```

<br>
<br>

### ➪ View the [result 👀](https://z-bj.github.io/the-keyboardio-model100/)

