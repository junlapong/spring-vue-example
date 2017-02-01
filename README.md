Spring Boot Vue Example
=======================

A Vue.js version of this example ( https://github.com/winterbe/spring-react-example ).

The `CommentBox` main view is isomorphic: HTML is initially rendered on the server with Nashorn by utilizing `renderToString`. All interactive DOM manipulations are handled by Vue.js directly in the browser.

### vue-devtools
https://github.com/vuejs/vue-devtools

### How to launch

```sh
mvn spring-boot:run
```

### How to build JavaScript

```sh
npm install

npm run build
```
