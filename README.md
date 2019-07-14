# JS-循环

本练习由几个小练习组成，每个小练习都有各自的readme，大家可以前去查看。

## 作业要求
- fork本仓库
- 按照readme要求完成作业
- 将作业提交到github，把github地址提交回系统

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
<script>
  var i , j;
            for(i = 1;i <= 9;i ++){
                document.write("<br>");               // i 为行的乘数，j 为列数  每一行打印完后换行
                for(j = 1;j <= i;j ++){
                    sum = i * j;
                    document.write(i ,"*",j ,"=",sum,"   ");     // 使 "i" 和 "j" 能打印出来
                }
            }
  </script>
  </head>
  <body>
  </body>
  </html>
