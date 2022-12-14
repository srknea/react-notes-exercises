```html
<!-- We will put our React component inside this div. -->
<div id="like_button_container"></div>
```

```jsx
/*These three lines of code find the <div>, create a React app with it, 
and then display our “Like” button React component inside of it.*/

const domContainer = document.querySelector('#like_button_container');
const root = ReactDOM.createRoot(domContainer);
root.render(e(LikeButton));
```

---

### Source:

[Add React to a Website](https://reactjs.org/docs/add-react-to-a-website.html)