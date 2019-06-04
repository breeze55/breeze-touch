
## breeze-touch

这是一个基于原生JavaScript开发的简单自定义滑动插件

## 版本

0.0.0

## 安装

使用npm下载源文件


```
npm install breeze-touch --save
```

直接使用script引用

```js
<script src="../dist/breeze-touch-0.0.0.min.js"></script>
```

## 使用

```js
<script>
  var boxHeight = document.getElementById('box').clientHeight;
  var windowHeight = window.innerHeight;
  var slideDistance = boxHeight - windowHeight;
  breezeTouch({
    pickerSlide: box,
    slideDistance: slideDistance
  });
</script>
```

## 参数
```
```

|        参数       |   类型   | 默认值  |             说明             |
|-------------------|----------|----------|-------------------------------------|
| pickerSlide              | String    | “”       | 待滑动盒子          |
| slideDistance              | String    | “”       | 滑动最大值          |

## 演示

[demo](https://breeze55.github.io/breeze-touch/example/demo.html)

```
如果你感觉好用，欢迎给我打赏
```
![avatar](https://raw.githubusercontent.com/breeze55/static/master/breeze.png)

## License
[MIT](https://github.com/breeze55/breeze-touch/blob/master/LICENSE)
