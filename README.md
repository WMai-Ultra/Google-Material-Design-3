为不支持Google Material Design 3的应用[apk]添加取色
此处使用WeChat作为示例


打开原软件安装包 选resources.arsc 选Arsc编辑器
进入Arsc编辑器选最下方包名
就不用图片了 包名-color-color
然后用MT管理器的过滤 输入复制好的原颜色进行筛选 
依然是包名-color-color 然后右上角添加将复制好的输入进去
然后点击项目有类型和数值
Color就是固定颜色了这个自己选颜色
Ref
参考浅色0106002C强调色0106003F一路保存退出
然后修改Arsc编辑器内的包名
举例monet.com.需要取色的应用的包名
再修改AndroidManifest.xml选字符常量池
过滤com.xxx.xxx包名将com.改为要取色应用的包名将monet.com.xxx.xxx改为monet.com.改为取色应用的包名 
