## Day 1 of React

# Today i learnt following things:

1. How to create react app using vite

code :  npm create vite@latest

2. a_react\index.html is displayed on the browser which have div with id="root"

 <div id="root"></div> 

3. a_react\src\main.tsx controls the content of root in index.html

ReactDOM.createRoot(document.getElementById('root') as HTMLElement).render(
  <React.StrictMode>
    <App />
  </React.StrictMode>,
)

4. i learnt how to make changes in app.tsx file . 
- install bootstrap in the project
- use bootstrap in app (list-group)

