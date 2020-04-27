# chaoxing-api

超星/超星尔雅/智慧树题库查题接口API
更新时间: 2020/4/27 13:43:10

声明:本接口并非从超星获取答案，而是从搜集而来的题目数据库中搜索！

# 已更换新服务器，原接口和现有接口均已恢复正常
# 接口格式

原接口:http://blog.vcing.top/api.php?key=chaoxing&q={问题}
http://test.vcing.top:81/api.php?key=chaoxing&q={问题}
例如：
http://test.vcing.top:81/api.php?key=chaoxing&q=大学生心理健康

# 返回格式

目前返回的为HTML格式
换行符为<br>
题目:xxxxx<br>
答案:xxxxx

# JSON接口格式

原接口:http://blog.vcing.top/japi.php?key=chaoxing&q={问题}
http://test.vcing.top:81/japi.php?key=chaoxing&q={问题}
例如：
http://test.vcing.top:81/japi.php?key=chaoxing&q=大学生心理健康

# 返回格式

目前返回的为JSON格式

{"title":"大学生心理健康标准","answer":"以上全是","code":1}

code更改为数字，如果为0则未查询到答案，详情在title里

#本项目采用MIT  License，如若第三方个人，机构将其二次开发，用于营利性业务或提供营利性服务，所产生的的各类纠纷，法律问题，均由其本人承担,与开发者团队无关。

