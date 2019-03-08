<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=gb2312" />
<title>无提示关闭窗口-鼠标特效代码-网页特效代码-鸿新网—分享不一样的网络资源、让您不再为找资源而烦恼！</title>


</head>
<body onload='setTimeout("mm()",3000)'>  //3000即页面在打开3秒后自动关闭此页面
<script>
function mm()
{
    window.opener=null;
    window.close();
}
</script>
</body>

</html>

