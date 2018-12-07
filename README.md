# brew update gradle with version

## 参考文档

[homebrew 安装指定版本gradle（软件）](https://www.jianshu.com/p/a537d9a4034f)

[脚本源地址](https://github.com/Homebrew/homebrew-core/blob/master/Formula/gradle.rb)

## 步骤总结

- 下载地址：[Gradle Build Tool Releases](https://gradle.org/releases/)

- 获取文件sha256：`openssl dgst -sha256 gradle-4.1-all.zip`

- 修改gradle.rb里面的url和sha256

- `brew unlink gradle`

- `brew install ./gradle.rb`