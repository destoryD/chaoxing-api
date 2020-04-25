# chaoxing-api
超星/超星尔雅/智慧树题库查题接口API
更新时间: 2020/4/25 14:30:32
# 接口格式
http://blog.vcing.top/api.php?key=chaoxing&q={问题}
例如：
http://blog.vcing.top/api.php?key=chaoxing&q=大学生心理健康
# 返回格式
目前返回的为HTML格式
换行符为<br>
题目:xxxxx<br>
答案:xxxxx
# JSON接口格式
http://blog.vcing.top/japi.php?key=chaoxing&q={问题}
例如：
http://blog.vcing.top/japi.php?key=chaoxing&q=大学生心理健康
# 返回格式
目前返回的为JSON格式
{"title":"大学生心理健康标准","answer":"以上全是","code":"1"}

code为字符串格式，如果为0则未查询到答案，详情在title里

#看完请记得点个star谢谢
