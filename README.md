# html
&lt;html> &lt;head>   &lt;title>Change bg color every 1 seconds&lt;/title> &lt;/head> &lt;body> &lt;h1>Background Color is being changed every 1 seconds&lt;/h1> &lt;script> setInterval( function () {   var randomColor = Math.floor(Math.random()*16777215).toString(16);   document.body.style.backgroundColor = "#"+randomColor; },1000); &lt;/script> &lt;/body> &lt;/html>
