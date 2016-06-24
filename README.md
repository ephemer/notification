# iOS Native Style Alerts

Native alerts and confirm boxes for cordova and a carefully styled browser version (blaze).

## Import

```
import { notification } from 'flowkey:notification';
```

### notification.alert

```js
flow.notification.alert({
	message: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore.',
	title: 'This is a test Message',
	callback: function(){}
});
```


### notification.confirm
```js
flow.notification.confirm({
	message: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore.',
	title: 'This is a test Message',
	callback: function(index){}, // index(String) conforms with the buttonLabels index counting from 1 - same for ios
	buttonLabels: ['Ok', 'Not now']
});
```