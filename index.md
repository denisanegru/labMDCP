<script> 
  document.cookie = "session=test GDPR"; 
  document.cookie = "favorite_task=collect Data"; 
  function alertCookie() { alert(document.cookie); 
  } 
</script>
<body> Bine ai venit la lab <button onclick="alertCookie()">Show cookies</button> 
</body>
<button onclick="alertCookie()">Show cookies</button>
document.cookie = "session=test GDPR";
document.cookie = "favorite_task=collect Data";

const cookieValue = document.cookie
  .split('; ')
  .find(row => row.startsWith('test2='))
  .split('=')[1];

function alertCookieValue() {
  alert(cookieValue);
}
<button onclick="alertCookieValue()">Show cookie value</button>

function doOnce() {
  if (!document.cookie.split('; ').find(row => row.startsWith('doSomethingOnlyOnce'))) {
    alert("Do something here!");
    document.cookie = "doSomethingOnlyOnce=true; expires=Fri, 31 Dec 9999 23:59:59 GMT";
  }
}
<button onclick="doOnce()">Only do something once</button>
function resetOnce() {
  document.cookie = "doSomethingOnlyOnce=; expires=Thu, 01 Jan 1970 00:00:00 GMT";
}
<button onclick="resetOnce()">Reset only once cookie</button>
