该包的原始开发人员为 [qinwf](https://github.com/qinwf/)，不知为什么在 github 上项目下线。

Fork 以保持备份。

# OpenCC  開放中文轉換 R 语言接口

Linux : [![Build Status](https://travis-ci.org/qinwf/ropencc.svg?branch=master)](https://travis-ci.org/qinwf/rpoencc)　Mac : [![Build Status](https://travis-ci.org/qinwf/ropencc.svg?branch=osx)](https://travis-ci.org/qinwf/ropencc)　Win : [![Build status](https://ci.appveyor.com/api/projects/status/db2nv83wk97x6mwj/branch/master?svg=true)](https://ci.appveyor.com/project/qinwf/ropencc/branch/master)


Windows 用户需要安装 RTools，https://cran.r-project.org/bin/windows/Rtools/ ，安装时注意 PATH 的设置。

```r
devtools::install_github("sunbjt/ropencc")

converter(S2T)["开放中文转换"]
converter(S2TW)["一条信息"]
converter(S2TWP)["一条信息"]
converter(S2HK)["一条信息"]
converter(T2S)["開放中文轉換"]
converter(T2HK)["開放中文轉換"]
converter(T2TW)["開放中文轉換"]
converter(TW2S)["開放中文轉換"]
converter(TW2SP)["一條資訊"]
converter(HK2S)["開放中文轉換"]

cc = converter(HK2S)
run_convert(cc, "開放中文轉換")
```
