# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Add solution URL here](https://github.com/Reykjabik/3-column-card-preview-frontendmentor)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

In this exercise I have really noticed some 'fluency' in HTML and CSS. This is the first project I tried to do in Frontendmentor, but I struggled a lot and postponed it untill I had gained some more theory. In this second attempt a week later I found it much easier. More than a challenge, this time it felt just like an exercise.

I have learnt here about the outline property in CSS.

```css
button:active {
	background-color: rgba(0, 0, 0, 0);
	outline: 2px solid var(--lg-gray);
	color: var(--lg-gray);
}
```

When I first approached this, I used the property *border*. What it did is to increase the height of the button, and therefore the whole section. This looked pretty bad, taking into account that the other two sections didn't grow. Trying to look for an option to have some sort of *inner border*, I found this *outline* property.

### Continued development

I still need to get more comfortable with Flexbox. I do know the theory, but when it comes to using it I start twisting my head trying to better understand how to place things on the main/cross axes. Especially I need to work on the align-items and align-content difference, since I still don't clearly see it.

Another thing in my to-do list is cleaner CSS. I do create variables, but I end up using them a lot all over the file. I feel that I still have a few redundant lines that I could group in a different and tidier way.

### Useful resources

- [CSS Tricks](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - The page that I keep open for every project so far, since it is a very condensed but useful Flexbox bible.

## Author

- Frontend Mentor - [@Reykjabik](https://www.frontendmentor.io/profile/Reykjabik)