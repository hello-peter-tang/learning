# learning

源码阅读与技术笔记。按项目分目录，每个子目录的 `README.md` 是该项目的索引。

| 主题 | 本地路径 | 状态 | 最后更新 |
| --- | --- | --- | --- |
| [vllm](./vllm/) | `/root/workspace/vllm` | 进行中 | 2026-11-08 |
| [sglang](./sglang/) | `/root/workspace/sglang` | 未开始 | — |
| [daft](./daft/) | `/root/workspace/daft` | 未开始 | — |
| [lance](./lance/) | `/root/workspace/lance` | 未开始 | — |

## 约定

- 一篇笔记一个文件，命名 `NN-主题.md`，序号只承担排序作用
- 每篇开头三行：一句话结论 / 涉及的模块 / 尚未验证的问题
- 引用源码用 permalink：在 GitHub 上按 `y` 切到 commit 视图后再复制带行号的链接，不写裸行号，避免上游提交后坐标漂移
- 数学推导直接写 `$$...$$`，GitHub 原生渲染，不需要额外构建
- 状态只有三种：未开始 / 进行中 / 已完成
