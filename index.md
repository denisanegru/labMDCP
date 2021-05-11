<script> 
  document.cookie = "session=test GDPR"; 
  document.cookie = "favorite_task=collect Data"; 
  function alertCookie() { alert(document.cookie); 
  } 
</script>
<body> Bine ai venit la lab <button onclick="alertCookie()">Show cookies</button> 
</body>
document.cookie = "test1=Hello";
document.cookie = "test2=World";

const cookieValue = document.cookie
  .split('; ')
  .find(row => row.startsWith('test2='))
  .split('=')[1];

function alertCookieValue() {
  alert(cookieValue);
}
<button onclick="alertCookieValue()">Show cookie value</button>
