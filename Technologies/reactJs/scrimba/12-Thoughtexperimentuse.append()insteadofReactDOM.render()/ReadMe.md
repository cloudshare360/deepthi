JSX returns plain javascript objects, it has nothing to do with DOM, browser doesnot recognize it.
only when we try to render it using reactDOM.render, it takes these js objects and turn then into real DOM elements that the browser can interpret as things like headers, paragraph etc....

so ReactDOM.render job is to take jsx elements, and interpret them into real DOM elements that browser can understand


