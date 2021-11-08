
# Androguard

原始androguard项目很长时间没动了，不得不自己动手

## 目的

实际分析apk过程中，会发现很多apk使用了对抗静态分析的方法，比如修改zip文件加密字节，伪装成加密zip文件使分析失败，而apk安装时会忽略这些无用字节，使apk能够正常安装运行

这个版本androguard将默认所有待分析的文件都是apk格式，尽可能忽略不必要的信息防止对抗

个人修改，可能会有很多bug，没精力做全面测试，遇到再说咯~~


## 原始作者

Androguard + tools: Anthony Desnos (desnos at t0t0.fr).

DAD (DAD is A Decompiler): Geoffroy Gueguen (geoffroy dot gueguen at gmail dot com)

## 原始文档

Find the documentation for master on [ReadTheDocs](http://androguard.readthedocs.io/en/latest/).

There are some (probably broken/outdated) examples and demos in the folders [demos](https://github.com/androguard/androguard/tree/master/demos) and [examples](https://github.com/androguard/androguard/tree/master/examples).


## Licenses

### Androguard

Copyright (C) 2012 - 2016, Anthony Desnos (desnos at t0t0.fr)
All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS-IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

### DAD

Copyright (C) 2012 - 2016, Geoffroy Gueguen (geoffroy dot gueguen at gmail dot com)
All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS-IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
