[![build status](https://secure.travis-ci.org/crcn/beanpoll-twilio.png)](http://travis-ci.org/crcn/beanpoll-twilio)

## Example

```javascript
var beanie = require('beanie');

beanie.
loader().
params({
	'hostname': 'mysite.com',
	'beanpoll-twilio': {
		accountSid: 'SID HERE',
		auth_token: ''
		phoneNumbers: {
			'craig': '+16269239971',
			'john':  '+11643280333'
		}
	}
})
require('beanpoll-twilio').
require('my-custom-plugin').
load();
```


```javascript
```