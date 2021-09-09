<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
    	/*通过给td设置高度和宽度，进而确定每一行高度*/
        td {
            width: 80px;
            height: 50px;
        }
        caption {
            font-size: 28px;
            margin-bottom: 10px;
        }
        /*需填内容较多时设置高度*/
        .body td {
            height: 150px;
        }
    </style>
</head>
<body>
    <table border="1" cellspacing="0" width=“650” align="center">
        <caption>个人简历</caption>
        <tr align="center">
            <td>姓名</td>
            <td>罗洁</td>
            <td>性别</td>
            <td>女</td>
            <td>出生年月</td>
            <td>2001-06-28</td>
            <td colspan="2" rowspan="4"></td>
        </tr>
        <tr align="center">
            <td>祖籍</td>
            <td>重庆</td>
            <td>民族</td>
            <td>汉</td>
            <td>政治面貌</td>
            <td>共青团员</td>
        </tr>
        <tr align="center">
            <td>身体状况</td>
            <td></td>
            <td>婚姻状况</td>
            <td></td>
            <td>学历</td>
            <td></td>
        </tr>
        <tr align="center">
            <td>毕业学校</td>
            <td colspan="2"></td>
            <td>所学专业</td>
            <td colspan="2"></td>
        </tr>
        <tr align="center" class="body">
            <td>专业能力</td>
            <td colspan="7"></td>
        </tr>
        <tr align="center" class="body">
            <td>求职意向</td>
            <td colspan="7"></td>
        </tr>
        <tr align="center" class="body">
            <td>获奖情况</td>
            <td colspan="7"></td>
        </tr>
        <tr align="center" class="body">
            <td>自我评价</td>
            <td colspan="7"></td>
        </tr>
    </table>
</body>
</html>
