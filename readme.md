<h1 align="center">
	<br>
	<img width="360" src="media/logo.png" alt="battery-level">
	<br>
	<br>
</h1>

> Get current battery level


## Install

```
$ npm install battery-level
```


## Usage

```js
const batteryLevel = require('battery-level');

(async () => {
	console.log(await batteryLevel());
	//=> 0.55
})();
```


## API

### batteryLevel()

Returns a `Promise<number>` with the battery level.


## Related

* [battery-level-cli](https://github.com/gillstrom/battery-level-cli) - CLI for this module
* [browser-battery](https://github.com/gillstrom/browser-battery) - Get battery information in a browser
* [is-charging](https://github.com/gillstrom/is-charging) - Find out if a computer is charging
