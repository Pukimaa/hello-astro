# 👋 `hello-astro`
[Take a look at the demo](https://hello-astro.vercel.app/)
This is a component that returns a random greeting in a random language...nothing more.

## ✨ Usage
```js
---
import { HelloAstro } from "hello-astro";
---
<h3>This is a random greeting:</h3>
<h1><Component.HelloAstro /></h1>

```
Please note that there is no element surrounding the greeting so you need to add one yourself
## ❌ Something's missing or wrong?
Please create a PR and follow these rules:
- The translation should be just "Hello"
- It should be the informal hello
- Just create a new Array Value in the `greetings.js` like the following:
    - `"Hello in Language X", // Language X Name`
