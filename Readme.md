## Boostrap Grid Debugger

![Preview](https://raw.githubusercontent.com/Chandu4221/bootstrap-grid-debugger/aebc68df7c09c30e96b6f0abc6426f70b56d76de/readme_files/bootstrap-grid-preview.gif)

### Usage

usage with plain HTML through CDN

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/npm/@dchandrashekhar/bootstrap-grid-debugger@1.0.6/dist/index.css"
/>
```

```html
<body class="grid for-container container">
  <!-- add `grid` and `for-container` classes here  -->
  ...
</body>
```

---

### Usage

usage with React.js, Vue.js

```javascript
import "@dchandrashekhar/bootstrap-grid-debugger/dist/index.css";
```

to debug `bootstrap container` add these classes to container `grid for-container`

```javascript
import "@dchandrashekhar/bootstrap-grid-debugger/dist/index.css";
import "bootstrap/dist/css/bootstrap.min.css";

function App() {
  return (
    // added grid for-container class here
    <div className="container grid for-container">
      <div className="row">
        <div className="col-xxl-2 col-xl-3 col-lg-4 col-md-6 col-sm-8">
          <div className="card bg-primary text-white">
            <div className="card-body">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed
              viverra vitae lorem ac cursus. Praesent sagittis non dolor vitae
              aliquet. Sed vel maximus diam. Nullam ullamcorper vitae urna sed
              gravida. Donec condimentum metus orci. Nam elementum dui id dolor
              vehicula vestibulum. Aliquam ac felis est.
            </div>
          </div>
        </div>
      </div>
    </div>
  );
}

export default App;
```

# XXL (col-xxl-2)

![](https://raw.githubusercontent.com/Chandu4221/bootstrap-grid-debugger/aebc68df7c09c30e96b6f0abc6426f70b56d76de/readme_files/XXL.png)

# XL (col-xl-3)

![](https://raw.githubusercontent.com/Chandu4221/bootstrap-grid-debugger/aebc68df7c09c30e96b6f0abc6426f70b56d76de/readme_files/XL.png)

# LG (col-lg-4)

![](https://raw.githubusercontent.com/Chandu4221/bootstrap-grid-debugger/aebc68df7c09c30e96b6f0abc6426f70b56d76de/readme_files/LG.png)

# MD (col-md-6)

![](https://raw.githubusercontent.com/Chandu4221/bootstrap-grid-debugger/aebc68df7c09c30e96b6f0abc6426f70b56d76de/readme_files/MD.png)

# SM (col-sm-8)

![](https://raw.githubusercontent.com/Chandu4221/bootstrap-grid-debugger/aebc68df7c09c30e96b6f0abc6426f70b56d76de/readme_files/SM.png)

---

Similarly to debug `bootstrap container-fluid` add these classes to container `grid for-container-fluid`

Made with ❤
