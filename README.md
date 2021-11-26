# SingleFileExecutionPlugin
[CLion](https://www.jetbrains.com/clion/) plugin to execute single file .c/.cpp file quickly.

## Description
CLion is a C/C++ IDE on [IntelliJ IDEA](https://www.jetbrains.com/idea/) platform provided by [JetBrains](https://www.jetbrains.com/).

CLion is working on CMake platform, so when you want to run a single file with main() function you need to configure CMakeLists.txt file everytime.
This plugin helps you to add a configuration to quickly run a single .c/.cpp file.

---
forked from [corochann/SingleFileExecutionPlugin](https://github.com/corochann/SingleFileExecutionPlugin)

>Executable name 新增 %SAFEFILENAME% 关键词，去除FILENAME中的标点，并将中文转化为拼音，解决了标点和中文字符导致Cmake报错的问题