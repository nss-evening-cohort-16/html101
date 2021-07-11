# html101

We will be create a multipage website using HTML, CSS, and Bootstrap

## Files
### HTML Pages
- index.html
- javascript.html
- css.html
- html.html

### CSS
- main.css

### JS
- main.js

## Bootstrap
Go to [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/) and to all the setup.

### Items we are using from boostrap
- [Navbar](https://getbootstrap.com/docs/5.0/components/navbar/)
- [`container`](https://getbootstrap.com/docs/5.0/layout/containers/) css class


## Refactor
Instead of hard coding the HTML cards, let's us the object JS data structure to create our data and then loop through the data adding the cards dynamically to the DOM.

Let's also get rid of all the pages and use buttons and click events to filter the data so that only the relevant topics show on the DOM.

```javacript
document.querySelector('SELECTOR').addEventListener('click', (e) => console.warn(e))
```
