  # Liuying Open Source Notices and Corresponding Source

  本仓库用于发布“流影”应用使用的第三方开源组件的许可证声明、对应源码、修改补丁和构建脚本。

  本仓库不是“流影”应用的完整源码仓库，也不表示“流影”应用本身采用开源许可证。

  ## Releases

  每个 Release 对应一个实际发布的“流影”应用版本。

  ### v1.0.0

  对应应用版本：`1.0.0`

  下载文件：

  - `liuying-1.0.0-mpv-lgpl-corresponding-source.tar.gz`
  - `liuying-1.0.0-mpv-lgpl-corresponding-source.tar.gz.sha256`

  源码包 SHA-256：

  ```text
  d6bd6eefe1dca9ce5d87e70ecb43aeea7609fd1c7c6c6cbff5d03bd5957e514e
  ```

  下载地址：

  https://github.com/Alone4869/liuying-open-source/releases/tag/v1.0.0
  (https://github.com/Alone4869/liuying-open-source/releases/tag/v1.0.0)

  ## Included Components

  v1.0.0 对应源码包包含以下组件的固定版本源码及许可证：

  - mpv 0.41.0
  - FFmpeg 8.0.1
  - FreeType 2.14.1
  - FriBidi 1.0.16
  - HarfBuzz 11.2.1
  - libass 0.17.5
  - libplacebo 7.360.1
  - fast_float commit 97b54ca9e75f5303507699d27c6b4f4efe4641a1

  源码包还包含：

  - 流影项目使用的 HarmonyOS 适配补丁
  - OHCodec 解码相关补丁
  - OHAudio 适配代码
  - HarmonyOS 交叉编译配置
  - 可重复构建脚本
  - 第三方许可证和版权声明
  - libmpv 重建与替换说明

  ## Building

  解压对应源码包后，先阅读：

  - RELINKING.md
  - THIRD_PARTY_NOTICES.md
  - tools/mpv/README.md

  准备 HarmonyOS Native SDK，然后在源码包根目录运行：

  tools/mpv/build.sh

  如果 SDK 不在默认位置，请设置：

  export OHOS_NDK=/path/to/openharmony/native

  ## Licensing

  各第三方组件继续按照其源码目录和源码包中附带的许可证授权，不存在适用于全部第三方源码的单一许可证。

  本仓库原创的发布说明、归档脚本和构建辅助材料按照仓库根目录 LICENSE 中的条款提供。

  “流影”应用的专有业务源码、名称、图标、界面素材及其他未明确发布的内容，不因本仓库而获得开源授权。

  ## Source Requests

  如果 Release 附件无法下载，或需要确认某个应用版本对应的源码，可通过本仓库的 Issues 联系维护者。
