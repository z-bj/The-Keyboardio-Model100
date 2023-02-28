
![Keyboardio Model 100 Banner](https://github.com/z-bj/The-Keyboardio-Model100/blob/master/Keyboardio-tribute-page-banner.jpg)

# The Keyboardio Model 100 Landing Page

![html](https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge&logo=HTML5&logoColor=white)
![css](https://img.shields.io/badge/CSS3-1572B6.svg?style=for-the-badge&logo=CSS3&logoColor=white)
![figma](https://img.shields.io/badge/Figma-F24E1E.svg?style=for-the-badge&logo=Figma&logoColor=white)
![kickstarter](https://img.shields.io/badge/Kickstarter-05CE78.svg?style=for-the-badge&logo=Kickstarter&logoColor=white)

This is a landing page for the Keyboardio Model 100, an ergonomic keyboard that was built through a Kickstarter campaign. As a fan of this keyboard, I wanted to create a landing page to showcase its features and benefits.

The landing page was built using HTML5 and CSS3, with the design created using Figma. JavaScript was intentionally avoided for this project. The "Raise the Curtains" effect in CSS was implemented on the page to add a unique visual element.

## User Story

For this project, the goal was to build a product landing page to market a product of my choice, and I chose the Keyboardio Model 100.

## Implementation

The "Raise the Curtains" effect was achieved using the `mix-blend-mode` property, combined with `scrolling` and `sticky` properties. Here's the code used for the effect:

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
## Mobile View

![Keyboardio Model 100 Mobile View](https://github.com/z-bj/The-Keyboardio-Model100/blob/master/Raise_the_curtain_effect.gif)

## Visit the Landing Page

You can test the full page [here](https://z-bj.github.io/The-Keyboardio-Model100/).

## Technologies Used

![HTML5 Badge](https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge&logo=HTML5&logoColor=white) ![CSS3 Badge](https://img.shields.io/badge/CSS3-1572B6.svg?style=for-the-badge&logo=CSS3&logoColor=white) ![Figma Badge](https://img.shields.io/badge/Figma-F24E1E.svg?style=for-the-badge&logo=Figma&logoColor=white) ![Kickstarter Badge](https://img.shields.io/badge/Kickstarter-05CE78.svg?style=for-the-badge&logo=Kickstarter&logoColor=white)

## Credits

-   Silvestar Bistrović for the "Raise the Curtains" effect implementation.
-   Keyboardio for creating such a unique and ergonomic keyboard.
