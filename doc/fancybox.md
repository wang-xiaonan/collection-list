## FancyBox参考手册

参考地址[FancyBox的使用技巧 (汇总)](http://www.cnblogs.com/qinpengming/archive/2013/05/26/3099848.html)

js:

```javascript
$.fancybox.open({
        padding:8,
        href:"#zzjg-img"
      });
```



**属性说明：** 

| 属性名                         | 默认值                    | 简要说明                                     |
| --------------------------- | ---------------------- | ---------------------------------------- |
| padding                     | 10                     | 浏览框内边距，和css中的padding一个意思                 |
| margin                      | 20                     | 浏览框外边距，和css中的margin一个意思                  |
| opacity                     | false                  | 如果为true，则fancybox在动画改变的时候透明度可以跟着改变       |
| modal                       | false                  | 如果为true，则'overlayShow' 会被设成 'true' ， 'hideOnOverlayClick', 'hideOnContentClick', 'enableEscapeButton', 'showCloseButton' 会被设成 'false' |
| cyclic                      | false                  | 如果为true，相册会循环播放                          |
| scrolling                   | 'auto'                 | 设置overflow的值来创建或隐藏滚动条，可以设置成 'auto', 'yes', or 'no' |
| width                       | 560                    | 设置iframe和swf的宽度，如果 'autoDimensions'为 'false'，这也可以设置普通文本的宽度 |
| height                      | 340                    | 设置iframe和swf的高度，如果 'autoDimensions'为 'false'，这也可以设置普通文本的高度 |
| autoScale                   | true                   | 如果为true，fancybox可以自适应浏览器窗口大小             |
| autoDimensions              | true                   | 在内联文本和ajax中，设置是否动态调整元素的尺寸，如果为true，请确保你已经为元素设置了尺寸大小 |
| centerOnScroll              | false                  | 如果为true，当你滚动滚动条时，fancybox将会一直停留在浏览器中心    |
| ajax                        | { }                    | 和jquery的ajax调用选项一样 注意: 'error' and 'success' 这两个回调事件会被fancybox重写 |
| swf                         | {wmode: 'transparent'} | swf的设置选项                                 |
| hideOnOverlayClick          | true                   | 如果为true则点击遮罩层关闭fancybox                  |
| hideOnContentClick          | false                  | 如果为true则点击播放内容关闭fancybox                 |
| overlayShow                 | true                   | 如果为true，则显示遮罩层                           |
| overlayOpacity              | 0.3                    | 遮罩层的透明度（范围0-1）                           |
| overlayColor                | '#666'                 | 遮罩层的背景颜色                                 |
| titleShow                   | true                   | 如果为true，则显示标题                            |
| titlePosition               | 'outside'              | 设置标题显示的位置.可以设置成 'outside', 'inside' 或 'over' |
| titleFormat                 | null                   | 可以自定义标题的格式                               |
| transitionIn, transitionOut | 'fade'                 | 设置动画效果. 可以设置为 'elastic', 'fade' 或 'none' |
| speedIn, speedOut           | 300                    | fade 和 elastic 动画切换的时间间隔, 以毫秒为单位         |
| changeSpeed                 | 300                    | 切换时fancybox尺寸的变化时间间隔（即变化的速度），以毫秒为单位      |
| changeFade                  | 'fast'                 | 切换时内容淡入淡出的时间间隔（即变化的速度）                   |
| easingIn, easingOut         | 'swing'                | 为 elastic 动画使用 Easing                    |
| showCloseButton             | true                   | 如果为true，则显示关闭按钮                          |
| showNavArrows               | true                   | 如果为true，则显示上一张下一张导航箭头                    |
| enableEscapeButton          | true                   | 如果为true，则启用ESC来关闭fancybox                |
| onStart                     | null                   | 回调函数，加载内容是触发                             |
| onCancel                    | null                   | 回调函数，取消加载内容后触发                           |
| onComplete                  | null                   | 回调函数，加载内容完成后触发                           |
| onCleanup                   | null                   | 回调函数，关闭fancybox前触发                       |
| onClosed                    | null                   | 回调函数，关闭fancybox后触发                       |

