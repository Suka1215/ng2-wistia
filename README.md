# ng2-wistia

For live demo go to [https://ng2-wistia-demo.herokuapp.com/](https://ng2-wistia-demo.herokuapp.com/)
Demo repo: [https://github.com/kibiluzbad/ng2-wistia-demo](https://github.com/kibiluzbad/ng2-wistia-demo)

## Angular2 Wistia Upload and Player

### How to build

```
npm install
node_modules/typescript/bin/tsc
npm run compile
```
### Run tests

```
npm test
```
### Installation

```
npm install ng2-file-upload --save 
npm install https://github.com/kibiluzbad/ng2-wistia.git --save
```
#### Add Bootstrap css

```html
<link  rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" >
```

#### Setup system-config.ts

```js
/** Map relative paths to URLs. */
const map: any = {
   ...
   'ng2-wistia': 'vendor/ng2-wistia',
   'ng2-file-upload': 'vendor/ng2-file-upload',
   ...
};

/** User packages configuration. */
const packages: any = {
    ...
   'ng2-wistia': {
    defaultExtension: 'js'
    },
    'ng2-file-upload':{
    defaultExtension: 'js'
    },
    ...
};
```

#### LICENCE

MIT