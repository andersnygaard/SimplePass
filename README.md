<h3>Bookmarklet</h3>
Add this to your bookmarks toolbar
<a href="javascript:(function()%7Bdocument.activeElement.value%20%3D%20btoa(encodeURIComponent(prompt(%22Please%20enter%20your%20personal%20password%22%2C%20%22%22)%20%2B%20window.location.hostname).replace(%2F%25(%5B0-9A-F%5D%7B2%7D)%2Fg%2C%20function(match%2C%20p1)%20%7Breturn%20String.fromCharCode('0x'%20%2B%20p1)%3B%7D))%7D)()">SimplePass</a>

<br>
<br>
Test it here:<br>
<input type="text"/>
