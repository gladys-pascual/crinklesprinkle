<h1 align="center">CrinkleSprinkle Website</h1>

[View the live project here.](https://gladys-pascual.github.io/crinklesprinkle/)

CrinkleSprinkle is a homemade cookie crinkle delivery business operating in South Dublin, Ireland.

The goal of this website is to provide information abd promote the business to potential and existing customers.

It is designed to be responsive and accessible on a range of devices, such as PCs, tablets and mobiles, making it easy to navigate for potential customers.

<img src="assets/images/crinkesprinkle.gif">

<br/>
<br/>
<br/>

## User Experience (UX)

- ### User stories
  - As a potential customer, I want to learn about CrinkleSprinkle and determine what the business is about.
  - As a potential or current customer, I want to navigate different pages of the website both by desktop and mobile.
  - As a potential customer, I want to learn what crinkles are in order to determine whether this is something I would like to buy.
  - As a potential or current customer, I want to see a gallery of pictures that crinkles to see how it looks like.
  - As a potential or current customer, I want to know my options of buying from crinkle sprinkle such as the flavours available, its cost, where the crinkles can be delivered, and how to place an order.
  - As a potential or current customer, I want to know how I can contact the business.
  - As a potential or current customer, I want to be able to identify the crinklesprinkle tab when I have loads of tabs open on my browser so that I can go back to the website easily.
  - As a potential or current customer, I want to be able to place my order.
- ### Design
  - #### Colour Scheme
    - The website [coolors.co](https://coolors.co/) was used to create the colour theme for the website.
    - The main colour used was a grey hint of pink (#ece4df) which gives a modern look. Using [coolors.co](https://coolors.co/), a color pallete was created around the main colour to ensure that the colours compliment each other.
  - #### Typography
    - The Lato font is the main font used throughout the whole website and Roboto on the main headings and navigation links, with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. The text at the homepage banner used "Caveat" font with font "cursive" as a fallback.
  - #### Imagery
    - Imagery is important. The large banner image of baked chocolate cookie crinkles is designed and animated to catch the user's appetite. It has a modern, energetic aesthetic.
    - The logo of CrinkleSprinkle was designed to give a modern aesthetic to the business.
    - The pictures in the gallery section are aimed to showcase the crinkle cookies made by the business, to show potential customers on what to expect when ordering from the business.
  - #### Animations
    - Four custom animations were created.
      - logo-bounce-animation: When there is a hover on the logo, logo-bounce-animation is applied to let the user know that the logo is a clickable link. The logo-bounce-animation adds some fun to the website.
      - banner-zoom and banner-text zoom: This was based on the animation learned from love-running lectures in Code Institute. It brings a modern look onthe website.
      - footer-image: This animation zooms in the logo in the footer, similar to banner zoom. Adds an emphasize on the crinklesprinke logo in the footer in a nice, modern look.
  - #### Favicon
    - CrinkleSprinkle favicon was used to allow user to distinguish the tab when multiple tabs are open in their browser, which allows for a better user experience.

### Wireframes

- Wireframes for both desktop and mobile of all the pages of this project are available [here](assets/wireframe/crinklesprinkle_wireframe.pdf).

## Features

### Responsiveness

Ensure responsiveness on all device sizes by using media queries.

- Use of media queries that has various screensize breakpoints to ensure that all the pages of the website looks good at all screen sizes.
-

### Accessibility

- Ensure accessibility throughout the website by:
  - Adding 'alt' text on all images.
  - Font awesome icons are in an `<i>` tag. A span with a class "sr-only" is added which describes the icons. The "sr-only" class has a display:none in the stylesheet, which hides the text on screen, but allows for screenreader to be read.

### Header

- CrinkleSprinkle logo
  - Logo is placed on the left hand side of the website.
  - Logo is a link and if clicked, it brings you to the homepage.
  - An animation is applied on the logo if hovered to let the user know that it is a link
- The header includes navigation links to different pages of the website, which are Home, Our Crinkles, Gallery, and Contact Us.
- A background colour is applied on the page that you currently exist on (using class names) to ensure that the user knows that page of the website they are on.
- When navigation links are hovered, the text colour changes, for better user experience.
- At tablet and mobile, the list of navigation links were replaced by a 'hamburger' button. When clicked, a dropdown of the navigation links will be shown. This feature ensures that the website looks clean at smaller screens but still ensuring accessibility to users.

### Footer

- CrinkleSprinkle logo has a zoom an animation as the page is loaded, giving a modern and sophisticated look. This time, it was found appropriate that the logo is not a link in order to not confuse the user.
- Links to Instagram and email are available in the footer. Change in styling is applied when links are hovered to let the user know that the icons are links, allowing for better user experience.

### Home

- A large banner image of baked chocolate cookie crinkles can be first seen in the homepage, along with the a huge text of the name of the business, CrinkleSprinkle. An zoom animation was applied aiming to catch the user's apetite and giving the website a modern, energetic aesthetics.
- Below the business name, a **short** description of what the business can offer is given. Then, a link "SEE OUR CRINKKLES" will direct the user to the "Our Crinkles" page, where the user can see what the business can offer.
- If the user decides to scroll down the homepage, a description of crinkle cookies are shown, along with an even more apetizing image of the cookie crinkles. This is aimed to encourage the user to buy from the business.

### Our Crinkles

- The business currently sells two flavours of crinkle cookies. The flavours are described in each 'card', along with the price and number of cookies per order. Cookie emojis were used for better user experience as it is more visual, which can increase the apetite of the user for a crinkle cookie.
- Details about the delivery and catering options are also listed in this page. Links to contact the business are available in the descriptions for ease of contacting the business, so that the user doesn't have to scroll to the footer or go to "Order Here" if they suddenly want to contact the business as soon as they read the descriptions.

### Gallery

- A number of good quality images taken by the business owner are available in the Gallery section.
- The gallery section aims to provide a visual representation of what the CrinkleSprinkle business can offer to its customers.
- To ensure responsiveness, media queries were used to decrease the number of images displayed as the screen size gets smaller.

### Order Here

- An order form is available where you can:
  - Choose crinkle flavour (required)
  - Add order notes (optional)
  - Add your name (required)
  - Email address (required)
  - Mobile number (required)
  - Delivery address (first line and eircode required, middle line optional)
- For now, since there is no backend connected to the page yet, as you click "order your crinkles" button, the page will be navigated to "Thank You" page, where it will state that CrinkleSprinkle is thanking the user for their order and that the user will be contacted in 24 hours. A list of payment options will also be shown.

<br/>
<br/>

## Technologies Used

### Languages Used

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
  - Flexbox was mainly used to create the website responsive on all devices such as PCs, tablets and mobiles.
- [Google Fonts:](https://fonts.google.com/)
  - Google fonts were used to import the 'Lato' font into the style.css file which is used on all pages throughout the project, while 'Roboto' was used for headings.
- [Font Awesome:](https://fontawesome.com/)
  - Font Awesome was used throughout the website to add icons for aesthetic and UX purposes.
- [Git](https://git-scm.com/)
  - Git was used for version control to commit to Git and Push to GitHub.
- [GitHub:](https://github.com/)
  - GitHub is used to store the projects code after being pushed from Git.
- [Virtual Studio Code](https://code.visualstudio.com/)
  - Virtual studio code was used to write the code.
  - [![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier) Prettier, a VS code extension, was used to automatically format the code as it is saved to mitigate code errors.
- [Balsamiq:](https://balsamiq.com/)
  - Balsamiq was used to create the [wireframes](assets/wireframe/crinklesprinkle_wireframe.pdf). during the design process.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

- [W3C Markup Validator](https://validator.w3.org/#validate_by_input)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)

During testing, the following errors were found and were rectified:

- Using [W3C Markup Validator](https://validator.w3.org/#validate_by_input):

  1. In the header, there was initially a `<div>` inside a `<ul>`, aimed to group the navigation links for the dropdown button being created for mobile and tablet sizes. The W3C Markup Validator gave an error to this as a `<div>` cannot be inside a `<ul>`. Both the HTML and CSS code was adjusted where the `<div>` was removed inside of `<ul>`, and the styling was fixed to ensure that the dropdown was not broken.

  2. Initially, the "SEE OUR CRINKLES" link in the home section and the "ORDER YOUR CRINKLES" link in the order here section were written as `<button>`, with a link tag `<a>` inside. The validator gave an error where an element must not appear as a descendant of the button element, which is the case initially (`<a>` is a descendant of `<button>`) The `<button>` element was removed and the link tag `<a>` was styled to make it look like a button.
  3. In the `<form>` of "Order Here" section, an incorrect type for the input text boxes were initially used. This was rectified.
  4. Warning on lack of headings on the gallery and thank-you section. This was rectified by adding `<h1>` with the title of the page, but putting the `class = "sr-only"`, which has a style of display to none, used for the `<i>` tags for font awesome described in the accessibility section earlier.

- Other general errors found during testing:

  - When the page was first deployed, all the images did not appear. During the coding, I used a localhost port 5500 to see my page and all images were uploading fine. I used chrome developer tools to debug and figure out what was causing this error. The filepath for all the images were written incorrectly with an extra '/' at the beginning, causing the images to not load when deployed. This was rectified.
  - I used chrome developer tools extensively to ensure alignment was correct and to figure out the default margins or paddings that I was not initially aware of.
  - Once deployed, the deployed link was tested on a mobile phone to ensure repsonsiveness. Note that Chrome Developer Tools with mobile view was used during development, but the deployed link was still tested in mobile view. Two things were seen:
    - Our Crinkles page: The price of chocolate crinkles is justified on the next line and justified on the left, which did not look correct. The style was changed for screen size at 500 px in media queries already created, using `justify-content: space-evenly'`.
    - Order Here page: Some of the inputs were justified on the left, some on the center. This was fixed by justfying everything on center, making the page consistent.

- Testing User Stories:
  1. As a potential customer, I want to learn about CrinkleSprinkle and determine what the business is about.
     - Upon entering the site, the users are automatically greeted with the business logo and easily readable navigation bar on the top of the page. Below, a banner image, a short description about the business, and a "See Our Crinkles" link that will navigate the user for more information.
     - The user has two options, click the link or scroll down.
     - If the user chooses to scroll down the home page, a description of crinkle cookies are shown, along with an even more apetizing image of the cookie crinkles.
  2. As a potential or current customer, I want to navigate different pages of the website both by desktop and mobile.
     - The site was designed to provide a nice, fluid and easy navigation. At the top of the page, a clean navigation bar with links to different pages of the website is available.
     - At tablet and mobile, the list of navigation links were replaced by a 'hamburger' button. When clicked, a dropdown of the navigation links will be shown. This feature ensures that the website looks clean at smaller screens but still ensuring accessibility to users.
  3. As a potential customer, I want to learn what crinkles are in order to determine whether this is something I would like to buy.
     - In the home page, a description of crinkle cookies are shown, along with an even more apetizing image of the cookie crinkle.
     - When the user clicks on "Our Crinkles", a description of the flavours of cookie crinkles that the business can offers are listed.
     - In the "Gallery" section, the user can see more images of the crinkles to showcase what crinkles are, show how apetizing it looks and convince the user to buy crinkle cookies.
  4. As a potential or current customer, I want to see a gallery of pictures that crinkles to see how it looks like.
     - As the user clicks on the "Gallery" link in the navigation, a images of crinkles taken by the business are shown. It is repsonsive and can be viewed in tablets and mobile phones.
  5. As a potential or current customer, I want to know my options of buying from crinkle sprinkle such as the flavours available, its cost, where the crinkles can be delivered, and how to place an order.
     - As the user clicks on the "Our Crinkles" link from the navigation bar, the user will be led to a page that describes the flavours available, the price and number of cookie crinkles per order.
     - This page is repsonsive and can be viewed in tablet and mobile. The description goes into one column instead of two columns (picture on one side, description on other side) when screen size is decreased.
     - Information about delivery and catering are available as you scroll down.
     - A link to the "Order Here" section on text that says "get in touch" is available, letting the user order without scrolling back up on the header. Otherwise, the user can click on the "Order Here" from the navigation. This gives the user two options on how to order.
  6. As a potential or current customer, I want to know how I can contact the business.
     - Instagram and email icons which are links to the the accounts of the business are available in the footer to allow the user to contact the business.
     - The "order here" page allows for the user to submit their order as well.
  7. As a potential or current customer, I want to be able to identify the crinklesprinkle tab when I have loads of tabs open on my browser so that I can go back to the website easily.
     - CrinkleSprinkle favicon was used to allow user to distinguish the tab when multiple tabs are open in their browser, which allows for a better user experience.
  8. As a potential or current customer, I want to be able to place my order.
     - The "order here" page allows for the user to submit their order. It was tested by:
       - Go to the "Order Here" page.
       - Try to submit the empty form and verify that an error message about the required fields appears.
       - Try to submit the form with an invalid email address and verify that a relevant error message appears.
       - Try to submit the form with all inputs valid and verify that the user will be navigated to the thank you page, where it will state that CrinkleSprinkle is thanking the user for their order and that the user will be contacted in 24 hours. A list of payment options will also be shown.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository, locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps:

1. At the top of the Repository, above the "Settings" Button on the menu, locate the "Fork" Button.
2. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Under the repository name, click "Clone or download".
2. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
3. Open Git Bash.
4. Change the current working directory to the location where you want the cloned directory to be made.
5. Type `git clone`, and then paste the URL you copied in Step 2.

```
git clone https://github.com/USERNAME/REPOSITORY
```

## Credits

### Code

- The placeholder in the input form in 'Order Here' page was made italic. This [stackoverflow](https://stackoverflow.com/questions/27644314/how-to-make-only-placeholder-italics-in-input) discussion gave me guidance on how to do this and ensured that it will work in all browsers.
- The idea for logo-bounce-animation came from this [article](https://css-tricks.com/making-css-animations-feel-natural/). I then wrote the animation myself.
- The banner-zoom animation came from Code Institute's 'love-running' lectures.

### Content

- All content was written by the developer.

### Media

- The photos used in this site were from the developer.

### Acknowledgements

- My mentor for continuous helpful feedback.
