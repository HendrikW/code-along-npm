# code-along-npm

## The structure

Basic HTML setup:
```html
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>NPM site</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" type="text/css" media="screen" href="main.css">
</head>

<body>
</body>

</html>
```

Navbar as first element in `<body>`:
```html
<nav>
    <div class="top-left">
        <a class="heart" href="#">♥︎</a>
        <span class="acronym">Neophobe Plebeian Mumpsimus</span>
    </div>
    <ul class="top-links">
        <li><a href="#">npm Enterprise</a></li>
        <li><a href="#">features</a></li>
        <li><a href="#">pricing</a></li>
        <li><a href="#">documentation</a></li>
        <li><a href="#">support</a></li>
    </ul>
</nav>
```

Header section:
```html
<header>
    <div>
        <img id="logo" src="images/npm-logo.png">
    </div>
    <img src="images/city-scape.svg">
    <div>
        <h1>Build amazing things</h1>
        <p>Essential JavaScript development tools that help you go to market faster and build powerful applications
            using modern open source code.</p>
        <button>Sign up for npm</button>
    </div>
</header>
```

Organizations section:
```html
<section id="npm-orgs">
    <img src="images/collaboration.svg">
    <div>
        <h2>Bring the best of open source to your company</h2>
        <ul>
            <li>Zero configuration</li>
            <li>Team management</li>
            <li>Familiar features</li>
        </ul>
        <button>Create an org</button>
    </div>
</section>
```

Enterprises section:
```html
<section id="npm-enterprise">
    <img src="images/forklift.svg">
    <div>
        <h2>npm Enterprise</h2>
        <p>You need to get quality products to market fast but you also need enterprise-grade security and
            compliance.
            Speed up development while also upgrading to the most advanced tooling in JavaScript, from the trusted
            authorities on JavaScript package management.</p>
        <button>learn more</button>
    </div>
</section>
```

Functionalities section:
```html
<section id="functionality">
    <div>
        <h2>JavaScript. Enterprise grade.</h2>
        <p>Bring your development under one roof, and get a handle on your company’s open source footprint with our
            secure, single-tenant, managed service. npm Enterprise empowers developers to do what they do best while
            providing you with industry-leading administrative capabilities. Reduce risk while reducing friction.
        </p>
        <div id="functionality-container">
            <div>
                <img src="images/binoculars.svg">
                <h6>Security expertise</h6>
                <p>npm is the central authority on JavaScript security. Automatically find and fix security
                    vulnerabilities before they ever make it into production, with nothing to set up or install.</p>
            </div>
            <div>
                <img src="images/mountain-flag.svg">
                <h6>De-duplicated development</h6>
                <p>npm’s search and distribution features have revolutionized the way developers collaborate.
                    Unlimited
                    namespaces allow your teams to easily share and manage their code.</p>
            </div>
            <div>
                <img src="images/backpack.svg">
                <h6>Access control</h6>
                <p>Single sign-on gives you total control of who has access to your system, allowing you to
                    distribute
                    permissions in a way that matches your company structure.</p>
            </div>
        </div>
    </div>
</section>
```
