# chaoxing-api

超星/超星尔雅/智慧树题库查题接口API
更新时间: 2020/4/26 15:50:32

# 域名备案掉了，原域名80端口不能使用，现在一律改用新域名test.vcing.top
# 接口格式

http://test.vcing.top:81/api.php?key=chaoxing&q={问题}
例如：
http://test.vcing.top:81/api.php?key=chaoxing&q=大学生心理健康

# 返回格式

目前返回的为HTML格式
换行符为<br>
题目:xxxxx<br>
答案:xxxxx

# JSON接口格式

http://test.vcing.top:81/japi.php?key=chaoxing&q={问题}
例如：
http://test.vcing.top:81/japi.php?key=chaoxing&q=大学生心理健康

# 返回格式

目前返回的为JSON格式

{"title":"大学生心理健康标准","answer":"以上全是","code":1}

code更改为数字，如果为0则未查询到答案，详情在title里

#本项目采用MIT  License，如若第三方个人，机构将其二次开发，用于营利性业务或提供营利性服务，所产生的的各类纠纷，法律问题，均由其本人承担,与开发者团队无关。

