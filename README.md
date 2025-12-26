# love
Html

<!DOCTYPE html>

<html>

<head>

<meta charset="UTF-8"> <title>给你的话</title> <style>

body {text-align:center; font-family:sans-serif;

background:#ffe6f0; }

button { font-size:18px;

padding:10px 20px;

margin:20px; }

</style>

</head>

<body>

<h1>我喜欢你</h1>

<button onclick="like()">喜欢</ button>

<button onclick="dislike()">T </button>

document.body.innerHTML =

<script>

function like(){

"<h1> 接受啦!我们在一起吧 </h1>";

}

function dislike(){

alert("你选择了拒绝");

history.back();

}

</script>

</body>

</html>
