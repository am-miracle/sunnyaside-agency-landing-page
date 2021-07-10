# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Sunnyside agency landing page solution](#frontend-mentor---sunnyside-agency-landing-page-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Javascript


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

i learnt how to effectively make use of flexbox and grid, which i was struggle to learn after some practices i finally learnt it (lol).

To see how you can add code snippets, see below:

```html
    <section class="card3">
      <div class="straw-wrapper">
        <div class="img-wrapper">
          <img src="/images/mobile/image-graphic-design.jpg" alt="" class="mobile">
          <img src="/images/desktop/image-graphic-design.jpg" alt="" class="desktop">
        </div>
        <div class="card3-text text2">
          <h2>Graphic design</h2>
          <p class="graphic-text">Great design makes you memorable. We deliver artwork that underscores your brand message and captures potential clients’ attention.</p>
        </div>
      </div>

      <div class="orange wrapper">
        <div class="img-wrapper">
          <img src="/images/mobile/image-photography.jpg" alt="" class="mobile">
          <img src="/images/desktop/image-photography.jpg" alt="" class="desktop">
        </div>
        <div class="card3-text text3">
          <h2>Photography</h2>
          <p>Increase your credibility by getting the most stunning, high-quality photos that improve your business image.</p>
        </div>
      </div>
    </section>h1>
```

```css
.bar.open{
  background: var(--White);
  color: var(--Very-dark-grayish-blue);
  list-style: none;
  padding: 2em;
  width: 300px;
  display: block;
  position: relative;
  margin-left: auto;
  margin-right: auto;
}
```

```js
    const hamburger = document.querySelector(".hamburger");
    const bar = document.querySelector(".bar");
    const bars = document.querySelectorAll(".bar li");

    hamburger.addEventListener("click" , () => {
      bar.classList.toggle("open");
  });
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.


### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

I will continue to improve in my skills and learn more on javascript.
I will work more on building responsive navigation bar.

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@andreas-15](https://www.frontendmentor.io/profile/andreas-15)
- Twitter - [@Dare_devs](https://www.twitter.com/Dare_devs)
- codepen - []


## Acknowledgments

Acknowledgments go to myself, for pushing myself to improve and grow in tech from what i have learnt so far. As a newbie this is the first big project i built on my own without watching any Youtube video or reading an article even checking from goggle apart from the javascript code for mobile navigation bar , which was difficult for me.

