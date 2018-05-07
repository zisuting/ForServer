idea直接引入文件即可。
步骤如下：
1：File->Open->找到myFirst解压路径 点ok即可
右键LoginApplication 选择Debug 或者 Run都可以
如果报错，点开左上角File->Project Structure,然后选中左侧栏的Modules 中间栏选中myFirst
点击上方的加号，选择Import Module输入Login的路径点ok，在接下来的弹出框中选择Import mudule from external model
选择 Gralde点击Next，选择Use local gradle distribution ，Gradle home: 选择gradle的解压路径 Gradle JVM 选择jdk的路径
点击Finish 即可。