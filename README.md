
![Keyboardio Model 100 Banner](https://github.com/z-bj/The-Keyboardio-Model100/blob/master/Keyboardio-tribute-page-banner.jpg)

# The Keyboardio Model 100 Landing Page

![html](https://img.shields.io/badge/HTML5-E34F26.svg?style=for-the-badge&logo=HTML5&logoColor=white)
![css](https://img.shields.io/badge/CSS3-1572B6.svg?style=for-the-badge&logo=CSS3&logoColor=white)
![figma](https://img.shields.io/badge/Figma-F24E1E.svg?style=for-the-badge&logo=Figma&logoColor=white)
![kickstarter](https://img.shields.io/badge/Kickstarter-05CE78.svg?style=for-the-badge&logo=Kickstarter&logoColor=white)



> This repository features a product landing page built using HTML5 and CSS3, with the design created using Figma. JavaScript was intentionally avoided for this project. The "Raise the Curtains" effect in CSS was implemented on the page to add a unique visual element, to create an immersive user experience

<img src="https://cultofthepartyparrot.com/parrots/hd/portalorangeparrot.gif" width="36">

## Purpose

The purpose of this landing page is to promote the Keyboardio Model 100 ergonomic keyboard, which was designed with user comfort in mind. The keyboard features a unique split design that reduces strain on the wrists and arms, making it an ideal choice for anyone who spends a significant amount of time typing.

> This amaizing ergonomic keyboard was funded through Kickstarter.

As a fan of the product, I created this landing page to showcase the keyboard's unique features and benefits, and to provide potential customers with a compelling reason to purchase it.

## Mobile View

![Keyboardio Model 100 Mobile View](https://github.com/z-bj/The-Keyboardio-Model100/blob/master/Raise_the_curtain_effect.gif)


## Features

The landing page features a bold gradient background and a prominent heading that utilizes the "difference" mix-blend-mode to create a striking visual effect. The heading is also designed to be responsive, using the clamp function to ensure that it scales appropriately on different screen sizes.

To enhance the user experience, the page includes scrolling and sticky positioning, allowing users to easily navigate through the content while maintaining the effect's continuity. Additionally, the page is designed to be JavaScript-free, ensuring that it is accessible and quick to load on all devices.

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

## Visit the Landing Page

You can test the full page [here](https://z-bj.github.io/The-Keyboardio-Model100/).
<img src="https://cultofthepartyparrot.com/parrots/hd/portalblueparrot.gif" width="36">

## Credits

-   Silvestar Bistrović for the "Raise the Curtains" effect discovery.
-   Keyboardio for creating such a unique and ergonomic keyboard.


