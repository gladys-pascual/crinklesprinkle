<h1 align="center">CrinkleSprinkle Website</h1>

[View the live project here.](https://gladys-pascual.github.io/crinklesprinkle/)

CrinkleSprinkle is a homemade cookie crinkle delivery business operating in South Dublin.

The goal of this website is to provide information to promote the business to potential customers.

It is designed to be responsive and accessible on a range of devices, such as PCs, tablets and mobiles, making it easy to navigate for potential customers.

<img src="assets/images/crinkesprinkle.gif">

<br/>
<br/>
<br/>

## User Experience (UX)

- ### User stories
  - As a potential customer, I want to learn about CrinkleSprinkle and determine what the business is about.
  - As a potential or current customer, I want to be able to navigate different pages of the website both by desktop and mobile.
  - As a potential customer, I want to learn what crinkles are in order to determine whether this is something I would like to buy.
  - As a potential or current customer, I want to see a gallery of pictures that crinkles to see how it looks like.
  - As a potential or current customer, I want to know my options of buying from crinkle sprinkle such as the flavours available, its cost, where the crinkles can be delivered, and how to place an order.
  - As a potential or current customer, I want to know how I can contact the business.
  - As a potential or current customer, I want to be able to identify the crinklesprinkle tab when I have loads of tabs open on my browser so that I can go back to the website easily.
  - As a potential or current customer, I want to be able to place my order.
- ### Design
  - #### Colour Scheme
    - The main colour used was a grey hint of pink - #ece4df which gives a modern look on the website.
  - #### Typography
    - The Lato font is the main font used throughout the whole website and Roboto on the main headings and navigation links, with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly.
  - #### Imagery
    - Imagery is important. The large, banner image of baked chocolate cookie crinkles is designed and animated to catch the user's appetite. It has a modern, energetic aesthetic.
    - The logo of CrinkleSprinkle was designed to give a modern aesthetic to the business.
    - The pictures in the gallery section are aimed to showcase the crinkle cookies made by the business, to show potential customers on what to expect.
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

### Header

- Logo of crinklesprinkle.
  - Logo is a link and if clicked, it brings you to the homepage.
- Navigation links (Home, Gallery, Our Crinkles, Contact Us).
  - Allows for navigation to different pages of the website.
- To create a modern look in desktop, logo and navigation links are placed in the opposite sides of the page.
- To ensure responsiveness, media queries was used where the navigation links were replaced by a 'hamburger' button. When clicked, a dropdown of the navigation links will be shown.
- - For example, when a link is hovered, an animation, background change or a variety style change is applied to let the user know that it is a clicakble link.

### Footer

### Home

### Our Crinkles

### Gallery

### Order Here

### Thank you

### Frameworks, Libraries & Programs Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)
  - Flexbox was mainly used to create the website responsive on all devices such as PCs, tablets and mobiles.
- [Google Fonts:](https://fonts.google.com/)
  - Google fonts were used to import the 'Titillium Web' font into the style.css file which is used on all pages throughout the project.
- [Font Awesome:](https://fontawesome.com/)
  - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
- [Git](https://git-scm.com/)
  - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
- [GitHub:](https://github.com/)
  - GitHub is used to store the projects code after being pushed from Git.
- [Virtual Studio Code](https://code.visualstudio.com/)
  - Virtual studio code was used to write the code.
  - [![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier) Prettier, a VS code extension, was used to automatically format the code as it is saved to mitigate code errors.
- [Balsamiq:](https://balsamiq.com/)
  - Balsamiq was used to create the [wireframes](assets/wireframe/crinklesprinkle_wireframe.pdf). during the design process.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

- [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)

- When first deployed, images won't appear. used chrome developer tools, figured out that I wrote the file path incorrectly by putting a / before the file path.
- Fix error where div is inside a ul, found using validator.w3.org.
- The element a must not appear as a descendant of the button element. Removed button, no need for a button. Just styled the link as a button. no JS required yet so button not needed.
- corrected form error. type=same as name, changed to type=text

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
   1. Go to the "Contact Us" page
   2. Try to submit the empty form and verify that an error message about the required fields appears
   3. Try to submit the form with an invalid email address and verify that a relevant error message appears
   4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

1. Home

- Logo

2. Gallery

- used chrome developer tools extensively to ensure alignment, margin/padding that I wasn't aware of.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
   - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Content

- All content was written by the developer.

### Media

- The photos used in this site were from the developer.

### Acknowledgements

- Make placeholder italic and make sure it works in all browsers
  https://stackoverflow.com/questions/27644314/how-to-make-only-placeholder-italics-in-input

- Got the idea of logo-bounce-animation from this article: https://css-tricks.com/making-css-animations-feel-natural/ and created the bounce animatiton myself.

- banner-zoom animation was from love-running lecture in code institute.

- accessibility - added alt on images, and on <i> aria hidden true, added sr-only class and add description of the icon.
