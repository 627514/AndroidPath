# unity android 环境变量配置

配置Adb环境变量
![1735004016713](https://github.com/user-attachments/assets/706926be-63da-4873-ba85-338143d9cb05)

配置Java环境变量
新建系统变量名JAVA_HOME
![1735004195658](https://github.com/user-attachments/assets/2bcb3014-1a6a-46ac-86eb-95532fc95a07)

新建系统变量名CLASSPATH
           值.;%JAVA_HOME%\lib;%JAVA_HOME%\lib\tools.jar
![1735004270910](https://github.com/user-attachments/assets/625d9134-684e-43fa-b171-e40a8cbdc1d1)
在系统变量Path中新增 %ADB% 
在系统变量Path中新增 %JAVA_HOME%\bin

![1735004416852](https://github.com/user-attachments/assets/564fcf5f-2330-4cee-a052-95c84cfb1131)
