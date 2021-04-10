# Eclipse 配置

## 导入、导出
- 导出：`File -> Export -> General -> Prefereces`
  - 取消 `Export all` 勾选，选择 `Code Style` 和 `Keys` 就行
  - 保存为 `.epf` 结尾的文件
- 导入：`File -> Import -> General -> Prefereces`

## 快捷键
- 打开调用栈：`Ctrl + Alt + H`
- 调试-运行到光标定位的行：`Ctrl + R`

## Lombok 插件
1. 在 `eclipse` 根目录下创建 `my-plugin` 文件夹，并复制 `lombok-1.18.6.jar` 到此目录
2. 在 `eclipse.ini` 下添加下面两行
```
-Xbootclasspath/a:my-plugin/lombok-1.18.6.jar
-javaagent:my-plugin/lombok-1.18.6.jar
```

## 编码 UTF-8
- 参考：https://blog.csdn.net/qq_20936333/article/details/81322007