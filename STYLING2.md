# Add some positioning to your page :-)

positioning the middle section:
```css
section#npm-orgs {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    padding: 50px 20px;

    color: white;
    background-color: rgb(39, 53, 71);
    min-height: 300px;
}

section#npm-orgs img {
    width: 300px;
}

@media (min-width: 786px) {
    section#npm-orgs img {
        width: 500px;
    }
}
```

position the last section:
```css
section#functionality {
    color: rgb(83, 88, 98);
    text-align: center;
    padding: 30px 80px;
}

section#functionality p {
    color: rgb(135, 145, 156);
}

section#functionality a {
    color: rgb(208, 74, 73);
}

#functionality-container {
    margin-top: 60px;

    text-align: center;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}
```

add a `description` class:
```html
...
<div class="description">
    <h1>Build amazing things</h1>
...            
```
```html
...
<div class="description">
    <h2>npm Enterprise</h2>
...            
```
