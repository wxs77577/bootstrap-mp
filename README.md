# bootstrap-mp
Bootstrap 小程序版

基于 Bootstrap 4.3，生成的css文件71kb左右。

### 安装
- `npm i bootstrap-mp`
- `import 'bootstrap-mp'`

或者直接复制文件内容 [https://github.com/wxs77577/bootstrap-mp/blob/master/dist/bootstrap-mp.css](https://github.com/wxs77577/bootstrap-mp/blob/master/dist/bootstrap-mp.css)

### 移除了部分样式：
- reboot
- dropdown
- custom forms
- navbar
- breadcrumb
- pagination
- jumbotron
- tooltip
- popover
- carousel
- print

### 修改了部分样式
- 默认标签都设置了border-box样式。
- .nav-tabs 中高亮菜单样式改成了底部3px 橙色边框，更符合移动端偏好。

### 新增了部分样式
- .scroll-x 横向可滑动菜单条布局
- .fs-0 ~ .fs-4 更小的字体，对应 1rem、0.9rem、0.8rem、0.7rem、0.6rem

### 手动编译
- `git clone git@github.com:wxs77577/bootstrap-mp.git`
- `npm i`
- `npm i -g parcel`
- `npm run dev` 开启调试
- `npm run build`