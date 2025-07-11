# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
# my-react-portfolio

For my project, the AI that I used was ChatGPT, When I originally tried to use the react-routing-dom in my project (when I was using snowpack), I was experiencing errors that I couldn't debug no matter what.

I asked ChatGPT what the error "No Default found" meant, and after it guided me towards making show my imports were correct (they were), StackOverflow didn't have any questions about it, and google didn't seem to understand as well. 

Because of this, and going around in circles; I asked:

"How can I restart this project?"

ChatGPT suggested using Vite instead of snowpack, I then looked on google to find out how to implement vite into my project to replace snowpack, and now my project is running on it. Because of Chatgpt suggesting using Vite in place of snowpack, I was able to get passed the issue. 

Till now, I still do not understand why the library was unavailable using snowpack, but now i've learned another method to use, and I will continue to use vite whenever I do deploy a react project.
