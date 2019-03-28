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

Give an ID to the `div` around the logo:
```html
<div id="logo-bar">
    <img src="images/npm-logo.png">
</div>
```

Give IDs and classes to the `div`s in the functionality-section: 
```html
<div id="functionality-container">
    <div class="functionality-box">
        <img src="images/binoculars.svg">
        <h6>Security expertise</h6>
        <p>npm is the central authority on <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">JavaScript</a> security. Automatically find and fix security
            vulnerabilities before they ever make it into production, with nothing to set up or install.</p>
    </div>
    <div class="functionality-box">
        <img src="images/mountain-flag.svg">
        <h6>De-duplicated development</h6>
        <p>npm’s search and distribution features have revolutionized the way developers collaborate.
            Unlimited
            namespaces allow your teams to easily share and manage their code.</p>
    </div>
    <div class="functionality-box">
        <img src="images/backpack.svg">
        <h6>Access control</h6>
        <p>Single sign-on gives you total control of who has access to your system, allowing you to
            distribute
            permissions in a way that matches your company structure.</p>
    </div>
</div>
```
