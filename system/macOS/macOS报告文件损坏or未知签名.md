# 解决macOS报告文件损坏/未知签名的错误

Created: December 8, 2021 9:08 PM

```shell
$ xattr -cr /Applications/Signal.app
```

The -c flag removes all attributes(属性), whereas -r applies recursively(递归) for the entire targeted .app directory contents.