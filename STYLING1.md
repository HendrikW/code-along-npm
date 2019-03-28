# The first styles get applied

In `main.css` add 
```css
/* NAV */
nav {
    background-color: #C12127;
    color: rgba(255, 255, 255, 0.8);
    padding-top: 15px;
    padding-left: 15px;
    padding-right: 15px;
    height: 60px;
}

nav a {
    color: rgba(255, 255, 255, 0.8);
    text-decoration: none;
}

.top-links {
    float: right;
    padding: 0;
}

.top-links li {
    display: inline-block;
    margin: 0 10px;
}
```

In your `index.html` add (before your own css file!)
```html
<link rel="stylesheet" type="text/css" media="screen" href="bootstrap-reboot.css">
```
