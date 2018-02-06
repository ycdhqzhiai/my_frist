# 人脸识别测试版本V1


## Introduction

v1版本主要完成实现功能有base64转Mat，人脸检测，活体检测，人脸特征提取以及人脸对比<br>

### v1结构

V1<br>
>base64Toimg/存放base64解码后图片<br>
>example/测试例子<br>
>>*.txt/base64码以及对比后的结果<br>
>>*.h/外部头文件<br>
>>test.cpp/测试代码<br>
>>run.sh/编译脚本<br>
>>tmp/活体检测测试<br>

>image/对比用的一些图片<br>
>lib/动态库<br>
>model/模型文件<br>
>readme.md<br>

### 运行
```
cd GZT_TEST/VERSION_1/example/
./run.sh
./demo ../model/mergeModel_40/
或者
./demo ../model/mergeModel_28/
```



