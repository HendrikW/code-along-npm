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

add styles for the header: 
```css
/* HEADER */
#logo-bar {
    height: 40px;
    padding: 10px 10px;
}

#logo-bar img {
    height: 30px;
}

header {
    background-image: url('./images/city-scape.svg');
    color: white;
    min-height: 300px;
}

header button {
    background-color: orange;
    color: white;
    padding: 10px;
}
```

Add styles for the first two sections: 
```css
/* SECTIONS */
section#npm-orgs img {
    width: 500px;
}

section#npm-orgs {
    color: white;
    background-color: rgb(39, 53, 71);
    min-height: 300px;
}


section#npm-orgs button {
    background-color: rgb(203, 56, 55);
    color: white;
    padding: 10px;
}

section#npm-enterprise {
    color: white;
    background-image: url("images/forklift.svg");
    min-height: 300px;
}

section#npm-enterprise button {
    background-color: rgb(49, 68, 88);
    color: white;
    padding: 10px;
}
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

add styles for the functionality section:
```css
section#functionality {
    color: rgb(83, 88, 98);
}

section#functionality p {
    color: rgb(135, 145, 156);
}

section#functionality a {
    color: rgb(208, 74, 73);
}

.functionality-box {
    max-width: 300px;
    text-align: center;
}
```
