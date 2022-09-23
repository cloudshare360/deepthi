![](cdn-links.png)

in the html head we add these scripts

<script crossorigin src="https://unpkg.com/react@17/umd/react.development.js"></script>
<script crossorigin src="https://unpkg.com/react-dom@17/umd/react-dom.development.js"></script>        <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>

in the body we add

<script src="index.js" type="text/babel"></script>

ReactDOM.render(<p>Hi, my name is Bob!</p>, document.querySelector("#root"))

ReactDOM.render(<h1>Hi, my name is Bob!</h1>, document.getElementByID("root"))

render has two parameters: 
1.what to render
2.where to render
so render is taking first parameter and appending it to root (second parameter).

document.querySelector is another way to tell, where to render.




