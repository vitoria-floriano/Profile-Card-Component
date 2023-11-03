# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

### The challenge

- Build out the project to the designs provided

### Screenshot

![](./src/images/project-victor.png)


## My process

- I built the HTML document a few times, until I thought it was good enough for me to work in a simple and effective way. I created the entire document with a certain dynamism, but I had a little difficulty centering the card. So I went by my own logic, which I managed to get results, instead of the default behavior, I researched the positioning of the flexbox in the body tag, and I didn't see anything about it not being semantic, so I believe I have solved the problem.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

The Flexbox showed me that sometimes I have to think outside the box, or create an outer box. This was the line of reasoning that gave me the expected result. In theory, I should put the rules to center the container, in its own selector, but it didn't work, and I thought, this is not where you want to be and work, but I'll make you understand me, so I thought, this box is inside a bigger box, the screen, so I'm going to work on it, the movement happened. I realized that with Flexbox you style what is inside the container, I thought, this container is inside another container, it's simple.

```html
<body>
  <main class="container">
  </main>
</body>
```
```css
/* HERE I HAVE THE RESULT */
body {
  display: flex;
  justify-content: center;
  align-items: center;
}

/* HERE DON'T */
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

### Continued development

I liked thinking this way, it made me realize that I can think about solving a problem, from other points of view, I always apply this in my personal life, but seeing myself in this situation was really cool.
