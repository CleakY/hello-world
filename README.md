# hello-world
just practise
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title></title>
    <script src="jquery-3.3.1.min.js" type="text/javascript" charset="utf-8"></script>
    <script src="jquery-migrate-1.0.0.js"></script>
    <script type="text/javascript">
$(function () {
    $("#btn").toggle(function () {
     $("#btn2").css("backgroundColor","red")
    },function () {
        $("#btn2").css("backgroundColor","blue")
    })
})
function ff() {
    setTimeout("1000");
    alert("sss")
}
    </script>
</head>
<body>
<input id="btn" type="button" value="使用on绑定点击事件">
<input id="btn2" type="button" value="使用off解绑点击事件" onclick="ff">
</body>
</html>
