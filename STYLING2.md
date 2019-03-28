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
