# Model-Server

Pre-trained models for browser-side ML, mainly TensorFlow.js.

## Usage

Access models at  
`https://rebo-85.github.io/Model-Server/path/to/model/model.json`

Example:

```js
const beautyModel = await tf.loadLayersModel("https://rebo-85.github.io/Model-Server/beauty_predict/model.json");
```

See [Web Server](https://rebo-85.github.io/Model-Server/) for model lists.
