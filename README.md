# haomai-libtv-operator-releases

好麦口播技能包与独立听写模型的公开发布仓库，不包含组资料、凭据或好麦源码。

当前技能版本：[V1.3.5](https://github.com/chenjiale364-crypto/haomai-libtv-operator-releases/releases/tag/V1.3.5)。需要好麦 0.2.27 或更高版本，在好麦口播页查看并安装技能更新。正在制作任务时先完成并登记，再安装更新；安装器会校验文件并备份旧技能。

- 固定更新源：[skill-release.json](https://github.com/chenjiale364-crypto/haomai-libtv-operator-releases/releases/latest/download/skill-release.json)。
- 技能 ZIP、更新清单和 SHA256SUMS.txt 放在技能版本 Release，技能版本设为 latest。
- 听写模型使用 `asr-<ZIP SHA256>` 独立版本，包含模型、来源与许可，不设为 latest。更新清单引用固定模型地址，内容一致时复用已安装模型。
- 下载文件的大小与 SHA256 以更新清单和对应 Release 的 SHA256SUMS.txt 为准。

好麦应用安装包与自动更新：[haomai-desktop-releases](https://github.com/chenjiale364-crypto/haomai-desktop-releases/releases/latest)。
