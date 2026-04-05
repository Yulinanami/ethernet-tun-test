# Throne Windows Quick Build

这个仓库只用于在 GitHub Actions 上快速构建上游 `throneproj/Throne` 的最新 Windows 版本。

它不再维护 Throne 源码副本，手动触发 `.github/workflows/quick-windows-test.yml` 后，会直接拉取上游 `main` 分支并完成构建。

## 用法

1. 打开 GitHub Actions。
2. 运行 `Quick Windows Test Build`。
3. 等待产物上传完成。

构建产物名称会带上上游提交的短 SHA，方便区分版本。
