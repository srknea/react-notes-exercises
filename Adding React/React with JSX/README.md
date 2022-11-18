Source: [Optional: Try React with JSX](https://reactjs.org/docs/add-react-to-a-website.html#optional-try-react-with-jsx)

---

React’e ne göstereceğini söylemek için bir JavaScript fonksiyon çağrısı kullanma:

```jsx
const e = React.createElement;

// Bir "Like" <button>'u göster
return e(
  'button',
  { onClick: () => this.setState({ liked: true }) },
  'Like'
);
```

Yukarıdaki kod parçası tarayıcılar tarafından doğal olarak desteklenen özelliklere riayet ederek oluşturulmuştur.

---

React’de JSX kullanma seçeneği de mevcuttur:

```jsx
// Bir "Like" <button>'u göster
return (
  <button onClick={() => this.setState({ liked: true })}>
    Like
  </button>
);
```

Bu iki kod parçacığı eşdeğerdir.  Fakat hem React’i hem de diğer kütüphaneleri kullanan birçok kişi, kullanıcı arayüzü kodu yazmak için JSX’i yararlı bulmaktadır.