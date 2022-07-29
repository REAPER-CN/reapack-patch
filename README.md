## 仓库介绍

该仓库存放 ReaPack 源上一些因各种原因长期未修复 bug 的脚本。

## 打补丁的脚本原则

1. 小修小补，不作功能新增，只依照原作者设计功能修复 bug。
2. 不对代码作格式化，只格式化新增或修改行，方便 diff。
3. 脚本描述在最后加上 **-REAPERCN** 作区分。
4. 定期和作者原版合并代码，如果原作者还有更新。
5. 若原作者已经把 bug 修复，则本仓库遗弃已修复的脚本。

## 打过补丁的脚本目录

遵循原脚本目录，为原作者文件夹加上 *_patch*，如：

```
├── me2beats_patch
│   └── Envelopes
│       └── me2beats_Paste envelopes to active takes of selected items.lua
```

## 版权说明

一切代码归属权属原作者。
