## OpenSSL for Android

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)
[![Build](https://github.com/Webpage-gh/OpenSSL_for_Android/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/Webpage-gh/OpenSSL_for_Android/actions/workflows/build.yml)
![Release](https://img.shields.io/github/release/Webpage-gh/OpenSSL_for_Android)

为 Android ARM64 构建静态 OpenSSL

### 下载

您可以在[发布](https://github.com/Webpage-gh/OpenSSL_for_Android)中找到我上传的二进制文件并下载。

### 从 [openssl/openssl](https://github.com/openssl/openssl) 构建最新稳定发布

有时本仓库的发布中可能不是最新版本。此时您可以手动构建最新版，步骤如下：
1. 转到本存储库主页
2. 点击顶部的分叉图标（一个像叉子的图标）
3. 点击`Create fork`（创建分支）
4. 点击`Actions`（操作），它可能在右上角的更多图标里
5. 点击`I understand my workflows, go ahead and enable them`（我了解我的工作流程，继续并启用它们）
6. 点击`All workflows`（所有工作流程）
7. 点击`Build OpenSSL for ARM64`（为ARM64编译OpenSSL）
8. 点击`Run workflow`（运行工作流程）
9. 确认选中main分支（默认勾选仅分叉main分支，一般不会出错）后，再次点击`Run workflow`
等待约三分钟后，您可以从Artifacts（产物）看到两个文件。其中`openssl-android-arm64`是`make install`后所有文件的打包，`openssl-binary`是openssl静态可执行文件的打包，对于一般用户，下载`openssl-binary`即可
