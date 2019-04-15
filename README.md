# Mybatis-generator
Mybatis逆向工程代码
1.编辑generatorConfig.xml
2.直接在当前目录下 shift+右键，点击在此处打开命令行窗口（Win10 打开 powerShell 窗口）。
3.输入以下命令即可执行成功：
java -jar mybatis-generator-core-1.3.2.jar -configfile generatorConfig.xml -overwrite
4.在当前目录的 src 目录下就会生成对应的实体类、映射文件和接口文件，注意得有 src 文件夹.
