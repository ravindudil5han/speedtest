## USAGE

```

const testSpeed = require('./main.js');

testSpeed().then((result) => {

  console.log(`Download speed: ${result.downloadSpeed} MB/s`);

  console.log(`Elapsed time: ${result.elapsedTime} seconds`);

}).catch((err) => {

  console.error(err);

});
```
