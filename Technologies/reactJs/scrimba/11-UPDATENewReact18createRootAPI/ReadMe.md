ReactDOM.render is no longer supported in React 18. Use createRoot instead. Until you switch to the new API, your app will behave as if it's running React 17. Learn more: https://reactjs.org/link/switch-to-createroot

changes to do from react version 18:
1. import ReactDOM from "react-dom/client"
2. instead of render take two parameters
ReactDOM.render(what, where)
a.create a root first
b.use that root to render what you want(one steps or 2 steps)

**ReactDOM.render(navbar, document.getElementById("root"))**

**ReactDOM.createRoot(document.getElementById("root")).render(navbar)**

or

**const root = ReactDOM.createRoot(document.getElementById("root"))
root.render(navbar)**

