Step 1: Visit: https://www.instagram.com/accounts/access_tool/current_follow_requests

Step 2: Scroll to the bottom of the page

Step 3: Then Run below script in the console:
 
```javascript
document.querySelectorAll('.-utLf').forEach((e) => {
	e.innerHTML = `<a target="_blank" href="https://www.instagram.com/${e.innerText}">${e.innerText}</a>`;
}); 
```
Step 4: Control-click each of the link then click on the request cancel button
