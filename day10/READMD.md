### day10
### 效果图
<img src="./day10.gif"/>

### 启动
1.npm i anywhere -g
2.进入day10目录在cmd或者终端输入anywhere回车
3.在页面打开返回返回的链接
4.点击day10.html
### 调试scss
1. 安装sass: npm i sass -g
2. 终端进入day10
3. 执行sass --watch ./day10.scss ./day10.css
4. 保存scss时会自动更新css

### 知识点
1. transform-origin;

```scss
// 改变元素中心
{
    //0 0位于元素的左上角，100% 100%位于元素的右下角,param1代表x轴偏移,param2代表y轴偏移
    //默认
    transform-origin:center center//等同于50% 50%
    
}
```