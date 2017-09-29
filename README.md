# Babel webpack example

To run the example first setup your AWS configuration.

```js
// src/config.js
export default {
  region: '',
  IdentityPoolId: '',
  UserPoolId: '',
  ClientId: '',
}
```

Now, you are ready to build this example.

```
npm install
npm run build
npm start // to start local dev server
```

Open browser to try this example.

```
open index.html
```
