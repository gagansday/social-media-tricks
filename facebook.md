# Facebook

Step 1: Visit: [https://m.facebook.com/friends/center/requests/outgoing](https://m.facebook.com/friends/center/requests/outgoing)

Step 2: Scroll to the bottom of the page

Step 3: Then Run below script in the console:
 
```javascript
// Cancel friend requests
var inputs = document.getElementsByClassName('_54k8 _56bs _56bt');
	for(var i=0; i<inputs.length;i++) {
	inputs[i].click();
}
```
