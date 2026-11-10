# 开发分工与 Obsidian 协作

`define-dev-roles` 是一个 Codex Skill，用于按项目需要拆分职能和负责对话，再用 Obsidian 记录派工、交付、提测、复测和验收。

## 获取与使用

```sh
git clone https://github.com/liaoqq123/define-dev-roles.git
```

将克隆得到的 `define-dev-roles` 文件夹放进 Codex 使用的个人 Skills 目录，保持 [SKILL.md](SKILL.md) 在该文件夹顶层。打开项目后可以这样发起任务：

> 用 $define-dev-roles 为当前项目建立分工，把 Obsidian 协作笔记放在项目内的 obsidian 文件夹。每个职能单独一页。

也可以把 [Obsidian 起步模板](assets/obsidian) 复制到自己的库，在 Obsidian 中打开 `项目协作.md`，登记实际负责对话、职责范围和验收条件。根据项目需要保留或细分职能，并同步修改关系网与收件索引。

## 交接规则

- 统筹按职能派工，为开发工作指定测试及验收条件。
- 制作方把资源与规格交给指定开发。开发每项工作完成后直接向指定测试提测，修复后沿相同路径提请复测。
- 独立测试的接收确认、缺陷、阻塞和验收结论只发给统筹，由统筹安排后续分派。

完整交接方向和记录字段见 [职能关系网](references/role-network.md)，排查方法见 [制作常见问题](references/production-pitfalls.md)。
