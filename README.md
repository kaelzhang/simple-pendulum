# simple-pendulum

A module to handle pendulum movements

## Install

```bash
$ cortex install simple-pendulum --save
```

<!--
Wrap examples with a pair of ```
使用成对的 ``` 来包裹示例。
代码块的 ``` 后面需要定义这部分代码的类型。比如上面的代码是 bash 脚本，常用的包括：
bash, js, json, html, css 等
-->


## Usage

```js
var pendulum = require('simple-pendulum');
var p = pendulum({
  max_angle: 90,
  max_angular_velocity: 200
});

p.when.angle(0).angular_velocity(); // 200
```


## License

The MIT License