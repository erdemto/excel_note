# excel_note
store some excel knowledge point.


将换行符和回车符替换为 <br>
=SUBSTITUTE(SUBSTITUTE(AT2,CHAR(10),"<br>"),CHAR(13),"<br>")
将日期格式转换为时间戳
=（B1-70*365-19）*86400-8*3600
