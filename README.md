# Creating forms with react-hook-form


### Makes the Application run
```javascript
// using app based on react-app boilerplate
// adding react-hook-form package
npx create-react-app react-hook-form
cd react-hook-form
// using yarn
npm install -g yarn
// we are going to need rbx: https://dfee.github.io/rbx
yarn add rbx
// start yarn
yarn start
// open browser to
open http://localhost:3000/
// open IDE
code .
```


```javascript
// import hooks
import { useForm, ErrorMessage } from "react-hook-form";
```


#### Refs and the DOM
We are going to register our uncontrolled component into the hook, using ref prop.

> Using react-hook-form we have control of the uncontrolled and controlled components, which can provide a better performance.