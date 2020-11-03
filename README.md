# Florus

Florus is a piece of Javascript code applied to Scriptable App, displaying date, lunar date, weekday, year progress, weather, event reminder, and random motto, etc.

![](https://wt365.github.io/lib/florus/screenshot.jpg)

Florus是一则应用于Scriptable App的Javascript脚本，它可以在iOS14小组件中实现：

* 显示日期、星期、农历、全年进度
* 显示指定经纬度的即时天气状况、温度、雨带距离
* 显示预设事项的倒数天数
* 随机从一言数据库中显示一句话及出处
* （新增）显示指定的基金实时估值

### 食用方法

1. iOS14用户安装**Scriptable** App。
2. 打开App，点击右上角+号新建脚本，将florus.js中的代码复制后粘贴入。（基金版本请使用florus-funds.js。）
3. 将代码中的**经纬度**及**提醒事项/基金代码**改成你自己需要的，如果你有**彩云天气APIKey**，也推荐换成自己的（公用APIKey有每天请求次数限制，超过会显示与卫星失联）。
4. 点击左上角'Done'，保存脚本后可长按对其重命名（如Florus）。
5. 长按iOS14桌面空白处，点击左上角+号添加小组件，选择Scriptable，建议选择中尺寸。
6. 长按刚添加的组件，点击'编辑小组件'，Script处选择Florus即可。

### 注意事项

* 请自行修改**经纬度**设置，用于显示天气。
* **提醒事项**请手动在脚本里添加，可添加任意多行，无需按顺序，会自动排序后显示未来最近的指定条数。
* 基金版本无提醒事项，可设置一组**基金代码**，中尺寸最多显示三个，大尺寸最多显示六个。
* 彩云天气的公用APIKey有每天请求次数限制，如果你有自己的**彩云APIKey**，推荐将公用APIKey换成自己的。APIKey申请地址 https://dashboard.caiyunapp.com/user/sign_in/ 。
* 推荐使用**中尺寸**小组件。另外，作者机型为iPhoneXS，其他设备可自行适当调整字号大小。
* 农历暂支持2020年，2021年之前我会再更新一下。
* 作者比较懒，更多好玩的功能我想到了再慢慢加。
