﻿English | [简体中文](./README_CN.md)

# AlloyTouch
super tiny size touch and physical motion library

* super tiny size 
* highly abstract 
* real touch feedback
* independent of style layout
* simple API design
* high efficiency movement
* real physical movement trace

# Install
```js
npm install alloytouch
```

# API
```js
new AlloyTouch({
            touch:"#wrapper",
            vertical: true,
            target: target, 
            property: "translateY", 
            min: 100, 
            max: 2000, 
            sensitivity: 1,
            factor: 1,
            spring: true,
            step: 45,
            change:function(){  }, 
            touchStart:function(value){  },
            touchMove:function(value){  },
            touchEnd:function(value){  },
            animationEnd:function(value){  } 
 })
```
# Demo(Mobile)

- Simple Demo: [http://alloyteam.github.io/AlloyTouch/](http://alloyteam.github.io/AlloyTouch/) 
- 3D Demo: [http://alloyteam.github.io/AlloyTouch/3d.html](http://alloyteam.github.io/AlloyTouch/example/3d.html) 
- Rotate Demo: [http://alloyteam.github.io/AlloyTouch/rotate.html](http://alloyteam.github.io/AlloyTouch/example/rotate.html) 
- Carousel Demo: [http://alloyteam.github.io/AlloyTouch/carousel.html](http://alloyteam.github.io/AlloyTouch/example/carousel.html) 

# Many thanks to 
- [transformjs](http://alloyteam.github.io/AlloyTouch/transformjs/)

# Who is using AlloyTouch?

![preview](http://sqimg.qq.com/qq_product_operations/im/qqlogo/imlogo.png)

# License
This content is released under the [MIT](http://opensource.org/licenses/MIT) License.
