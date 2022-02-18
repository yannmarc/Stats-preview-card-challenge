# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

### Screenshot

![ challenge screenshot ](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [ The solution URL over here ](https://github.com/yannmarc/Stats-preview-card-challenge)
- Live Site URL: [ Live site URL here](https://compassionate-meninsky-a1e19d.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox
- Mobile-first workflow

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
 <section id="text">
        <div class="text-container">
          <h1 role="heading" class="heading">Get <span  class="span-voilet">insights</span> that help your business grow.</h1>
        <p class="p-2 "> Discover the benefits of data analytics and make better decisions regarding revenue, customer experience, and overall efficiency.</p>
        <div class="stats-section">
          <div class="stat">
            <p class="text-mid" aria-label="stats" >10k+</p>
            <p>companies</p>
          </div>
          <div class="stat">
            <p class="text-mid" aria-label="stats">314</p>
            <p>templates</p>
          </div>
          <div class="stat">
            <p class="text-mid" aria-label="stats">12m+</p>
            <p> queries </p>
          </div>
        </div>
        </div>
      </section>
```
```css

#img {
    width: 100%;
    height: 100%;
    order: 1;
    position: relative;
}

#img::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: var(--so-voilet);
    opacity: 0.7;
}

```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.



### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

#### Concetpz i would like to focus regarding future projects

* CSS Grid
* CSS preprocessors
* CSS media queries
* CSS matrix property



### Useful resources

- [w3schools](https://www.example.com) - This helped me in remembering the principles behind flexbox in CSS. It was so helpfull to me and I learned alot.
- [Freecodecamp](hhtps://www.freecodecamp.org) - This is an amazing resource website that teaches you the fundamentals of HTML & CSS coupled with Javascript.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Frontend Mentor - [@yannmarc](https://www.frontendmentor.io/profile/yannmarc)
- Twitter - [@yannmarc](https://www.twitter.com/yannmarc)
