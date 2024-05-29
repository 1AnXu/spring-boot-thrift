步骤
1. 在`src/main/resources/thrift`目录下编写`[filename].thrift`文件
2. 使用`thrift -r -gen java [filename].thrift`命令在`resources`目录下生成`java`文件
3. 将`java`文件移动到`[filename].thrift`所定义的`namespace`空间所对应的`package`下
4. 编写服务端实现类`[filename]ServiceImpl`
5. 编写服务端和客户端启动类