# moro

> 跟踪工作时间

- 调用“moro”(不带参数)，将当前时间设置为工作日的开始时间：

`moro`

- 指定工作日开始的自定义时间：

`moro hi {{09:30}}`

- 第二次调用“moro”时不带参数，以在工作日结束时设置当前时间：

`moro`

- 指定工作日结束的自定义时间：

`moro bye {{17:30}}`

- 在当前工作日添加备注：

`moro note {{3 hours on project Foo}}`

- 显示当前工作日的时间日志和备注报告：

`moro report`

- 显示记录中所有工作日的时间日志和备注报告：

`moro report --all`

[#]: contributors: ([潘潘]，[爱生活])