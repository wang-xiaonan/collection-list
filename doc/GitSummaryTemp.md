### Git Summary Template

​	git 提交模板，个人总结

> <type>(<scope>) : <subject>
>
> <空行>
>
> <body>
>
> <空行>
>
> <footer>



- type 提交类型

  > add：新增功能
  >
  > fix：修补Bug
  >
  > doc：文档编写
  >
  > style：格式！注意是格式，不影响代码运行的变动
  >
  > refactor：重构老功能代码变动，不是修改bug也不是新增
  >
  > test：增加测试

- scope 模块

  > 修改所在模块，具体由项目而定，可以分成功能模块，也可以分成级别等

- subject 问题概括描述

  > 尽少的字数描述问题，可以是填Issue ID等，不要超过50字。控制在30字以内

- body 修改详细描述

  > 具体的修改信息 应该尽量详细
  >
  > 应该分条阐述，尽量清晰

- footer 备注

  >  可以写备注信息



使用工具时注意大体的格式就可以，使用git提交时注意尽量不要用`git commit -m "....."`或者`git commit --message "....."` ，可以添加自己的模板或者提交时编辑