# 留言板

<!DOCTYPE html>

<html lang="en">

<head>

  <meta charset="UTF-8">

  <title>FORM Text</title>

  <link rel="stylesheet" id="templatecss" type="text/css" href="css/basic-grey.css">

</head>

<body>

  <form action="" method="post" class="basic-grey">

    <h1>留言板

      <span>请您填写以下信息</span>

    </h1>

    <label>

      <span>姓名:</span>

      <input id="name" type="text" name="name" placeholder="请输入您的姓名" />

    </label>

    <label>

      <span>电话:</span>

      <input id="name" type="text" name="name" placeholder="请输入您的电话" />

    </label>
    <label>

      <span>邮箱:</span>

      <input id="email" type="email" name="email" placeholder="请输入您的邮箱" />

    </label>



    <label>

      <span>留言:</span>

      <textarea id="message" name="message" placeholder="请输入您的留言"></textarea>

    </label>

    <!--<input type="date" name="date" id="date" placeholder="留言时间"/>&ndash;&gt;-->

    <label>

      <span>日期:</span>
      <input type="date" name="date" id="date" placeholder="留言时间" />
      <label>

        <span>&nbsp;</span>

        <input type="button" class="button" value="Send" />

      </label>

  </form>


</body>

</html>
