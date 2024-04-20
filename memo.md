## style.css 的两种表现方法

1.  在.html 文件里面直接加入 style
    <!DOCTYPE html>
    <html lang="en">
      <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0" />
        <title>Document</title>

        <style></style>
        <title></title>

      </head>
      <body>
        <h1>JavaScript is Fun!</h1>
        <p class="first">learn basic ideas of HtmL ans Css</p>
        <h2>Another heading</h2>
        <p class="second">Just another paragraph</p>
        <img src="" alt="" />
      </body>
    </html>

2.  新建 style.css 文件，写入；在.html 文件里面 link
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link href="style.css" rel="stylesheet" />
  <title>Learning HTML & CSS</title>
</head>
