# React

### Source:

[Getting Started - React](https://reactjs.org/docs/getting-started.html)

[Tutorial: Intro to React - React](https://reactjs.org/tutorial/tutorial.html)

---

```jsx
class ShoppingList extends React.Component {
  render() {
    return (
      <div className="shopping-list">
        <h1>Shopping List for {this.props.name}</h1>
        <ul>
          <li>Instagram</li>
          <li>WhatsApp</li>
          <li>Oculus</li>
        </ul>
      </div>);
  }
}

// Örnek kullanım: <ShoppingList name="Mark" />

// ShoppingList is a React component class
// ShoppingList, React bileşen sınıfıdır

```

props → properties (özellikler)

<aside>

📌 Bir React bileşeni, `props` isimli parametreleri alır, ve arayüzü görüntülemek amacıyla `render`metodundan geriye bir görünüm hiyerarşisi (XML kodu) döndürür.

</aside>

---