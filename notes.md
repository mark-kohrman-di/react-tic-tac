APP.JS

The code in App.js creates a component. In React, a component is a piece of reusable code that represents a part of a user interface. Components are used to render, manage, and update the UI elements in your application.

index.js

You won’t be editing this file during the tutorial but it is the bridge between the component you created in the App.js file and the web browser.

Fragments

- <></> wrappers to wrap multiple elements

Componentes must start with a capital letter e.g. <Square />

The componenet Square can be passed a value prop by inserting as an "argument" with curly braces
e.g. `function Square({ value })`

To pass `value` in the function you need curly braces
e.g. `return <button className="square">{value}</button>`

git init
git add .
git commit -m "add tic tac toe react project"
git remote set-url origin git@github.com:mark-kohrman-di/tic-tac-toe-react.git
git push origin main
