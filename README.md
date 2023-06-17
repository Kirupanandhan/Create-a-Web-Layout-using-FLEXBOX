# Ex-03-Create-a-Web-Layout-using-FLEXBOX
## Aim:-
To Create-a-Web-Layout-using-FLEXBOX
## Algorithm:-
### Step 1:
Set up the HTML structure
### Step 2:
Define the container styles
### Step 3:
Style the flex items
### Step 4:
Apply Flexbox properties
### Step 5:
Customize and expand the layout
### Step 6:
Publish your FLEXBOX
## Program:-
```html
<!doctype html>
<title>Example</title>
<style>
  * {
   box-sizing: border-box; 
  }
  body {
    margin: 0;
  }
  #main {
    display: flex;
    min-height: calc(100vh - 40vh);
  }
  #main > article {
    flex: 1;
  }
  #main > nav, 
  #main > aside {
    flex: 0 0 20vw;
    background: beige;
  }
  #main > nav {
    order: -1;
  }
  header, footer, article, nav, aside {
    padding: 1em;
  }
  header, footer {
    background: yellowgreen;
    height: 20vh;
  }
</style>
<body>
  <header>Header</header>
  <div id="main">
    <article>Article</article>
    <nav>Nav</nav>
    <aside>Aside</aside>
  </div>
  <footer>Footer</footer>
</body>
```
## Output:-
![image](https://github.com/Kirupanandhan/Create-a-Web-Layout-using-FLEXBOX/assets/94386222/53a3a7e4-5e65-45f7-b416-2a174cba9185)
## Result:-

Thus the program to Created a Web Layout using FLEXBOX successfully.

