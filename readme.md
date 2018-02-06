# 人脸识别测试版本V2

## Introduction

v2版本主要完成实现功能有base64转Mat，人脸检测,人脸特征提取以及人脸对比<br>

### v2结构

V2<br>
>image/存放base64解码后图片<br>
>example/测试例子<br>
>>*.txt/base64码以及对比后的结果<br>
>>*.h/外部头文件<br>
>>test.cpp/测试代码<br>
>>CMakeLists.txt/cmake文件

>lib/动态库<br>
>Models/模型文件<br>
>readme.md<br>

### 运行
#### 人脸1v1
```
cd GZT_TEST/VERSION_2/example/build
cmake ..
cd ..
./demo ../Models/

