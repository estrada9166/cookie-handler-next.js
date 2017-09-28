# Cookie Handler for server render with Next.js

## Main Idea
The main idea behind this example is to handle the cookies when the view is render on the server side. Because on the server side it can't be something like `document.cookie` because it can't access to the `document` so the idea is to have a middleware on the server of `Next.js` that will get the cookie and set it in `res.locals` making it accessible from the view with `static getInitialProps({ res })`

## How it works

```
Clone the repo

npm install
npm run dev
```
