what is react creating with JSX?
java script objects . theses objects represent the dom element that we want react to put on the page for us.

jsx is like a function which when runs, returns us object, that react can interpret and is used to create the actual element ( it can put on scrren for us can return only one parent element.)
-if required to return 2 elements wrap them in a parent element as follows
ReactDOM.render(
    <div>
        <h1 className="header">This is JSX</h1>
        <p>This is a paragraph</p>
    </div>,
    document.getElementById("root")
)

you can save a whole collection of elements as a variable
