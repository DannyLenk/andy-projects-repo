# Standard README.md File

![Design preview for the Space tourism website coding challenge](./assets/preview.jpg)

## Welcome! 👋
## Table of contents

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- CSS utility classes


### What I learned

1) the way to make a copy of a DOM element with its children

```js
let someObj = {
      createNewRow: function() {
      const tBody = document.querySelector('#tBody');
      const expenseRow = document.querySelector('.output__tr');

      tBody.appendChild(expenseRow.cloneNode(true));
   }
}
```

2) learned to fit content in one or two even columns
```css
div {
   border: 1px solid #CDCDCD;
   min-width: 40%;
   flex: 1 1 0;
   margin-bottom: .5em;
   text-align: left;
   padding: .5em;
}
```

### Continued development

* CSS grid;

*Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

### Useful resources

- [Find li index](https://stackoverflow.com/questions/18295673/javascript-find-li-index-within-ul) - This helped me build the To-Do app.
- [Data from form to table](https://stackoverflow.com/questions/18295673/javascript-find-li-index-within-ul) - Has the answer how to do it with the plain JS.
- [remove item from HTML collection](https://stackoverflow.com/questions/37311003/how-to-remove-an-item-from-htmlcollection) - Helped with the expense-tracker.
- [Indexes Search By Clicking](https://stackoverflow.com/a/23528539/16906724) - finally this helped me figure out the way to fetch an index of an element or its relatives by clicking on it.


- [Git + GitHub](https://www.youtube.com/watch?v=RGOj5yH7evk) - the basic git commands (Youtube).
- [The Markdown Guide](https://www.markdownguide.org/) - for more help with writing markdown (Article).

## Author

- Github - [DannyLenk](https://github.com/DannyLenk)
- Frontend Mentor - [@DannyLenk](https://www.frontendmentor.io/profile/DannyLenk)
- Facebook - [Valerii Danylenko](https://www.facebook.com/valerii.danylenko)
- LinkedIn - [Valerii Danylenko](https://www.linkedin.com/in/valerii-danylenko-74379212b)
- insta - [valeriidanylenko](https://www.instagram.com/valeriidanylenko/?hl=ru)

## Acknowledgments

Thank you, Kevin Powell. Hats off to you and your clear English.