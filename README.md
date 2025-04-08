[![Draw Keymap](https://github.com/marcel-trabolt/zmk-new_corne/actions/workflows/draw.yml/badge.svg)](https://github.com/marcel-trabolt/zmk-new_corne/actions/workflows/draw.yml)


- [中文](README.md)
- [English](README_EN.md)

# 睫毛外设 (Eyelash Peripherals) Corne ZMK 仓库

**该键盘与 [foostan's Corne](https://github.com/foostan/crkbd) 不同，无法与标准的 `corne` 固件兼容。**

![睫毛外设 Corne 的照片](https://ae01.alicdn.com/kf/Sa797fee25edd44248fbfdb0e13d44e00B.jpg)

如果您需要该键盘的 3D 模型，请发送电子邮件至 `380465425@qq.com`。

## 使用说明

1. [叉取此仓库](https://docs.github.com/en/get-started/quickstart/fork-a-repo#forking-a-repository)。
2. [点击 **Actions** 选项卡，确保工作流已启用](https://docs.github.com/en/actions/managing-workflow-runs-and-deployments/managing-workflow-runs/disabling-and-enabling-a-workflow#enabling-a-workflow)。
3. 确保 [`config/west.yml`](config/west.yml) 中的 `eyelash_corne` 项目仍然有效。`boards/arm/eyelash_corne` 文件夹将从此 URL 下载。
4. 如果您的叉取中仍存在 `boards/arm/eyelash_corne` 文件夹，请将其删除。

**如果您已经有 ZMK 配置仓库，[您可以将此作为模块添加，而不是叉取](https://zmk.dev/docs/features/modules#building-with-modules)。**

## Corne 键位图

![Diagram of config/eyelash_corne.keymap](keymap-drawer/eyelash_corne.svg "generated by @caksoylar's Keymap Drawer")
