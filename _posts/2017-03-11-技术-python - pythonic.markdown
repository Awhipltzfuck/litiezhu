---
layout: post
title:  "pythonic"
date:   2017-03-11 22:24:49
categories: 技术
tags: 技术
---
1. if 10 < a <15:

	print 'ok'

2. if/else: text = '男' if gender == 'male' else '女'

3. #判断列表不为空:

	if values:
		do_something()

4. 字符串格式化：

s3 = "welcome to {blog} and following {wechat}".format(blog="foofish.net", wechat="vttalk")

5. 通过key分组：

groups = {}
for (key, value) in data:
    groups.setdefault(key, []).append(value) 

6. 字典推导式：（2.7之后）

numbers = [1, 2, 3]
my_dict = {number: number * 2 for number in numbers}
